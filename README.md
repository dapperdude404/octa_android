# Octo for Android

Wraps the Octo web app (`app/src/main/assets/index.html`) in a WebView.

- Android 8.0 and up (minSdk 26)
- Pure Java, no native code: runs on arm64-v8a (ARMv8), armeabi-v7a (32-bit ARM) and x86 phones
- Needs internet for helper libraries (PDF, Word, Excel) and fonts

## Build with GitHub (no Android Studio)
1. Upload everything in this folder to a new repository, e.g. `octo-android` (keep the `.github` folder).
2. Open the **Actions** tab, choose **Build APK**, and click **Run workflow**.
3. When it finishes, open the run and download the **octo-apk** file. Unzip it to get the `.apk`.

## Build with Android Studio
Open this folder, wait for sync, then **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## Install
Copy the APK to your phone, open it, and allow "Install unknown apps" when asked.
