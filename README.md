# VibeRun: Save Mia (test build)

Plain Android WebView app. The game lives in app/src/main/assets/index.html.

## Easiest: build the APK in the cloud (nothing to install)
1. Create a new GitHub repo and upload everything in this folder (keep the .github folder).
2. Open the repo's Actions tab, run "Build APK" (it also runs on every push).
3. When it turns green, open the run and download the VibeRun-debug-apk artifact. Unzip it to get app-debug.apk.
4. Copy the APK to your phone, tap it, and allow "install unknown apps" if asked.

## Or build locally
Open this folder in Android Studio and press Run, or run `gradle assembleDebug` with JDK 17.
The APK appears in app/build/outputs/apk/debug/.

Notes: debug-signed test build only (not for the Play Store). The audio-import button opens the Android file picker.
In this APK the bass-pulse visual is off; imported music still plays.
