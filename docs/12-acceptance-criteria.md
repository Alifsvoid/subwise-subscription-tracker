# 12. Acceptance Criteria

### AC-01: Subscription Logging Form Validation
* **Scenario:** User attempts to submit a subscription missing critical fields.
* **Given:** The subscription creation modal interface is open.
* **When:** The user leaves the "Cost" or "Service Name" inputs empty and hits the save button.
* **Then:** The system must block the form submission and display an explicit error warning to the user.
