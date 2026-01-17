# RemindToDeleteApps Privacy Policy

**Last Updated**: January 2025

This Privacy Policy describes how **Sudarshan Tech Labs** ("we", "our", or "us") collects, uses, and protects your information when you use the **RemindToDeleteApps** Android application ("the App", "our App", "the Service").

By using RemindToDeleteApps, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information We Collect

### 1.1 Tracked Apps Information

When you track an app for reminders, we store the following information locally on your device:

* **App Package Name**: Unique identifier for the app (e.g., `com.example.app`)
  * Used to identify which app to remind you about
  * Stored in Room database
* **App Name**: Display name of the app
  * Retrieved from Android PackageManager
  * Stored for display purposes
* **Install Timestamp**: When the app was first installed on your device
  * Retrieved from Android PackageManager
  * Used to calculate days since installation
* **Reminder Days**: Number of days before reminder triggers
  * Set by you when creating a reminder
  * Stored in Room database
* **Exclusion Status**: Whether the app is marked as "Keep Forever"
  * Set by you to exclude apps from reminders
  * Stored in Room database
* **Last Notification Timestamp**: When you were last notified about this app
  * Updated when reminder notifications are sent
  * Used to prevent notification spam

### 1.2 Reminder Data

We store reminder information locally on your device:

* **Reminder ID**: Unique identifier for each reminder
* **Package Name**: Which app the reminder is for
* **Trigger Time**: When the reminder should fire (calculated from install time + reminder days)
* **Completion Status**: Whether the reminder has been completed
* **Snooze Status**: Whether the reminder has been snoozed
* **Snooze Count**: How many times the reminder has been snoozed
* **Snooze Days**: Number of days to snooze (3 or 7 days)

### 1.3 App Preferences (Local Storage)

The following data is stored locally on your device using DataStore:

* **Default Reminder Days**: Your preferred default number of days for reminders
* **Ask on New App Install**: Whether to show notifications when new apps are installed
* **Onboarding Completed**: Whether you've completed the onboarding flow

### 1.4 What We DON'T Collect

We do **NOT** collect:

* ❌ Personal identification information (name, email, phone number)
* ❌ Location data
* ❌ Contact information
* ❌ Device identifiers for tracking
* ❌ App usage statistics or analytics
* ❌ Network activity or browsing history
* ❌ Payment information
* ❌ Biometric data
* ❌ Photos, videos, or other media files
* ❌ Call logs or SMS messages

---

## 2. How We Use Your Information

### 2.1 Primary Uses

We use your information to:

* **Track Installed Apps**: Maintain a list of apps you want to track for reminders
* **Set Reminders**: Create reminders based on your preferences
* **Send Notifications**: Notify you when reminders expire or when new apps are installed (if enabled)
* **Manage Exclusions**: Remember which apps you've marked as "Keep Forever"
* **Respect Preferences**: Remember your settings for default reminder days and new app notifications
* **Provide App Features**: Enable all app functionality including home screen, app list, expired apps, and settings

### 2.2 Data Sharing

* **With Third Parties**: 
  * We do **NOT** share your data with any third parties
  * We do **NOT** sell, rent, or monetize your data
  * We do **NOT** use your data for advertising
* **With Cloud Services**:
  * We do **NOT** store your data in the cloud
  * We do **NOT** sync your data to any servers
  * All data remains on your device
* **With Other Apps**:
  * We do **NOT** share your data with other apps
  * We only access the list of installed apps (with your permission) to show them in the app

---

## 3. Third-Party Services

### 3.1 No Third-Party Services

RemindToDeleteApps **does not use any third-party services** that collect or process your data:

* ❌ No analytics services (Google Analytics, Firebase Analytics, etc.)
* ❌ No advertising networks
* ❌ No cloud storage services
* ❌ No crash reporting services (Firebase Crashlytics, etc.)
* ❌ No user tracking services
* ❌ No social media integrations
* ❌ No payment processors (app is free)

**Your data stays 100% on your device.**

---

## 4. Permissions Explained

### 4.1 Required Permissions

| Permission | Purpose | Why Needed |
|------------|---------|------------|
| **QUERY_ALL_PACKAGES** | Access list of installed apps | Required to show installed apps in the app list and set reminders. This permission is necessary because Android 11+ restricts package visibility. Without this permission, the app cannot show your installed apps. |
| **POST_NOTIFICATIONS** | Send reminder notifications | Required to notify you when reminders expire and when new apps are installed (if enabled). This permission is required for Android 13+ devices. |

### 4.2 Privacy Controls

You have full control over your data:

* ✅ **Notification Control**: Enable/disable notifications anytime in Settings
* ✅ **New App Notifications**: Toggle "Ask on new app install" in Settings
* ✅ **Data Deletion**: Remove tracked apps or clear all data anytime
* ✅ **Exclude Apps**: Mark apps as "Keep Forever" to exclude from reminders
* ✅ **Uninstall**: Uninstalling removes all local data permanently

---

## 5. Data Storage & Retention

### 5.1 Where Data is Stored

* **Room Database**: Tracked apps and reminders
  * Stored in app's private data directory
  * Encrypted using Android's built-in encryption
  * Not accessible by other apps
* **DataStore**: App preferences
  * Stored in app's private data directory
  * Encrypted using Android's built-in encryption
* **Local Device Only**: All data remains on your device
  * Not synced to cloud
  * Not backed up to external services

### 5.2 Data Retention

* **Tracked Apps**: Retained until you remove them or uninstall the app
* **Reminders**: Retained until completed, deleted, or app uninstall
* **Preferences**: Retained until you change them or uninstall the app
* **Uninstall**: All data is permanently deleted when you uninstall the app

### 5.3 Data Deletion

When you delete data or uninstall the app:

1. All tracked apps are removed from the database
2. All reminders are removed from the database
3. All preferences are cleared
4. All local files are deleted
5. Data cannot be recovered after deletion

**Note**: Deletion is permanent and cannot be undone.

---

## 6. Security Measures

### 6.1 Data Protection

We implement industry-standard security measures:

* ✅ **Encryption**: All data is encrypted using Android's built-in encryption
* ✅ **Private Storage**: Data stored in app's private directory (not accessible by other apps)
* ✅ **No Network Transmission**: App data is never sent over the network
* ✅ **Regular Updates**: Security patches and updates applied regularly
* ✅ **Minimal Permissions**: Only requests permissions necessary for functionality

### 6.2 Security Practices

* All database operations use Room with encryption
* DataStore uses encrypted storage for preferences
* No sensitive data is logged or exposed
* App follows Android security best practices

---

## 7. Your Rights

### 7.1 Data Control

You have the right to:

* **View Your Data**: Access all tracked apps and reminders in the app
* **Edit Your Data**: Modify reminder days, exclude apps, or remove tracking
* **Delete Your Data**: Delete individual apps or clear all data (Settings)
* **Uninstall**: Uninstalling removes all local data
* **Export**: Request your data export (contact us at sudarshantechlabs@gmail.com)

### 7.2 GDPR Rights (EU Users)

If you're in the European Union, you have additional rights under GDPR:

* ✅ **Right to Access**: View all your personal data
* ✅ **Right to Rectification**: Edit inaccurate data
* ✅ **Right to Erasure**: Delete your data at any time ("Right to be Forgotten")
* ✅ **Right to Data Portability**: Request your data export in a portable format
* ✅ **Right to Object**: Control how your data is used
* ✅ **Right to Restrict Processing**: Limit how we process your data

**How to Exercise Your Rights**: 
* Use the app's built-in features in Settings
* Contact us directly at sudarshantechlabs@gmail.com
* We will respond within 48 hours

### 7.3 CCPA Rights (California Users)

If you're in California, you have additional rights under CCPA:

* ✅ **Right to Know**: Know what personal information we collect
* ✅ **Right to Delete**: Request deletion of your personal information
* ✅ **Right to Opt-Out**: Opt-out of sale of personal information (we don't sell data)
* ✅ **Right to Non-Discrimination**: We won't discriminate for exercising your rights

---

## 8. Children's Privacy

RemindToDeleteApps is intended for users who are 13 years of age or older. We do not knowingly collect personal information from children under 13.

If you are a parent or guardian and believe your child has provided us with personal information, please contact us immediately. We will delete such information from our servers.

---

## 9. International Data Transfers

Since all data is stored locally on your device and never transmitted to any servers, there are no international data transfers. Your data remains on your device in your country of residence.

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:

* Updating the "Last Updated" date at the top of this policy
* Posting the new Privacy Policy in the app (if applicable)
* Sending you an in-app notification (for significant changes)

Your continued use of the App after any changes constitutes your acceptance of the new Privacy Policy.

---

## 11. Contact Us

If you have any questions about this Privacy Policy or our data practices, please contact us:

* **Email**: sudarshantechlabs@gmail.com
* **Developer Email**: sunny.sudarshan@gmail.com
* **Website**: https://sudarshantechlabs.com
* **GitHub**: [RemindToDeleteApps Repository](https://github.com/SUDARSHANCHAUDHARI/RemindToDeleteApps)

**Response Time**: We aim to respond to privacy-related inquiries within **48 hours**.

---

## 12. About Sudarshan Tech Labs

**RemindToDeleteApps** is developed and published by **Sudarshan Tech Labs**.

* **Company**: Sudarshan Tech Labs
* **Website**: https://sudarshantechlabs.com
* **Email**: sudarshantechlabs@gmail.com
* **Developer**: Sudarshan Kishor Chaudhari
* **Developer Email**: sunny.sudarshan@gmail.com
* **GitHub**: [@SUDARSHANCHAUDHARI](https://github.com/SUDARSHANCHAUDHARI)

---

## 13. Legal Basis for Processing (GDPR)

For users in the European Union, we process your personal data based on:

* **Consent**: You consent to data processing by using the App
* **Contractual Necessity**: Processing is necessary to provide the App's services
* **Legitimate Interests**: To improve the App and ensure security

You can withdraw your consent at any time by uninstalling the app.

---

## 14. Data Breach Notification

Since all data is stored locally on your device and never transmitted to any servers, the risk of a data breach is minimal. In the unlikely event that your device is compromised, we recommend:

* Uninstalling the app to remove all local data
* Contacting us if you have concerns
* Following your device manufacturer's security recommendations

---

## 15. Complaints

If you have a complaint about how we handle your personal information, you can:

* Contact us directly at sudarshantechlabs@gmail.com
* File a complaint with your local data protection authority (for EU users)
* File a complaint with the California Attorney General (for California users)

---

**Last Updated**: January 2025

**Version**: 0.0.2

---

**Made with ❤️ by Sudarshan Tech Labs**

_Privacy is not a feature - it's a fundamental right._
