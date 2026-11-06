# Dino Blocks Arcade

Two games in one app: Block Blast (with custom block colors) and Dino Hop (a Crossy Road style road crosser).
The whole game is `app/src/main/assets/index.html`. It also runs in any browser by opening that file.

## Get the .apk

Option A, Android Studio (easiest):
1. Open this folder in Android Studio and let it sync.
2. Build > Build Bundle(s) / APK(s) > Build APK(s).
3. The file is at app/build/outputs/apk/debug/app-debug.apk. Copy it to your phone and open it.
   You may need to allow "Install unknown apps" for your file manager.

Option B, no install: push this folder to a GitHub repo. The "Build APK" workflow runs on every push.
Download `dino-blocks-arcade-apk` from the Actions tab, unzip, and install app-debug.apk.

Option C, command line with the Android SDK installed: `gradle assembleDebug`
