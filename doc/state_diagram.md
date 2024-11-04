# State Transition Diagrams

This document contains state transition diagrams for various parts of the system. The diagrams are created using mermaid syntax.

## Bank Statement Process

```mermaid
stateDiagram-v2
    [*] --> New
    New --> Imported : Import Bank Statement
    Imported --> Processed : Process Bank Statement
    Processed --> Completed : Complete Bank Statement
    Completed --> [*]
```

## Payment Process

```mermaid
stateDiagram-v2
    [*] --> New
    New --> Approved : Approve Payment
    Approved --> Paid : Pay Payment
    Paid --> Completed : Complete Payment
    Completed --> [*]
```

## Order Process

```mermaid
stateDiagram-v2
    [*] --> Drafted
    Drafted --> Completed : Complete Order
    Completed --> Closed : Close Order
    Closed --> [*]
```
