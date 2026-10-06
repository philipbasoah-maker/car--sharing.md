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
