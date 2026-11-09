<div align="center">

# 🎵 JOY MUSIC

**An elegant, open-source YouTube Music client for Android**  
*Built with modern Kotlin, Jetpack Compose, and Material 3 Expressive design.*

[![Latest Release](https://img.shields.io/badge/Release-v13.6.6-8A2BE2.svg?style=for-the-badge&logo=android)](https://github.com/jehadjoy69-droid/apk-joy-music/raw/refs/heads/main/joymusic.apk)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](LICENSE)
[![Android](https://img.shields.io/badge/Android-8.0%2B-3DDC84.svg?style=for-the-badge&logo=android)](https://joymusic.site/)
[![Website](https://img.shields.io/badge/Website-joymusic.site-6C4BCC.svg?style=for-the-badge&logo=google-chrome)](https://joymusic.site/)

<br />

[**📥 Download Latest APK (v13.6.6)**](https://github.com/jehadjoy69-droid/apk-joy-music/raw/refs/heads/main/joymusic.apk) • [**🌐 Official Website**](https://joymusic.site/) • [**🐛 Report an Issue**](https://github.com/jehadjoy69-droid/apk-joy-music/issues)

</div>

---

## ✨ Features

- 🚫 **100% Ad-Free Listening:** Enjoy your favorite music without any video, banner, or audio advertisements.
- 🎨 **Material 3 Expressive UI:** Beautiful, fluid, and intuitive user interface adhering to Material Design 3 guidelines with expressive dynamic colors and fluid motion.
- 👥 **Listen Together:** Host or join private listening rooms to sync real-time playback seamlessly with your friends.
- 📜 **Real-Time Synchronized Lyrics:** Line-by-line synchronized and translated lyrics powered by multiple providers (LRCLIB, BetterLyrics, and Kugou).
- 🎧 **Background & Lock Screen Playback:** Keep playing music when the screen is off or while using other apps, complete with full notification controls.
- 🔍 **Full YouTube Music Library:** Instant access to millions of songs, albums, artists, official playlists, charts, and moods.
- 💾 **Offline Caching & Downloads:** Cache and download tracks locally for listening anytime, anywhere without an internet connection.
- 🎚️ **Audio Equalizer & Enhancements:** Built-in equalizer, bass boost, volume normalization, and audio offload.
- 📊 **Discord Rich Presence & Last.fm:** Real-time playback status with album artwork on Discord and seamless Last.fm scrobbling.
- 🔒 **Privacy Focused:** Open source, no account required, and no intrusive trackers.

---

## 📥 Download & Installation

You can download the latest official release APK directly from this repository or from our official website:

| Package | Version | Size | Download |
| :--- | :---: | :---: | :---: |
| **JOY MUSIC Universal APK** | `v13.6.6` | `22.8 MB` | [**Download APK**](https://github.com/jehadjoy69-droid/apk-joy-music/raw/refs/heads/main/joymusic.apk) |

> **Note:** Supported on **Android 8.0 (Oreo / API 26)** and above. Compatible with `arm64-v8a` and `armeabi-v7a` architectures.

---

## 🛠️ Building From Source

### Prerequisites
- **JDK 21** or later
- **Android SDK** (API Level 36/37)
- **Git**

### Build Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/jehadjoy69-droid/apk-joy-music.git
   cd apk-joy-music
   ```

2. Build the debug APK:
   ```bash
   ./gradlew :app:assembleFossDebug
   ```

3. Build the release APK:
   ```bash
   ./gradlew :app:assembleFossRelease
   ```

The compiled APK will be located at:
`app/build/outputs/apk/foss/release/app-foss-release.apk`

---

## 🏗️ Architecture & Tech Stack

- **Language:** Kotlin 100%
- **UI Toolkit:** Jetpack Compose & Material 3
- **Dependency Injection:** Hilt / Dagger
- **Media Engine:** AndroidX Media3 / ExoPlayer
- **Network & Serialization:** Ktor, OkHttp, KotlinX Serialization, Protobuf
- **Database & Storage:** Room Database, Proto DataStore

---

## 👨‍💻 Creator & Maintainer

- **Lead Developer:** **Jehad Joy**  
  GitHub: [@jehadjoy15-stack](https://github.com/jehadjoy15-stack)  
  Website: [https://joymusic.site/](https://joymusic.site/)

---

## 📄 License

JOY MUSIC is licensed under the [GNU General Public License v3.0 (GPL-3.0)](LICENSE).  
Based on and inspired by Metrolist.
