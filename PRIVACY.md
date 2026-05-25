# Privacy Policy — Clock Rings

**Developer:** Eric Rogers Technology
**Last updated:** May 24, 2026

Clock Rings is built with privacy as a default. This policy explains what the app accesses on your device, how it uses that information, and — importantly — what it does *not* do.

## Short version

- I do not collect, store, or transmit your personal data. I have no servers.
- Your shift history, alarms, and settings live on your device and sync through *your own* Apple iCloud account, which only you can access.
- No analytics, no ads, no third-party tracking SDKs.
- Location is used only to fetch local weather and is never stored or sent to me.

## What the app accesses on your device

**Punch history** (clock in/out, lunch, breaks). Stored locally via Apple's SwiftData. If you keep iCloud sync enabled, it mirrors to your private CloudKit database so your other Apple devices see it. The developer cannot access this data.

**App settings, alarms, and active shift state.** Stored in your device's preferences and synced via Apple's iCloud Key-Value Storage. Visible only to your Apple ID's devices.

**Location (When In Use).** Used to retrieve current weather conditions from Apple's Weather service for the main clock screen. Location is not stored, logged, or transmitted to the developer.

**Face ID / Touch ID.** Used only if you enable App Lock. Biometric data never leaves your device's Secure Enclave.

**Notifications and alarms.** Scheduled locally on your device through Apple's notification and AlarmKit systems. Nothing sent through an external server.

**Siri shortcuts.** Voice commands are processed by Apple's Siri. The app only receives the recognized intent (e.g., "start shift", "lunch out"), never your voice recording.

## What this app does NOT do

- No personal information is collected or shared.
- No servers operated by the developer hold your data.
- No third-party analytics, advertising, or tracking SDKs.
- No data is sold, rented, or transferred to any third party.
- No access to contacts, photos, microphone, or camera.

## Children's privacy

The app does not knowingly collect data from anyone, including children under 13.

## Changes to this policy

If this policy materially changes, the updated version will be posted at this URL with a new "Last updated" date.

## Contact

Questions? Email: **EricRogersTechnology@iCloud.com**
