AYESHA & SIMO — LOVE QUEST (CAPACITOR ANDROID STARTER)

This is a prepared Capacitor wrapper project for the existing web game.
It is source code, not a compiled APK.

REQUIREMENTS (on a computer):
- Node.js (use a current LTS release)
- Android Studio and Android SDK
- Internet for npm dependencies / Gradle setup

BUILD STEPS:
1. Extract this ZIP on your computer.
2. Open a terminal/Command Prompt in this extracted folder.
3. Run:
   npm install
   npm install @capacitor/android@^8
   npx cap add android
   npx cap sync android
   npx cap open android
4. In Android Studio, wait for Gradle sync to finish.
5. To make a test APK: Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Android Studio shows the output path, usually android/app/build/outputs/apk/debug/app-debug.apk.

SIGNED RELEASE APK:
Build > Generate Signed Bundle / APK > APK > Next.
Create a new keystore, keep it private and backed up securely, choose release, then Finish.
Never share keystore passwords or upload key files in chats.

SAVE DATA:
Game progress is saved locally on the device/browser storage. It is not cloud-synced.
Clearing app data or uninstalling may remove saved progress.

LIMITATIONS:
- This starter uses CSS/emoji character animation placeholders, not custom frame-by-frame character art.
- Coins/hearts are game points, not money.
- Test the app on a device before sharing. Play Store publishing is a separate process.
