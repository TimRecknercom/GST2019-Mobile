# Google Santa Tracker (2023 Mobile Archive)

<img width="1535" height="958" alt="Screenshot 2026-11-08 222426" src="https://github.com/user-attachments/assets/422abcf3-42d8-495b-9688-1e32a945f366" />
<img width="1532" height="887" alt="Screenshot 2026-11-08 230318" src="https://github.com/user-attachments/assets/207d050f-8b2f-4a99-93f4-bf5c407b0c1a" />


An archival and preservation project for the final official Android release of Google Santa Tracker (December 2023). 

Following the delisting and discontinuation of the native Santa Tracker app on the Google Play Store, this repository preserves the standalone Android build along with setup instructions for modern devices and desktop emulators.

---

## 📌 About This Project

In late 2023, Google sunsetted active development for the native Android build of Santa Tracker, shifting focus strictly to web-based experiences. As a result, the native client was removed from the Play Store, putting the original games, physics engines, and offline assets at risk of becoming lost media.

This repository exists to document, archive, and provide instructions on how to run the preserved 2023 Android APK locally.

### Key Features of the 2023 Build
* **Native Offline Mini-Games:** Includes client-rendered favorites like *Present Drop*, *Rocket Sleigh*, and *Wrap Battle*.
* **Dedicated Engine Assets:** Localized sound banks, sprite sheets, and animations built specifically for Android runtimes.
* **Preserved Village Map:** The final structural layout released prior to full web-only migration.

---

## 🚀 How to Run the App

Because this is a native Android application (`.apk`), it requires either a physical Android device or a desktop Android emulator.

### Option 1: On a PC / Mac (Recommended)
You can run the APK on any modern computer using an Android emulator:
1. Download and install an emulator such as [BlueStacks 5](https://www.bluestacks.com/) or [MuMuPlayer](https://www.mumuplayer.com/).
2. Download the `GST2023.apk` file from the **Releases** section of this repository.
3. Drag and drop the `.apk` file into your emulator window to install it.
4. Launch the game from the emulator home screen.

### Option 2: On a Physical Android Device
1. Download the APK file directly to your phone or tablet.
2. Open the file and allow installation from unknown sources if prompted by your system settings.
3. Tap **Install** and open the app.

---

## ⚠️ Known Limitations
* **Live Telemetry & Christmas Eve Route:** Google’s live backend tracking APIs for the Christmas Eve flight stream are inactive. Real-time location endpoints will not connect.
* **Cloud Sync / Play Games:** Google Play Games leaderboards and cloud saves are no longer authenticated.
* **Offline Functionality:** All local mini-games, sound effects, and village interactions run independently of Google servers.

---

## 📜 Disclaimer
This repository is an independent digital preservation effort intended strictly for historical and archival purposes. All rights, characters, and trademarks belong to Google LLC.
