# RemindToDeleteApps — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

RemindToDeleteApps helps you manage installed apps on your Android device by scheduling reminders to review and remove apps you no longer use. All data is stored locally. Sudarshan Tech Labs does not collect or transmit personal data.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| App reminder configurations (app name, reminder date, notes) | Core reminder functionality | Room database on your device |
| List of installed apps (read at runtime) | Display apps for reminder setup | Not stored — read dynamically |
| App preferences | Personalisation | DataStore on your device |

### Installed App Information

RemindToDeleteApps reads the list of apps installed on your device to allow you to set reminders. This list is processed in-app only and is not stored permanently or transmitted externally.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Display installed apps for reminder setup | Installed app list (runtime only) |
| Schedule and deliver reminder notifications | Local reminder configurations |
| Run background checks for due reminders | Local WorkManager tasks |

---

## Data Storage and Security

- **Reminder data:** Stored in a Room database in the App's private directory
- **No cloud storage:** Sudarshan Tech Labs operates no backend server
- **Biometric lock:** Optional biometric authentication to access the App (Android Biometric API — biometric data managed by Android OS)
- **Android sandbox:** All data is protected by Android's application isolation

## Data Retention

| Data | Retention |
|---|---|
| All local reminder data | Until you delete it or uninstall the App |

---

## Data Sharing

We do not collect, sell, or share your data. Installed app information is never transmitted externally.

---

## Background Services

RemindToDeleteApps uses a foreground service (`FOREGROUND_SERVICE_DATA_SYNC`) to check for due reminders in the background. A persistent notification is visible while the service runs.

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `POST_NOTIFICATIONS` | Deliver app deletion reminder notifications |
| `RECEIVE_BOOT_COMPLETED` | Reschedule reminders after device restart |
| `QUERY_ALL_PACKAGES` | Read the list of installed apps to set reminders for them |
| `REQUEST_DELETE_PACKAGES` | Show the system uninstall dialog for an app when you tap Delete |
| `INTERNET` | Network library initialisation (no personal data sent) |
| `FOREGROUND_SERVICE` | Run the reminder check service in the background |
| `FOREGROUND_SERVICE_DATA_SYNC` | Required foreground service type for background data tasks |

---

## Your Rights and Controls

- **Delete individual reminders:** Use the delete function in the App
- **Delete all data:** Uninstall or go to Android Settings > Apps > RemindToDeleteApps > Storage > Clear Data

---

## Children's Privacy

RemindToDeleteApps is not directed at children under 13. We do not collect personal information.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of RemindToDeleteApps after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions, data access requests, or account deletion:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Reminder configurations | Local only | No | App functionality |
| Installed app list | Runtime only, not stored | No | Reminder setup |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21
