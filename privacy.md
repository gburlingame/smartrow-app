---
layout: default
title: Privacy Policy
---

# Privacy Policy

**Last updated: February 28, 2026**

SmartRow Companion ("the app") is developed by Greg Burlingame. This privacy policy describes how the app handles your data.

## Data Collection

SmartRow Companion does **not** collect, transmit, or sell any personal data to third parties. The app does not contain analytics, advertising, or tracking of any kind.

## Data Stored on Your Device

The app stores the following data locally on your device:

* **Workout sessions** — Rowing metrics from each session (distance, pace, power, stroke rate, heart rate, force curves, calories, and timestamps) are saved to your device using Apple's SwiftData framework.
* **App settings** — Your preferences (export options, display settings, feedback toggles) are stored locally using UserDefaults.
* **Bluetooth device information** — The identifier of your paired SmartRow device and heart rate monitor is stored locally so the app can reconnect automatically.
* **Strava authentication token** — If you connect your Strava account, an OAuth token is stored securely in the iOS Keychain on your device. This token is used solely to upload workout data to your Strava account.

## iCloud Sync

If you are signed into iCloud on your device, workout sessions are automatically synced across your devices using Apple's CloudKit. This data is stored in your private iCloud account and is not accessible to the developer or any third party. You can manage or delete this data through your iCloud settings. If you are not signed into iCloud, all data remains local to your device.

## Apple Health

If you enable Apple Health export, the app writes workout data (duration, distance, calories, and heart rate samples) to Apple Health using HealthKit. If you enable heart rate zones with the "From Age" setting, the app reads your date of birth from Apple Health to calculate your age-based maximum heart rate. Your date of birth is used only for this calculation and is never stored, transmitted, or shared. Sharing of Health data is controlled entirely by you through the Health app's permissions.

## Strava

If you enable Strava export, the app uploads workout data (power, distance, heart rate, pace, and timestamps) to your Strava account as a FIT file. This upload uses Strava's API and requires you to authorize the app via Strava's OAuth flow. You can revoke this access at any time through your Strava account settings. The app does not read any data from your Strava account.

## Heart Rate Data

If you pair a Bluetooth heart rate monitor, heart rate data is received via Bluetooth LE during your workout session. This data is displayed in real time, saved with your workout session, and included in exports to Apple Health and Strava if those features are enabled. Heart rate data is never transmitted elsewhere.

## Bluetooth

The app communicates with your SmartRow sensor and optional heart rate monitor via Bluetooth Low Energy (BLE). All Bluetooth communication occurs directly between your device and the sensors. No Bluetooth data is transmitted to any server or third party.

## Data Retention

All workout data is stored on your device (and in your private iCloud account if iCloud is enabled). You can delete individual sessions from within the app. Uninstalling the app removes all locally stored data.

## Children's Privacy

The app does not knowingly collect any data from children under 13.

## Changes to This Policy

If this privacy policy is updated, the revised version will be posted on this page with an updated date.

## Contact

If you have questions about this privacy policy, please [open an issue](https://github.com/gburlingame/smartrow-app/issues) on GitHub.
