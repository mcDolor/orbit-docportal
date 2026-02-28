# 🪐 Orbit
> **Target:** `OB.010.001` &middot; **Status:** 🟢 Active Development

---
### 🗺️ **Site Map**
* 🏠 [Project Homepage](../project-homepage.md)
* 🔐 [Access Management](./access-management.md)
* 📅 [Event Scheduling Module](./event-scheduling-module.md)
* 🔄 [Geolock API Synchronization](./geolock-api-synchronization.md)
  * 👉 **Synchronize Attendance Data**
* 👥 [Member Attendance Viewer](./member-attendance-viewer.md)
* 📊 [Participation Analytics](./participation-analytics.md)

---

**[Project Homepage](../project-homepage.md) > [Geolock API Synchronization](./geolock-api-synchronization.md) > Synchronize Attendance Data**

### Mockup Image (optional)
![Synchronize Data Mockup](./public/images/sync-data-mockup.png)

### Synchronize Attendance Data
The system shall periodically fetch real-time attendance logs from the external Geolock database using the unique Event ID to verify student presence.

### Use Case Scenario

| Use Case Details | Description |
| :--- | :--- |
| **Use Case Name** | Synchronize Attendance Data |
| **Primary Actors** | System Admin, Geolock API |
| **Pre-condition** | The event must be created, and the Geolock API must be accessible with valid authentication keys. |
| **Main Success Flow** | 1. The System Admin initiates a manual sync or the system triggers a scheduled periodic fetch.<br>2. The system sends a request to the Geolock API using the unique Event ID.<br>3. The Geolock API responds with the real-time time-in and time-out logs.<br>4. The system processes the incoming data and updates the Orbit database.<br>5. The system logs a successful synchronization status. |
| **Alternative Flow** | If the Geolock API is unreachable or returns an error, the system aborts the synchronization, logs the error, and notifies the System Admin to check the connection. |

---
<div align="center">
  © 2026 Orbit Team
</div>