# 18. Entity Relationship Diagram (ERD)

```mermaid
erDiagram
    USERS {
        int id PK
        string username
        string password_hash
    }
    SUBSCRIPTIONS {
        int id PK
        int user_id FK
        string service_name
        decimal cost
        string billing_cycle
        date renewal_date
    }
    USERS ||--o{ SUBSCRIPTIONS : owns
