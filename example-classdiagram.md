sequenceDiagram
    actor user
    participant catalogueService
    participant database

    user ->> catalogueService: search
    catalogueService ->> database: select items
    database ->> catalogueService: selected items
    catalogueService ->> user: display item