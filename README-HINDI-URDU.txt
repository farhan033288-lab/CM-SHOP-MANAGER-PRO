CM SHOP MANAGER PRO — Android APK build package

Important: This folder is Android source code, not yet a compiled APK.
This environment does not have the Android SDK/Gradle build toolchain installed, so it cannot honestly provide an APK built and tested here.

Free build using GitHub Actions:
1. On GitHub, create a new repository (for example: cm-shop-manager-pro). A free account is enough for this public project.
2. Upload the CONTENTS of this android-app folder to the repository root. Make sure the .github/workflows/build-apk.yml file is included; if uploading from a phone is difficult, use GitHub Desktop on a computer.
3. Open the repository's Actions tab. Allow workflows if GitHub asks.
4. Choose “Build Android APK” and tap “Run workflow”. Or push/commit the files to main/master to trigger the workflow.
5. When it finishes successfully, open that workflow run and download the artifact named “CM-SHOP-MANAGER-PRO-APK”.
6. Extract the downloaded artifact ZIP; inside is app-debug.apk. Send that APK to friends.
7. On each Android phone, open the APK and allow “Install unknown apps” for the app used to open it, if Android asks. Only install APKs from people you trust.

This is a debug APK for personal sharing/testing, not a Play Store release. It is not signed with a private release key. Each phone stores shop data locally on that phone; data does not sync between friends' devices. Keep JSON backups. Test all workflows before using it for important shop accounts.
