# 🪐 Orbit
> **Target:** `OB.010.001` &middot; **Status:** 🟢 Active Development

---
### 🗺️ **Site Map**
* 🏠 [Project Homepage](../project-homepage.md)
* 🔐 [Access Management](./access-management.md)
* 📅 [Event Scheduling Module](./event-scheduling-module.md)
* 🔄 [Geolock API Synchronization](./geolock-api-synchronization.md)
* 👥 [Member Attendance Viewer](./member-attendance-viewer.md)
  * 👉 **View Attendance Log**
* 📊 [Participation Analytics](./participation-analytics.md)

---

**[Project Homepage](../project-homepage.md) > [Member Attendance Viewer](./member-attendance-viewer.md) > View Attendance Log**

### Mockup Image (optional)
![View Attendance Mockup](./public/images/view-attendance-mockup.png)

### View Attendance Log
The system shall retrieve and display individual time-in and time-out logs for specific events, allowing members to verify their own attendance status.

### Use Case Scenario

| Use Case Details | Description |
| :--- | :--- |
| **Use Case Name** | View Attendance Log |
| **Primary Actors** | Student Member |
| **Pre-condition** | The user must be authenticated as a "Student Member" and be registered in the respective organization. |
| **Main Success Flow** | 1. The Student Member navigates to their personal attendance history page.<br>2. The system queries the database for the member's specific time-in and time-out logs across events.<br>3. The system formats and displays the logs in a readable list or table.<br>4. The member successfully views their personal attendance status. |
| **Alternative Flow** | If the member has not attended any events or the logs have not yet synchronized, the system displays a "No attendance records found for this event" message. |

---
<div align="center">
  © 2026 Orbit Team
</div>