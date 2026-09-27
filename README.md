# Floating Apps v2

A polished Android floating-app launcher. It lists launchable installed apps with icons, search, app cards, overlay permission status, and a draggable floating bubble.

## Android limitation
A regular third-party app cannot force arbitrary other apps into a true resizable floating window. This project uses an Android overlay bubble that stays above other apps and reopens the selected app. Apps that support Android Picture-in-Picture can use their own PiP behavior.

## Build
Open in Android Studio and build the debug APK, or push to GitHub and use the included Actions workflow.
