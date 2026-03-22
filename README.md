# 🎬 BDIX TV - v1.1.4
Official Android/ Google TV/ PC app releases for BDIX Live TV

## What's New in This Update
✨ **Improved Stability & Performance** – No more crashes due to script downloading issues  
✨ **Smart Script Management** – Automatic versioning prevents conflicts after updates  
✨ **Enhanced Sports Tab** – More reliable loading and better error handling  
✨ **Optimized GitHub Sync** – Reduced API calls and improved token handling  

## 📥 Download & Install

### Windows PC (No changes – still v1.1.2)
[![Download Windows](https://img.shields.io/badge/Download-Windows-blue)](https://github.com/mpshimul/BDIX-Live-TV-APP/releases/download/v1.1.2/BDIX_TV_Setup_v1.1.2.exe)  
**[BDIX_TV_Setup_v1.1.2.exe](https://github.com/mpshimul/BDIX-Live-TV-APP/releases/download/v1.1.2/BDIX_TV_Setup_v1.1.2.exe)** (~60 MB)

**Installation Instructions:**
1. Download the installer above
2. Double-click to run the installer
3. Follow the on-screen instructions
4. Launch BDIX TV from your desktop or Start menu

> **⚠️ Troubleshooting**: If you see an error message saying `api-ms-win-core-path-l1-1-0.dll is missing`, your computer needs the **Microsoft Visual C++ Redistributable**. Download and install it from the official links below, then restart BDIX TV.
> - [Download Visual C++ Redistributable for 64-bit Windows](https://aka.ms/vs/17/release/vc_redist.x64.exe)
> - [Download Visual C++ Redistributable for 32-bit Windows](https://aka.ms/vs/17/release/vc_redist.x86.exe)

---

## 📱 Mobile Apps (Updated to v1.1.4)

### Android Universal (Recommended for most devices)
[![Download Android](https://img.shields.io/badge/Download-Android-green)](https://github.com/mpshimul/BDIX-Live-TV-APP/releases/download/v1.1.4/app-universal-release.apk)  
**[app-universal-release.apk](https://github.com/mpshimul/BDIX-Live-TV-APP/releases/download/v1.1.4/app-universal-release.apk)** (~126 MB)

### Android 64-bit (ARM64)
**[app-arm64-v8a-release.apk](https://github.com/mpshimul/BDIX-Live-TV-APP/releases/download/v1.1.4/app-arm64-v8a-release.apk)** (~82 MB)

### Android 32-bit (ARMv7)
**[app-armeabi-v7a-release.apk](https://github.com/mpshimul/BDIX-Live-TV-APP/releases/download/v1.1.4/app-armeabi-v7a-release.apk)** (~66 MB)

**Installation Instructions for Android:**
1. Download the APK that matches your device
2. Enable "Install from Unknown Sources" in your phone settings
3. Tap the downloaded APK to install
4. Open the app and enjoy!

---

## 🐛 Bug Fixes & Improvements

- **Script Download Reliability**: Fixed multiple parallel downloads causing API errors and crashes
- **Versioned Script Folders**: Scripts are now stored in a version‑specific folder (e.g., `scripts_v114`) to prevent conflicts when updating the app
- **Sports Service**: Complete rewrite using local scripts – no more GitHub download failures
- **Movie & Series Sync**: Added script initialization before scraping to ensure scripts are ready
- **GitHub Token Handling**: Thread‑safe token retrieval and caching reduces unnecessary API calls
- **Channel Cache**: Prevents saving empty channel lists that could overwrite valid caches
- **Backup Channels**: Now kept separate from the main combined cache to avoid confusion

---

## 💡 Tips

- **Sports Tab**: Click the refresh button to get the latest live matches – the new implementation is faster and more reliable
- **First Launch**: The app will download the required Python scripts once; subsequent launches will use the cached version
- **Upgrading from v1.1.3**: Your settings and data are preserved, and the new version will automatically clean up old script folders

---

**Note**: The Windows PC version remains at v1.1.2. Only the Android app has been updated in this release.
