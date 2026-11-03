<p align="center">
  <img src="assets/banner.png" alt="Groupy Pocket Banner" width="100%">
</p>

<p align="center">
  <a href="https://groupy.iriskernel.dev"><img src="https://img.shields.io/badge/Groupy%20Web-groupy.iriskernel.dev-38bdf8?style=flat&logo=safari&logoColor=white" alt="Groupy Web"></a>
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20iOS-10b981?style=flat" alt="Android and iOS">
  <img src="https://img.shields.io/badge/Format-APK%20%7C%20IPA-6366f1?style=flat" alt="APK & IPA">
  <img src="https://img.shields.io/badge/Storage-100%25%20Offline-f59e0b?style=flat" alt="100% Offline">
  <a href="https://github.com/iriskernel/groupy-pocket-releases/releases"><img src="https://img.shields.io/github/v/release/iriskernel/groupy-pocket-releases?color=ec4899&label=Latest%20Release" alt="Latest Release"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-3b82f6?style=flat" alt="MIT License"></a>
</p>

<p align="center">
  <a href="https://groupy.iriskernel.dev"><b>Website</b></a> ·
  <a href="#-quick-download"><b>Quick Download</b></a> ·
  <a href="#-what-is-groupy"><b>What is Groupy?</b></a> ·
  <a href="#-android-installation-guide"><b>Android Guide</b></a> ·
  <a href="#-ios-installation-guide"><b>iOS Guide</b></a> ·
  <a href="#-features-highlight"><b>Features</b></a> ·
  <a href="https://github.com/iriskernel/groupy-pocket-releases/releases"><b>All Releases</b></a>
</p>

---

Official public release repository for **Groupy Pocket** — the offline-first mobile audio player with real-time synced lyrics, background playback telemetry, GPU topographic shaders, and bidirectional cloud sync with [Groupy](https://groupy.iriskernel.dev).

> Free, open-source, offline-first, and privacy-respecting audio engine. Contains zero tracking, zero third-party telemetry, and zero ads: all music streams, downloads, and files remain sandboxed on your device.

## ⚡ Quick Download

| Platform | Format | Direct Download | Requirements & Compatibility |
| :--- | :---: | :--- | :--- |
| **Android** | `.apk` | [**Download GroupyPocket.apk**](https://github.com/iriskernel/groupy-pocket-releases/releases/latest/download/GroupyPocket.apk) | Android 8.0 (Oreo) or higher. Direct install, no root required. |
| **iOS** | `.ipa` | [**Download GroupyPocket.ipa**](https://github.com/iriskernel/groupy-pocket-releases/releases/latest/download/GroupyPocket.ipa) | iOS 15.0 or higher. Install via SideStore, AltStore, Sideloadly, or TrollStore. |
| **All Releases** | All | [**Browse All Releases**](https://github.com/iriskernel/groupy-pocket-releases/releases) | Full historical changelogs, build checksums, and update archives. |

---

## 🌌 What is Groupy?

**Groupy** ([groupy.iriskernel.dev](https://groupy.iriskernel.dev)) is a modern, web-first social music streaming ecosystem and audio platform. Featuring a signature dark elevation contour aesthetic, Groupy integrates ad-free music playback, synchronized real-time lyrics, community playlists, user profiles, and deep listening analytics into a unified browser experience.

### What is Groupy Pocket?

<p align="center">
  <img src="assets/showcase.png" alt="Groupy Pocket Interface Showcase: Offline Library, Now Playing Scrubber, and Timeframe Analytics" width="100%">
</p>

**Groupy Pocket** brings the power of Groupy straight into your pocket as a dedicated native mobile app for Android and iOS:

* 📴 **100% Offline Playback**: Download individual songs, full studio albums, or entire playlists directly to sandboxed local device storage. Listen on flights, road trips, or off-grid areas with zero mobile data usage.
* 🔄 **Bidirectional Cloud Sync**: Seamlessly links to your `groupy.iriskernel.dev` account. Playlists created on the web synchronize down to your phone, while offline plays in your pocket automatically sync back up to your profile telemetry when connectivity resumes.
* 🎧 **Native Background Audio & Lockscreen Controls**: Full integration with iOS `MPNowPlayingInfoCenter` and Android foreground media services. Control playback, scrub timelines, view album covers, and navigate previous tracks directly from your lock screen, Dynamic Island, or Bluetooth earbuds.
* 🎨 **GPU Shader Topography on Mobile**: Hardware-accelerated WebGL shader background featuring living contour lines that react in real-time to your selected accent theme or custom hex color.
* 📊 **Timeframe Analytics & Daily Tracker**: In-app statistics with instant toggles for **24 Hours**, **7 Days**, **1 Month**, and **1 Year**, plus a day-by-day listening breakdown to track how long you listened each day.
* 🎵 **Queue & Scrubber Precision**: Dedicated "Add to Queue" modal matching the Groupy website and an ultra-smooth 0.7s debounced slider for pixel-perfect scrubbing.

---

## 🤖 Android Installation Guide

Installing Groupy Pocket on Android takes less than a minute.

### Step-by-Step Instructions

1. **Download the APK**  
   Tap [**Download GroupyPocket.apk**](https://github.com/iriskernel/groupy-pocket-releases/releases/latest/download/GroupyPocket.apk) on your Android device (in Chrome, Firefox, or any browser).

2. **Open the Downloaded File**  
   Once the download completes, tap the download notification or navigate to your **Downloads** folder in your Files app and tap `GroupyPocket.apk`.

3. **Allow Installation from Unknown Sources (First time only)**  
   If your phone prompts you with *"For your security, your phone is not allowed to install unknown apps from this source"*:
   - Tap **Settings** in the dialog.
   - Toggle **Allow from this source** (or "Install unknown apps") to **ON**.
   - Press the back button to return to the installer.

4. **Install and Launch**  
   Tap **Install**. Once finished, tap **Open** to launch Groupy Pocket.

> [!NOTE]
> **Google Play Protect Notice**: If Google Play Protect displays a message stating *"Unrecognized app"*, simply tap **More details** and select **Install anyway**. Groupy Pocket is clean and built directly via automated GitHub Actions CI.

---

## 🍎 iOS Installation Guide

Because iOS does not allow direct APK-style sideloading without an installer tool, you install `GroupyPocket.ipa` using any standard sideloading utility (SideStore, AltStore, Sideloadly, or TrollStore).

### Method 1: SideStore (Recommended · Wire-Free on iPhone)

SideStore allows you to sign and refresh Groupy Pocket directly on your phone using on-device VPN without connecting to a computer.

1. Download [`GroupyPocket.ipa`](https://github.com/iriskernel/groupy-pocket-releases/releases/latest/download/GroupyPocket.ipa) in Safari on your iPhone.
2. Open the **SideStore** app.
3. Switch to the **My Apps** tab and tap the **`+`** icon in the upper-left corner.
4. Select `GroupyPocket.ipa` from your Files / Downloads.
5. SideStore will sign and install the app. Groupy Pocket will appear on your Home Screen.

---

### Method 2: AltStore

1. Download [`GroupyPocket.ipa`](https://github.com/iriskernel/groupy-pocket-releases/releases/latest/download/GroupyPocket.ipa) to your iPhone.
2. Launch **AltStore** and ensure your computer running AltServer is connected to the same Wi-Fi network.
3. Tap the **My Apps** tab, then tap the **`+`** icon.
4. Select the downloaded `GroupyPocket.ipa`.
5. AltStore will sign and install Groupy Pocket to your Home Screen.

---

### Method 3: Sideloadly (PC or Mac)

Sideloadly is the fastest method if you have a Mac or Windows PC.

1. Download and install [Sideloadly](https://sideloadly.io/) on your Mac or Windows computer.
2. Download [`GroupyPocket.ipa`](https://github.com/iriskernel/groupy-pocket-releases/releases/latest/download/GroupyPocket.ipa) to your computer.
3. Connect your iPhone or iPad to your computer using a USB cable.
4. Open Sideloadly. Your device should appear under **iDevice**.
5. Drag and drop `GroupyPocket.ipa` into the IPA icon box in Sideloadly.
6. Enter your Apple ID email (used strictly by Apple's free developer signing service).
7. Click **Start**. Sideloadly will package, sign, and install Groupy Pocket onto your device.

---

### Method 4: TrollStore (iOS 14.0 – 16.6.1 / 17.0)

If your device supports TrollStore:
1. Download `GroupyPocket.ipa` in Safari.
2. Tap the share sheet icon and select **Open in TrollStore**.
3. TrollStore installs Groupy Pocket permanently with no 7-day expiration or app limits.

---

### ⚠️ Essential iOS Post-Installation Step

The first time you open any sideloaded app on iOS, iOS requires you to trust your free personal developer certificate:

1. Open iPhone **Settings**.
2. Navigate to **General** > **VPN & Device Management** (or *Device Management*).
3. Under **Developer App**, tap your Apple ID email address.
4. Tap **Trust "[Your Apple ID]"** and confirm.
5. *(iOS 16+ only)*: If prompted, go to **Settings > Privacy & Security > Developer Mode**, toggle it **ON**, and restart your device when prompted.

---

## 🔄 Automatic In-App Updates

Groupy Pocket includes an automated in-app update detector:
* When a new version is released here on GitHub, a popup will automatically appear inside the app notifying you of the update and listing the new changelog highlights.
* Tap **Download Update** to immediately grab the latest build.
* You can also manually check for updates at any time by going to **Settings > Check for Updates**.

---

## ✨ Features Highlight

- 📴 **100% Offline-First Architecture**: Audio playback, playlist browsing, search, and lyric synchronization operate with zero internet connection.
- 🎨 **Topographic Contour Shaders**: GPU WebGL terrain shaders with audio reactivity and custom hex color accent theming.
- 📜 **Real-Time Synced Lyrics**: Apple Music & LRC time-synced lyrics with word-by-word scrolling and lockscreen real-time subtitle telemetry.
- 📊 **Continuous Listening Statistics**: Accurately tracks playtime, top artists, and songs even when your phone screen is locked or in your pocket.
- 🔁 **Up Next Queue & Fast Scrubber**: Smooth 0.7s debounced playback seeking and an instant Add-to-Queue library picker matching the Groupy website.
- ☁️ **Groupy Cloud Synchronization**: Bi-directional profile, badge, and playlist sync with your [Groupy](https://groupy.iriskernel.dev) account.

---

## 🌐 Community & Support

- **Website**: [groupy.iriskernel.dev](https://groupy.iriskernel.dev)
- **Releases & Updates**: [github.com/iriskernel/groupy-pocket-releases](https://github.com/iriskernel/groupy-pocket-releases)
- **Source Repository**: [github.com/iriskernel/groupy-pocket](https://github.com/iriskernel/groupy-pocket)
