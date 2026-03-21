# Privacy Policy — RemindToDeleteApps

**Effective Date:** 2026-03-21
**Developer:** SudarshanTechLabs
**Location:** Bangkok, Bangkok, Thailand
**Contact:** sudarshantechlabs@gmail.com

---

## 1. Introduction

RemindToDeleteApps ("the App") is developed and maintained by SudarshanTechLabs. This Privacy Policy explains what information the App accesses, how it is used, and your rights as a user.

We are committed to your privacy. **The App does not collect, store, or transmit any personal data to external servers.**

---

## 2. Data We Access

### 2.1 Installed Applications List
The App requests the `QUERY_ALL_PACKAGES` permission to read the list of apps installed on your device.

- **Why:** To display your installed apps so you can set reminders for them.
- **How it is used:** Entirely on-device. The app list is never transmitted, uploaded, shared, or sold to any third party.

### 2.2 App Uninstall Capability
The App uses the `REQUEST_DELETE_PACKAGES` permission to initiate the system uninstall dialog for an app when you tap "Delete."

- **Why:** To trigger the standard Android uninstall flow on your behalf.
- **How it is used:** Only when you explicitly tap a delete/uninstall action. The App does not silently uninstall anything.

### 2.3 Notifications
The App uses the `POST_NOTIFICATIONS` permission to send reminder notifications.

- **Why:** To alert you when an app's reminder timer has expired.
- **How it is used:** Notifications are scheduled and delivered entirely on-device via Android's WorkManager and AlarmManager. No notification content is sent to external servers.

### 2.4 Boot Completion
The App uses the `RECEIVE_BOOT_COMPLETED` permission.

- **Why:** To reschedule your pending reminders after a device restart, so reminders are never lost.

### 2.5 Foreground Service
The App uses a foreground service (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_DATA_SYNC`) for background processing of app installation events.

- **Why:** To detect when new apps are installed and offer to set a reminder immediately.
- **How it is used:** Processing happens locally. No data leaves your device.

### 2.6 Internet
The `INTERNET` permission is declared in the App.

- **Current use:** Not actively used for core features. May be used in future versions for optional features such as crash reporting or feature announcements, in which case this policy will be updated.

---

## 3. Data Storage

All app data — including your reminder settings, snooze preferences, and keep-forever lists — is stored **locally on your device** using Android's Room database and DataStore.

- No data is backed up to any cloud service operated by SudarshanTechLabs.
- Standard Android system backups (if enabled by the user) may include this local data per Android's backup policies.

---

## 4. Data Sharing

We do not sell, rent, trade, or otherwise share your data with any third parties. No analytics SDKs, advertising SDKs, or tracking libraries are integrated into the App.

---

## 5. Third-Party Services

The App does not integrate any third-party analytics, advertising, or crash reporting services at this time.

---

## 6. Children's Privacy

The App does not knowingly collect any information from children under the age of 13. The App does not target children. If you believe a child has provided information through the App, please contact us and we will address it promptly.

---

## 7. Security

Since all data is stored locally on your device, its security depends on your device's security settings (screen lock, encryption, etc.). We do not have access to your device or its data.

---

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the **Effective Date** at the top of this page. Continued use of the App after changes are posted constitutes acceptance of the updated policy.

---

## 9. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact:

**SudarshanTechLabs**
Bangkok, Bangkok, Thailand
sudarshantechlabs@gmail.com

---

*This privacy policy applies to the RemindToDeleteApps Android application published on the Google Play Store.*
