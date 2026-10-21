# Quick Launcher

<div align="center">

<img src="logo.png" alt="Quick Launcher Logo" width="100" height="100" style="border-radius: 20px;" />

### Group websites and desktop tools for one-click launching

[![Release](https://img.shields.io/badge/Release-v0.1.0-2ea043.svg)](https://github.com/Neil-Enrera/Quick-Launcher-App/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS-0078D6.svg)](https://github.com/Neil-Enrera/Quick-Launcher-App/releases)
[![Electron](https://img.shields.io/badge/Electron-44.x-47848F.svg?logo=electron)](https://www.electronjs.org/)
[![Angular](https://img.shields.io/badge/Angular-22.x-DD0031.svg?logo=angular)](https://angular.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[**Download for Windows (.exe)**](https://github.com/Neil-Enrera/Quick-Launcher-App/releases/latest) | [**macOS Releases**](https://github.com/Neil-Enrera/Quick-Launcher-App/releases) | [View All Releases](https://github.com/Neil-Enrera/Quick-Launcher-App/releases) | [Report an Issue](https://github.com/Neil-Enrera/Quick-Launcher-App/issues)

</div>

---

## About Quick Launcher

Do you start every day repeating the same manual routine - opening work tabs, documentation, Spotify, VS Code, Discord, and terminals one by one?

**Quick Launcher** turns your startup routine into a single click. Organize websites and desktop tools into customized **Presets**, set your preferred browser, and fire up your entire workspace instantly.

---

## Supported Platforms

Quick Launcher is designed as a native cross-platform desktop application:

- **Windows 10 and 11** (x64)
- **macOS** (Intel and Apple Silicon / M-series)

---

## How to Download and Install

### Windows 10 and 11

1. **Download the Installer**:
   Download the latest installer from the [Releases page](https://github.com/Neil-Enrera/Quick-Launcher-App/releases) or click [Download Quick Launcher Setup](https://github.com/Neil-Enrera/Quick-Launcher-App/releases/latest).
2. **Install**:
   Double-click the downloaded `.exe` installer. Quick Launcher will install and automatically start.
3. **Desktop and Start Menu Shortcuts**:
   A shortcut will be created on your Desktop and in your Windows Start Menu for easy access.

> [!TIP]
> **Windows SmartScreen Note**: Because Quick Launcher is an open-source indie application without a commercial code-signing certificate, Windows SmartScreen may show a prompt on first launch. Click **"More info"** and then **"Run anyway"**.

### macOS

1. **Download the DMG**:
   Download the latest `.dmg` package from the [Releases page](https://github.com/Neil-Enrera/Quick-Launcher-App/releases).
2. **Install**:
   Open the `.dmg` file and drag **Quick Launcher** into your `/Applications` folder.
3. **Launch**:
   Open Quick Launcher from your Applications folder or Spotlight search.

> [!TIP]
> **macOS Gatekeeper Note**: On first launch of unsigned apps, right-click (or Control-click) Quick Launcher and choose **"Open"**, or go to **System Settings > Privacy & Security** and click **"Open Anyway"**.

---

## How to Use Quick Launcher

### 1. Interactive Onboarding Walkthrough
When you open Quick Launcher for the first time, a guided spotlight tour automatically introduces each feature step-by-step. You can navigate with `Next` / `Back` buttons or arrow keys, skip with `Esc`, and replay the tour anytime from the **Settings** dialog.

### 2. Create a Preset
- Click the primary **New preset** button in the top bar.
- Name your preset (for example: *Morning Standup*, *Web Dev Stack*, or *Gaming*).

### 3. Add URLs and Desktop Apps
- **Web Links**: Click **+ URL** and enter the website address (for example: `https://github.com`, `https://chatgpt.com`).
- **Desktop Software**: Click **+ App** to open the built-in **Installed Applications Picker**. Search through detected applications on your computer (VS Code, Spotify, Discord, Slack, etc.) or browse your disk to pick any executable (`.exe` on Windows, `.app` on macOS).
- **Custom CLI Arguments**: Need to launch an app with flags (such as `--incognito`, `-n`, or project directories)? Click the **CLI Arguments** button to add comma-separated parameters.

### 4. Choose Target Browser and Launch Delay
- **Target Browser**: Select which browser opens the web links for this preset (Safari, Google Chrome, Microsoft Edge, Mozilla Firefox, Brave, Opera, Vivaldi, Arc, or System Default).
- **Launch Delay**: Set the stagger delay between items (default 800 ms) to prevent system lag and focus clashes.

### 5. Launch with One Click
- Click **Launch preset** to fire up all your configured items in sequence.
- Need to stop mid-way? The button dynamically becomes **Stop launch** so you can cancel anytime.

---

## Shortcuts and System Integration

| Shortcut / Action | Platform | What it does |
|---|---|---|
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>L</kbd> | Windows | Global hotkey to summon or hide Quick Launcher anywhere |
| <kbd>Cmd</kbd> + <kbd>Option</kbd> + <kbd>L</kbd> | macOS | Global hotkey to summon or hide Quick Launcher anywhere |
| **Window Close (X)** | All | Minimizes Quick Launcher quietly to the system tray / menu bar |
| **Tray / Menu Bar Icon** | All | Click to restore the dashboard, or right-click to Quit |
| **System Startup** | All | Enable in Settings to have Quick Launcher launch automatically when your computer turns on |

---

## Feature Highlights

- **One-Click Multi-Launch**: Fire up web links and local applications in automated sequence.
- **Cross-Platform**: Full support for Windows 10/11 and macOS with native application launchers.
- **Interactive Guided Tour**: Spotlight walkthrough for beginners, replayable anytime.
- **Installed App Scanner**: Auto-detects desktop software installed on your machine.
- **Per-Preset Browser Choice**: Send work tabs to Chrome/Safari and personal links to Brave or Edge.
- **Safe and Concurrency-Locked**: Only one launch runs at a time with real-time Stop/Cancel controls.
- **Custom Arguments**: Optional CLI parameter support for developer tools and scripts.
- **Modern Dark Theme**: Curated dark UI with responsive layouts and green desktop accents.



## License

This project is open-source under the [MIT License](LICENSE).

## Author

**Neil Enrera**
- GitHub: [@Neil-Enrera](https://github.com/Neil-Enrera)
- Public App Repository: [Quick-Launcher-App](https://github.com/Neil-Enrera/Quick-Launcher-App)
