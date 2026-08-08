# GivAwayTrail AI for Android

This project wraps the hosted GivAwayTrail AI app in a native Android WebView.

## Included Android features

- JavaScript and browser storage support
- Profile-picture and image file selection
- Android back-button navigation
- External giveaway links open in the device browser
- HTTPS-only network policy
- Dark status and navigation bars matching the app

## Build

1. Install Android Studio or the Android SDK with Android API 36.
2. Copy `local.properties.example` to `local.properties` and update `sdk.dir`.
3. Run `gradlew.bat assembleRelease` on Windows or `./gradlew assembleRelease` on macOS/Linux.
4. Find the APK under `app/build/outputs/apk/release/`.

The app loads `https://lootloom-ai-radar.thejacksons37.chatgpt.site/`, so an internet connection is required. The website's existing access rules still apply.

The included release APK is signed for direct sideloading and testing. Publishing to Google Play requires replacing that test signature with your own permanent release key.
