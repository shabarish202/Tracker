# Shabarish Muscle Tracker — Final PWA v3

Includes the existing calorie, macro, food, workout, progress, local persistence and backup features plus:

- 💧 Daily water goal and progress bar
- 💧 Quick water buttons: 250 / 500 / 750 / 1000 ml
- 💧 Custom water amount
- 💧 Water log with timestamps
- 💧 Water history
- 🔔 Food and water reminder menu
- 🔔 Enable browser notifications
- 🔔 Reminder on/off switches and delete controls
- 🔔 Suggested water and meal schedules
- 📦 LocalStorage persistence and JSON backup/restore
- 📱 PWA manifest + service worker/offline cache

## Notification note
Browser/PWA notification behavior is controlled by the device and browser. The app checks scheduled reminders while the PWA is running. On iPhone, background/scheduled notifications from a plain web page are not guaranteed; install the PWA and allow notifications for the best supported behavior.

## Files
- index.html
- sw.js
- manifest.json
- icon.svg
