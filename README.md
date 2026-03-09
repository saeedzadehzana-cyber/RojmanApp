# Rojman Android App

A lightweight Android WebView app for https://rojman.org with pull-to-refresh and in-app navigation.

## Build locally

1. Open the project in Android Studio.
2. Let Gradle sync.
3. Run on a device or emulator.
4. To generate an APK:
   - **Debug APK:** `Build > Build Bundle(s) / APK(s) > Build APK(s)`
   - or terminal: `./gradlew assembleDebug`

The generated APK will be at:

`app/build/outputs/apk/debug/app-debug.apk`

## Build on GitHub

1. Upload this project to a GitHub repository.
2. Go to **Actions**.
3. Run **Build Android APK**.
4. Download the file from **Artifacts**.
