```mermaid
 sequenceDiagram
    participant Browser
    participant Server
    Browser->>+Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
    Server-->>-Browser: HTML file
    Browser->>+Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
    Server-->>-Browser: CSS file
    Browser->>+Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa.js
    Server-->>-Browser: JavaScript file
    Browser->>+Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
    Server-->>-Browser: JSON file
    Note right of Browser: Renders the notes
```   




 