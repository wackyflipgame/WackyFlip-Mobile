# 📱 WackyFlip-Mobile

The official mobile version of [Wacky Flip](https://wackyflip.com) — optimized for Android and iOS devices.
Flip, bounce, and soar with touch-powered precision on the go!

---

## 🎯 Overview

`WackyFlip-Mobile` is the mobile-optimized port of the original Wacky Flip game, redesigned specifically for smartphones and tablets. Built with performance, responsiveness, and usability in mind, this version delivers the same wacky gameplay experience with intuitive touch controls, offline play, and platform-native enhancements.

Whether you're flipping during your commute or binging levels on your couch — Wacky Flip is now always at your fingertips.

---

## 📦 Key Features

* **📱 Touch-Optimized Controls**
  Tap, swipe, and press to perform flips, tricks, and aerial stunts

* **🚀 Fast, Lightweight, and Offline-Ready**
  Compact build size with minimal load time and full offline support

* **🎨 Adaptive UI & Layouts**
  Interface dynamically adjusts to different screen sizes and orientations

* **📲 Native Integrations**
  Haptic feedback, platform notifications, and social sharing via iOS & Android APIs

* **🕹️ Cross-Platform Progress Sync**
  Save and sync your progress between mobile and desktop versions via cloud support

---

## ⚙️ Tech Stack

* **React Native** – Cross-platform mobile framework
* **Expo** – Streamlined mobile development environment
* **Redux** – Game state and level data management
* **Lottie** – High-quality animations for menus and transitions
* **AsyncStorage** – Persistent offline storage for game data

---

## 📁 Project Structure

```
WackyFlip-Mobile/
├── assets/             # Images, sounds, fonts
├── components/         # Reusable UI and control components
├── screens/            # Game screens (Home, Level, Pause, Game Over)
├── game-engine/        # Mobile game logic (adapted from WackyFlip-Core)
├── utils/              # Helpers, storage, device detection
├── App.js              # App entry point
└── app.config.js       # Expo app configuration
```

---

## 🚀 Getting Started

### Prerequisites

* Node.js, Expo CLI
* iOS Simulator (Xcode) or Android Emulator (Android Studio)

### Installation

```bash
git clone https://github.com/wackyflipgame/WackyFlip-Mobile.git
cd WackyFlip-Mobile
npm install
```

### Run the App

```bash
npx expo start
```

Scan the QR code with Expo Go (on your mobile device) to test live.

---

## 📦 Build for App Store / Play Store

```bash
npx expo build:android
npx expo build:ios
```

For custom builds and native modules, eject from Expo and follow the native build guides.

---

## 🧪 Testing

* Unit tests using **Jest**
* Touch gesture testing with **Detox**
* Run `npm test` to begin test suite

---

## 👥 Contributing

Want to help make [Wacky Flip](https://wackyflip.com) mobile even better?

* Fork the repo
* Create a feature branch
* Submit a pull request with a clear description and test coverage

---

## 📜 License

This project is released under the **MIT License**.
All original game content (e.g., sprites, music, levels) © Wacky Flip Studios.

---

## 🔗 Related Projects

* [`WackyFlip-Core`](https://github.com/wackyflipgame/WackyFlip-Core) – Main game engine
* [`WackyFlip-Web`](https://github.com/wackyflipgame/WackyFlip-Web) – Website frontend
* [`WackyFlip-Assets`](https://github.com/wackyflipgame/WackyFlip-Assets) – Visual and animation assets

---

## 📬 Support

For bug reports, feedback, or mobile-specific requests, open an [issue](https://github.com/wackyflipgame/WackyFlip-Mobile/issues) or contact us at [support@wackyflip.com](mailto:support@wackyflip.com).
