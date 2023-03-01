```mermaid
sequenceDiagram
actor me
me->>Save Button : CLICKS 
Save Button-->>me : Returning HTML , CSS and JS (Loading in Browser) 
Save Button->>Server: GET REQUEST for Adding note
Server-->>Save Button : Returning HTML , CSS and JS (Loading in Browser) 

Note right of Server: Processes and produces json


```