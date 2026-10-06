# LAB 02 – Car-Share Story Map

## Objective

Construct a **2D story map** for a digital peer-to-peer car-sharing application and extract the **Walking Skeleton MVP**.

---

## 1. 2D Story Map

| Release | Find a Car | Book a Car | Pick Up & Use | Return Car | Payment & Review |
|---|---|---|---|---|---|
| **MVP** | Search available cars | Select car and request booking | View pickup location | Confirm return | Pay for rental |
| **MVP** | View car details | Choose date/time | Pick up car | Mark trip completed | View receipt |
| **Release 2** | Filter by location/price | Receive booking confirmation | View trip details | Report problems | Rate car/owner |
| **Release 2** | View owner information | Cancel booking | Contact owner | Confirm car condition | Rate renter |
| **Release 3** | Save favorite cars | Modify booking | Digital key | Damage reporting | Dispute payment |
| **Release 3** | View availability calendar | Booking notifications | Trip tracking | Return reminders | Loyalty/rewards |

---

## 2. Story Map

```text
                    CAR-SHARE STORY MAP

Activities     Find Car     Book Car     Pick Up     Return     Payment
---------------------------------------------------------------------------
MVP            Search       Select       Pickup      Confirm    Pay
               cars         car          location    return     rental
                            & booking     & unlock

Release 2      Filters      Confirmation Trip        Report     Reviews
               Owner info   Cancellation  details     issues     & ratings

Release 3      Favorites    Modify        Digital     Damage     Disputes
               Calendar     booking       key         report     & rewards
---------------------------------------------------------------------------
                         TIME / PRIORITY

                         MVP → Later Releases
