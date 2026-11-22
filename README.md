# GeoLens Pro — Native Android APK Source Package

This archive contains the complete native Android Studio project (`com.geolens.pro`) that compiles directly into an installable `.apk` file with full Camera, Microphone, GPS, and Android MediaStore Gallery permissions.

## Option 1: Build APK Locally in Android Studio (2 Minutes)
1. Extract this ZIP archive.
2. Open **Android Studio** -> **Open** -> select the `geolens_android_project` folder.
3. Let Gradle sync automatically.
4. Click **Build -> Build Bundle(s) / APK(s) -> Build APK(s)**.
5. Your installable APK will be generated at:
   `app/build/outputs/apk/debug/app-debug.apk`

## Option 2: Build APK in the Cloud Without Installing Android Studio
1. Create a free repository on GitHub and upload the contents of `geolens_android_project`.
2. Open the **Actions** tab -> click **Build Android APK** -> **Run workflow**.
3. Download `GeoLensPro-debug-apk` and install it on your Android phone.
