# Build APK on GitHub (mobile browser)
1. Upload all project files with their folder paths preserved. Do not upload the ZIP as a single file.
2. Open Actions > Build Android APK > Run workflow.
3. Open the successful run > Artifacts > MessageScheduler-debug-APK.
4. Download artifact ZIP, extract app-debug.apk, install on Android after reviewing permissions.

This is an untested debug build. WhatsApp only opens a prepared message after a notification tap; it does not automatically press Send. SMS uses SEND_SMS permission and may incur carrier fees. Test only with your own number first. Exact alarms may need special access. Private repo recommended.
