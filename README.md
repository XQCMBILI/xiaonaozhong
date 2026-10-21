# xiaonaozhong
Small Alarm Clock
 
A native Android alarm clock application, written in pure Java, no third‑party SDK dependencies.
 
Features
 
- Core Alarm Functions
​
- Custom alarm hour, minute, second precision trigger time
​
- Repeat rules: single‑time, workdays, weekends, every selected weekday
​
- Gradually increasing ringtone volume, customizable ramp‑up duration
​
- Vibration control, customizable snooze interval
​
- Dawn wake‑up: screen brightness fades in softly for gentle morning wake‑up
​
- Math Quiz Wake‑up Verification
Three difficulty levels (Simple / Medium / Hard). Users must solve arithmetic or logic problems to turn off the alarm; cannot dismiss alarm without passing the quiz. Prevent oversleeping by forcing your brain to wake up.
​
- Bedtime Reminder
Custom bedtime notification. Pop‑up reminder window with nightly gentle quotes to remind you to rest on time.
​
- Future Reminders (Long‑term alerts)
Schedule reminders for birthdays, medical appointments, future events months away.
Requires typing the exact text  I acknowledge this  to dismiss. If ignored, it will repeatedly alert you. Supports postponing for 5 minutes or until tomorrow.
​
- Statistics & Achievement Badge System
​
- Track early‑rising days, quiz‑solved count, consecutive‑day streaks
​
- Bronze / Silver / Gold tier achievement medals
​
- Record bedtime‑reminder completion status
​
- All data stores locally on device, no network connection required, no data uploads.
​
- UI & Theme
​
- Material‑style dynamic UI, fluid gradient background optional
​
- Multiple accent color options, dark / light mode support
​
- Smooth custom time‑picker wheel with mechanical tick haptic feedback
 
Compile & Build
 
1. Import this project with Android Studio
​
2. Compile with Gradle
​
3. Min SDK: 19, Target SDK:26
​
4. Generate release APK for installation.
 
Required Permissions
 
- Wake lock, vibrate
​
- Receive boot‑completed broadcast (restore alarms after device reboot)
​
- System overlay / draw over other apps (lock‑screen pop‑up alarm page)
​
- Full‑screen intent permission for Android 14+
 
Notice
 
This app works best when you disable battery‑optimization restrictions for it on your Android device, to avoid the system killing background alarm services.
