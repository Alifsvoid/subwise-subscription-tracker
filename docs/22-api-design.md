# 22. API Endpoints

| HTTP Method | Route Endpoint | Description | Payload Example |
| :--- | :--- | :--- | :--- |
| **POST** | `/api/auth/signup` | Registers new user | `{"username": "user1", "password": "xyz"}` |
| **GET** | `/api/subscriptions` | Fetches active list | *None* |
| **POST** | `/api/subscriptions` | Adds new tracking item | `{"name": "Spotify", "cost": 10.99}` |
| **DELETE** | `/api/subscriptions/:id` | Drops log item from DB | *None* |
