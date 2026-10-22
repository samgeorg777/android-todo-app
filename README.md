# 📱 Todo Master for Android

[![GitHub Releases](https://img.shields.io/github/v/release/samgeorg777/android-todo-app?color=38bdf8&label=Latest%20Release)](https://github.com/samgeorg777/android-todo-app/releases)
[![Build Android APK](https://github.com/samgeorg777/android-todo-app/actions/workflows/build-apk.yml/badge.svg)](https://github.com/samgeorg777/android-todo-app/actions/workflows/build-apk.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, fast, and offline-capable **Todo List software** engineered specifically for Android devices. Featuring a sleek OLED dark theme, task categorization, priority tagging, completion analytics, and instant offline persistence.

---

## ✨ Features

- **📱 Mobile-First Experience:** Tailored for Android touchscreens with bottom sheets, swipe gestures, and tactile haptic audio feedback.
- **⚡ 100% Offline-Ready:** All tasks, tags, and settings are cached locally. No cloud sign-in required, zero latency.
- **🎯 Task Prioritization & Tags:**
  - **Priority Levels:** High (🔴), Medium (🟡), Low (🔵).
  - **Custom Categories:** General, Work, Personal, Shopping, Ideas.
- **📅 Smart Due Dates:** Automatic overdue detection and relative indicators ("Today", "Tomorrow").
- **📊 Real-Time Progress Meter:** Dynamic percentage meter and daily completion stats to keep you on track.
- **🔍 Quick Search & Filter Tabs:** Search tasks on-the-fly and filter by status (*All, Active, Completed, Urgent, Work, Personal*).
- **🌓 OLED Dark & Clean Light Themes:** Seamless toggle between pure obsidian dark mode and crisp daylight themes.
- **💾 Backup & Restore:** One-tap export of your tasks to JSON format for safekeeping.
- **🚀 Automated CI/CD:** GitHub Actions builds the installable `.apk` file automatically on every release.

---

## 📥 Installation

### Method 1: Install APK (Android Package)
1. Go to the [**Releases**](https://github.com/samgeorg777/android-todo-app/releases) tab.
2. Download the latest `app-debug.apk` directly to your phone.
3. Open and tap **Install**.

### Method 2: Offline Standalone App (Zero Installation)
1. Download or open `index.html` in your mobile browser (Chrome, Vivo Browser, Firefox).
2. Tap the browser menu (⋮) &rarr; **Add to Home screen** / **Install app**.
3. It launches instantly from your home screen as a standalone application.

---

## 🛠️ Project Structure

```
android-todo-app/
├── .github/
│   └── workflows/
│       └── build-apk.yml          # GitHub Actions APK builder & release publisher
├── app/
│   ├── src/main/
│   │   ├── AndroidManifest.xml   # Android manifest configuration
│   │   ├── assets/
│   │   │   └── index.html        # Embedded offline web engine
│   │   ├── java/                 # Native Android WebView wrapper
│   │   └── res/                  # Android styles & resources
│   └── build.gradle              # App build configuration
├── index.html                    # Complete standalone Todo software
├── manifest.json                 # PWA manifest
├── build.gradle                  # Root gradle configuration
└── settings.gradle               # Gradle project settings
```

---

## 📄 License
This project is open-source under the [MIT License](LICENSE).
