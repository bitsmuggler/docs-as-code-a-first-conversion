::: mermaid
sequenceDiagram
    actor user
    participant catalogueService
    participant database
    participant paymentService

    user ->> catalogueService: search
    catalogueService ->> database: select items
    database ->> catalogueService: selected items
    catalogueService ->> user: display item
:::