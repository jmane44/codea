```mermaid
flowchart TD

subgraph Legend
L1([Start/End - Oval])
L2[Process - Rectangle]
L3[/Input or Output - Parallelogram/]
L4{Decision - Diamond}
end

A([Start]) --> B[/Input Username & Password/]

B --> C{Credentials Valid?}

C -- No --> D[/Prompt Student To Try Again/]
D --> B

C -- Yes --> E{Account Holds?}

E -- Yes --> F[/Display Holds Must Be Resolved Message/]
F --> G([End])

E -- No --> H[Generate Course List]

H --> I[/Display Courses/]

I --> J[/Select Course ID/]

J --> K[/Select Section ID/]

K --> L{Prerequisites Met?}

L -- No --> M[/Display Prerequisite Not Met Message/]
M --> I

L -- Yes --> N{Open Seats > 0?}

N -- No --> O[/Display Section Full Message/]
O --> I

N -- Yes --> P[Enroll In Course]

P --> Q[/Confirm Enrollment/]

Q --> G
```
