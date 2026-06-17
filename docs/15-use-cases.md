# 15. Use Cases

### Use Case UC-01: Create Subscription Entry
* **Primary Actor:** Logged-in User
* **Preconditions:** The user is securely authenticated and viewing their main dashboard.
* **Main Success Scenario:**
    1. The user clicks on the "Add New Subscription" button element.
    2. The system serves an entry form modal.
    3. The user populates the data inputs and clicks submit.
    4. The backend validates the structural layout of the payload, writes to the dataset, and triggers a dashboard UI refresh.
