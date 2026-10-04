# System Flow Diagram

## Student Support Flow

```mermaid
flowchart TD
    A[Student Login] --> B[Support Portal]
    B --> C[Search Knowledge Base]
    C --> D{Problem Solved?}
    D -->|Yes| E[End]
    D -->|No| F[Create Ticket]
    F --> G[Ticket Assigned]
    G --> H[Support Staff]
    H --> I[Troubleshooting]
    I --> J[Solution Provided]
    J --> K[Student Feedback]
    K --> L[Ticket Closed]
    L --> E
```

## Explanation

1. Student logs into the support portal.
2. Student searches the Knowledge Base.
3. If a solution is available, the student solves the problem.
4. If the problem is not solved, a support ticket is created.
5. The ticket is assigned to support staff.
6. Support staff investigates the problem.
7. A solution is provided.
8. The student provides feedback.
9. The ticket is closed.
