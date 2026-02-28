# 🪐 Orbit
> **Target:** `OB.010.001` &middot; **Status:** 🟢 Active Development

---
### 🗺️ **Site Map**
* 🏠 [Project Homepage](../project-homepage.md)
* 🔐 [Access Management](./access-management.md)
* 📅 [Event Scheduling Module](./event-scheduling-module.md)
  * 👉 **Schedule Event**
* 🔄 [Geolock API Synchronization](./geolock-api-synchronization.md)
* 👥 [Member Attendance Viewer](./member-attendance-viewer.md)
* 📊 [Participation Analytics](./participation-analytics.md)

---

**[Project Homepage](../project-homepage.md) > [Event Scheduling Module](./event-scheduling-module.md) > Schedule Event**

### Mockup Image (optional)
![Schedule Event Mockup](./public/images/schedule-event-mockup.png)

### Schedule Event
The system shall allow officers to create, update, and delete event details (name, date, time) and generate a unique Event ID for tracking.

### Use Case Scenario

| Use Case Details | Description |
| :--- | :--- |
| **Use Case Name** | Schedule Event |
| **Primary Actors** | Organization Officer |
| **Pre-condition** | The user must be authenticated and hold the "Officer" role for their respective organization. |
| **Main Success Flow** | 1. The Organization Officer navigates to the Event Management dashboard.<br>2. The officer selects the option to create, update, or delete an event.<br>3. The officer inputs/modifies the event details (name, date, time).<br>4. The system processes the request, generates a unique Event ID (if creating), and saves the changes to the database.<br>5. The system displays a success confirmation to the officer. |
| **Alternative Flow** | If the officer leaves required fields blank or inputs an invalid date/time (e.g., a past date), the system prevents saving and displays a validation error message. |

---
<div align="center">
  © 2026 Orbit Team
</div>