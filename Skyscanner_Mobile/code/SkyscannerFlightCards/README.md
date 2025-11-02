# SkyscannerFlightCards

Minimal Android app scaffold demonstrating Backpack cards UI.

How to open
- Open this folder in Android Studio (Narwhal 2025.1.1 or later recommended).
- Sync Gradle. If Android Gradle Plugin or Kotlin plugin versions need updating to match your Studio installation, adjust the versions in the project-level `build.gradle`.

Notes
- Backpack dependency is declared in `app/build.gradle` as `net.skyscanner.backpack:backpack-android:71.0.0` as requested; verify on Maven Central if you want to bump to a newer patch.
- This project uses minSdk 33 (Android 13) per instructions.
- Release builds enable `minifyEnabled true` in `app/build.gradle`.

Verify UI
- Run an emulator with API 33+ and launch the app. The main screen contains three Backpack cards for flight, departure and arrival.
