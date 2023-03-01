```mermaid
sequenceDiagram
WebApp->>Server: GET REQUEST
Server-->>WebApp: POST REQUEST!
Note right of Server: Processes and produces json
```