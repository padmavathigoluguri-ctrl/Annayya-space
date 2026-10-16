ANAYYA SPACE — Android app project

This project wraps the Anayya Space app in a native Android launcher app so it opens from its own app icon and runs offline.

To build an installable APK:
1. Install Android Studio on a computer.
2. Open the AnayyaSpace folder in Android Studio.
3. Allow Gradle sync and install Android SDK Platform 35 if prompted.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The debug APK will be under app/build/outputs/apk/debug/app-debug.apk.
6. Transfer that APK to the Android phone and install it. Android may ask permission to install apps from that source.

No internet permission is requested. The app content is bundled locally. This source project is not itself an APK; it must be built in Android Studio to create the installable APK.
