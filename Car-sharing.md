# LAB 02 – Car-Share Story Map

## Objective

Construct a 2D story map for a digital peer-to-peer car-sharing application and extract the Walking Skeleton MVP.

---

## 1. Car-Share Story Map

The story map organizes the main activities of the car-sharing application horizontally and prioritizes user stories vertically.

| Priority | Find a Car | Book a Car | Pick Up & Use | Return Car | Payment & Review |
|---|---|---|---|---|---|
| **MVP** | Search available cars | Select car & request booking | View pickup location | Confirm return | Pay for rental |
| **MVP** | View car details | Choose date/time | Pick up car | Mark trip completed | View receipt |
| **Release 2** | Filter by location/price | Receive booking confirmation | View trip details | Report problems | Rate car/owner |
| **Release 2** | View owner information | Cancel booking | Contact owner | Confirm car condition | Rate renter |
| **Release 3** | Save favorite cars | Modify booking | Digital key/access | Damage reporting | Dispute payment |
| **Release 3** | View availability calendar | Booking notifications | Trip tracking | Automated return reminders | Loyalty/rewards |

---

## 2. Story Map Visualization

```text
                         CAR-SHARE STORY MAP
================================================================================

                         USER ACTIVITIES
--------------------------------------------------------------------------------
 Find a Car          Book a Car          Pick Up & Use       Return       Payment
--------------------------------------------------------------------------------
 Search cars         Select car          Pickup location     Confirm      Pay rental
 View car details    Choose date/time    Pick up car         Return car   View receipt
--------------------------------------------------------------------------------
                         MVP / WALKING SKELETON
================================================================================

 Find a Car          Book a Car          Pick Up & Use       Return       Payment
--------------------------------------------------------------------------------
 Filters             Confirmation       Trip details        Report       Reviews
 Owner information   Cancellation       Contact owner       problems     Ratings
--------------------------------------------------------------------------------
                         RELEASE 2
================================================================================

 Find a Car          Book a Car          Pick Up & Use       Return       Payment
--------------------------------------------------------------------------------
 Favorites           Modify booking     Digital key        Damage       Dispute
 Availability        Notifications      Trip tracking       reporting    Rewards
 calendar
--------------------------------------------------------------------------------
                         RELEASE 3
================================================================================

                         PRIORITY / TIME
                    MVP  →  Release 2  →  Release 3
