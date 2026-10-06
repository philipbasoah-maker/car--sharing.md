## 3. Walking Skeleton MVP

The Walking Skeleton is the smallest working system that connects the major parts of the car-sharing application from beginning to end.

### Car-Share MVP Flowchart

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
