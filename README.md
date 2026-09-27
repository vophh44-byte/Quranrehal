# QuranRehal — Web + Android starter

This package starts from the current QuranRehal/Usmania dashboard source and prepares it for:
- Web deployment
- PWA installation on phones
- Android packaging with Capacitor

## Web
Serve the `www` folder with any static host, or locally:
```bash
npm run web
```

## Android
Install Node.js and Android Studio, then from this folder:
```bash
npm install
npx cap add android
npm run sync
npx cap open android
```

Build an APK/AAB from Android Studio.

## Important
The current dashboard is still the existing application. Authentication, cloud database,
teacher/student/parent accounts, Quran course data, and production security should be added
before calling this the finished public platform.
