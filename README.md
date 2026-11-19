# Sky Task – APK build / APK உருவாக்க

1. Create a new GitHub repository and upload everything in this folder (keep the `.github` folder).
   புதிய GitHub repository உருவாக்கி இந்த folder-இல் உள்ள அனைத்தையும் (`.github` உட்பட) upload செய்யவும்.
2. Open the **Actions** tab -> **Build Sky Task APK** -> **Run workflow**.
3. After ~5 minutes, download **SkyTask-APK** from the run page, unzip, and install `app-debug.apk` on your phone (allow "install unknown apps").
   சுமார் 5 நிமிடத்தில் **SkyTask-APK** பதிவிறக்கி, `app-debug.apk`-ஐ phone-இல் install செய்யவும்.

Local build instead: `npm install && npx cap add android && npx cap sync && cd android && ./gradlew assembleDebug` (needs Node 20, JDK 17, Android SDK).
