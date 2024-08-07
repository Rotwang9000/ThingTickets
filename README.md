# ThingTickets

# How was your experience developing on Fuse?
Dunno yet

#Idea....


**ThingTickets**
(avoid using "event" as this means a momentary thing that happens in computing, plus is too restrictive for expansion - For example with integration with HomeConnect it could be used to give permissions to IoT devices for temporary users like AirBNB, but with payment built in for adding optional extras... but I digress, "Thing" for now means things like concerts and gigs.
 
**Admin: (eg. event organiser)**
_Create Thing_
- Optional TIme, Date, Location

_Create Permissions_
- Optionally create ticket groups with default time/use values and prices.
- Webhook/ email notification

_Create Ticket _
- Ticket type is a set price with a set of permissions or permission groups either included in the price or added as optional extras. Optional Time/Date/Location restrictions either absolute or relative to Thing or purchase of extra.
eg.
Saturday ticket to weekend festival allows entrance to Festival only on Saturday and no entrance to campsite.
An optional single "Happy Hour" beer can be added for Midday until 1pm.
Generic "units" for payment can be loaded and spent (ie. Soft Drink 1 Unit, Beer/Cider 2 Units, Dirty Burger 3, etc)  - These units can be dynamically priced based on when purchased or what type of ticket.
VIP camp entrance (automated gates or checked by operator) can be added for the entire day, or can be added on the day for 2 hours from purchase time.
Admin/Operator might want to ad-hoc permit day ticket holders to the VIP either by manually adding or perhaps automatically based on automatic occupancy measurements.
Checking-in with GPS or QR at the time of a band can get a free sticker.

**Operator:  (eg. Security)**
Given Roles - ie. Front Door, Bar staff
_Door Staff _- Scan user signed ticket QR, get Green Light or Red. No Tapping. Pref some kind of ZKProof added so that to check the ticket, no connection is required. Notifications can be queued up and sent when they can.
- Optionally shows identity proof which can be automatically checked or just visually checked by staff. Staff can scan a required ID at time of entrance.
_Bar staff_, Enter products/amount of units, Customer scans a QR, signs and displays their QR to staff (or a unit) - Account is checked and payment taken if required... this can be done without the customer having any signal... or for unlimited free things they can do the signed ticket like above.

**Customer**
Can buy tickets, add identification documents and identity services, add ons, view account, zkproof sign purchased tickets, sign purchase requests
Whilst there should be separate ticket codes/QR, everything should be able to be done with a single code - In a festival scenario, a customer may have lost their phone, or be too rainy to use, have no signal etc, or may just be privacy conscious on the grounds. They can be given a RF card to prove their ID and have to enter a PIN on a terminal if a transaction is to be signed... this can remove the need for touchscreens

