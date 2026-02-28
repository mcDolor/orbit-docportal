# 🪐 Orbit
> **Target:** `OB.010.001` &middot; **Status:** 🟢 Active Development

---
### 🗺️ **Site Map**
* 🏠 [Project Homepage](../project-homepage.md)
* 🔐 [Access Management](./access-management.md)
* 📅 [Event Scheduling Module](./event-scheduling-module.md)
* 🔄 [Geolock API Synchronization](./geolock-api-synchronization.md)
* 👥 [Member Attendance Viewer](./member-attendance-viewer.md)
* 📊 [Participation Analytics](./participation-analytics.md)
  * 👉 **Analyze Participation**
---

**[Project Homepage](../project-homepage.md) > [Participation Analytics](./participation-analytics.md) > Analyze Participation**

### Mockup Image (optional)
![Participation Analytics Mockup](./public/images/analytics-mockup.png)

### Analyze Participation
The system shall aggregate attendance data to display a statistical dashboard for officers, visualizing participation trends and attendance rates per event.

### Use Case Scenario

| Use Case Details | Description |
| :--- | :--- |
| **Use Case Name** | Analyze Participation |
| **Primary Actors** | Organization Officer, System Admin |
| **Pre-condition** | Event data must exist and attendance logs must be successfully synchronized from the Geolock API. |
| **Main Success Flow** | 1. The Organization Officer or System Admin navigates to the Analytics Dashboard.<br>2. The system retrieves aggregated attendance data from the database.<br>3. The system calculates participation trends, total registered members, and attendance rates per event.<br>4. The system renders visual charts (e.g., bar graphs, pie charts) for the user to analyze. |
| **Alternative Flow** | If there is insufficient data to generate a trend (e.g., a newly created organization with zero past events), the system displays empty chart placeholders with a "Data unavailable" prompt. |

---
<div align="center">
  © 2026 Orbit Team
</div>