```mermaid
sequenceDiagram
    participant Browser
    participant Server
    Note right of Browser: Creates a new note
    Note right of Browser: Re-renders the notes list
    Note right of Browser: Sends the note to server
    Browser->>+Server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    Note left of Server: Creates note
    Server-->>-Browser: HTTP 201 Created
```   




 