# LAB 02 – Car-Share Story Map

## 1. 2D Story Map

```mermaid
flowchart TB

    A["CAR-SHARE STORY MAP"]

    A --> B["FIND A CAR"]
    A --> C["BOOK A CAR"]
    A --> D["PICK UP & USE"]
    A --> E["RETURN CAR"]
    A --> F["PAYMENT & REVIEW"]

    B --> B1["MVP: Search Available Cars"]
    B --> B2["MVP: View Car Details"]
    B --> B3["Release 2: Filter by Location/Price"]
    B --> B4["Release 2: View Owner Information"]
    B --> B5["Release 3: Save Favorite Cars"]
    B --> B6["Release 3: View Availability Calendar"]

    C --> C1["MVP: Select Car & Request Booking"]
    C --> C2["MVP: Choose Date/Time"]
    C --> C3["Release 2: Booking Confirmation"]
    C --> C4["Release 2: Cancel Booking"]
    C --> C5["Release 3: Modify Booking"]
    C --> C6["Release 3: Booking Notifications"]

    D --> D1["MVP: View Pickup Location"]
    D --> D2["MVP: Pick Up Car"]
    D --> D3["Release 2: View Trip Details"]
    D --> D4["Release 2: Contact Owner"]
    D --> D5["Release 3: Digital Key/Access"]
    D --> D6["Release 3: Trip Tracking"]

    E --> E1["MVP: Confirm Return"]
    E --> E2["MVP: Mark Trip Completed"]
    E --> E3["Release 2: Report Problems"]
    E --> E4["Release 2: Confirm Car Condition"]
    E --> E5["Release 3: Damage Reporting"]
    E --> E6["Release 3: Return Reminders"]

    F --> F1["MVP: Pay for Rental"]
    F --> F2["MVP: View Receipt"]
    F --> F3["Release 2: Rate Car/Owner"]
    F --> F4["Release 2: Rate Renter"]
    F --> F5["Release 3: Dispute Payment"]
    F --> F6["Release 3: Loyalty/Rewards"]
## 3. Walking Skeleton MVP

```mermaid
flowchart TD
    A([Start]) --> B[Search Available Cars]
    B --> C[View Car Details]
    C --> D[Select Date and Time]
    D --> E[Confirm Booking]
    E --> F[View Pickup Location]
    F --> G[Pick Up Car]
    G --> H[Use Car]
    H --> I[Return Car]
    I --> J[Make Payment]
    J --> K[Booking Completed]
    K --> L([End])

