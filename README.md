# Android Message Scheduler V1.0 (source project)

Open the folder in Android Studio (JDK 17, Android SDK 35), sync Gradle and use Build > Build APK(s). No compiled APK is included.

Features: one-time SMS scheduling, WhatsApp ready-to-send notification, local history, cancellation, reboot rescheduling, permission request.

Important limitations:
- Standard personal WhatsApp does not provide an official API for unattended automatic sending. This app NEVER sends WhatsApp messages without the user's Send action.
- SMS submission is not proof of delivery. No delivery receipts are implemented in V1.0.
- SMS permission may be restricted by Google Play policy. Intended for local testing/sideloading, not a Play Store publication claim.
- Exact alarms require user approval on modern Android. Power saving, SIM/network status, reboot and device manufacturer settings can affect timing.
- Notifications require permission on Android 13+. WhatsApp links require internet and installed WhatsApp for the intended workflow.
- This is an untested initial source build. It needs device testing before production use.
- Do not use for unsolicited bulk messaging.
