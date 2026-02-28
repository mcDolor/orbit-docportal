# 🪐 Orbit
> **Target:** `OB.010.001` &middot; **Status:** 🟢 Active Development

---
### 🗺️ **Site Map**
* 🏠 [Project Homepage](../project-homepage.md)
* 🔐 [Access Management](./access-management.md)
  * 👉 **Manage Access**
* 📅 [Event Scheduling Module](./event-scheduling-module.md)
* 🔄 [Geolock API Synchronization](./geolock-api-synchronization.md)
* 👥 [Member Attendance Viewer](./member-attendance-viewer.md)
* 📊 [Participation Analytics](./participation-analytics.md)

---

**[Project Homepage](../project-homepage.md) > [Access Management](./access-management.md) > Manage Access**

### Mockup Image (optional)
![Manage Access Mockup](./public/images/manage-access-mockup.png)

### Manage Access
The system shall validate user credentials (email/password) via Supabase Auth and enforce role-based access control (Officers vs. Members).

### Use Case Scenario

| Use Case Details | Description |
| :--- | :--- |
| **Use Case Name** | Manage Access |
| **Primary Actors** | Organization Officer, Student Member, System Admin |
| **Pre-condition** | The user must have a registered account in the system database. |
| **Main Success Flow** | 1. The user navigates to the login interface.<br>2. The user inputs their credentials.<br>3. The system validates the credentials.<br>4. The system grants access and redirects the user based on their specific role (Officer, Member, or Admin). |
| **Alternative Flow** | If credentials are invalid, the system denies access and prompts the user to try again. |

---
<div align="center">
  © 2026 Orbit Team
</div>