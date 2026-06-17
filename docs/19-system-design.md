# 19. System Design

SubWise follows a standard **Three-Tier Architecture Model**:
1.  **Presentation Layer (Client):** Handled via standard HTML5 forms and responsive CSS3 layouts (utilizing Flexbox grids for dashboard modules).
2.  **Application Layer (Server):** Standard HTTP server capturing request parameters, managing route validation, and calculating aggregated metrics.
3.  **Data Layer (Database):** A relational schema ensuring transaction isolation and data durability for user logs.
