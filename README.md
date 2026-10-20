# âš¡ Quick Launcher

<div align="center">

<img src="logo.png" alt="Quick Launcher Logo" width="100" height="100" style="border-radius: 20px;" />

### Group websites and desktop tools for one-click launching

[![Release](https://img.shields.io/badge/Release-v0.1.0-2ea043.svg)](https://github.com/Neil-Enrera/Quick-Launcher-App/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D6.svg?logo=windows)](https://github.com/Neil-Enrera/Quick-Launcher-App/releases)
[![Electron](https://img.shields.io/badge/Electron-44.x-47848F.svg?logo=electron)](https://www.electronjs.org/)
[![Angular](https://img.shields.io/badge/Angular-22.x-DD0031.svg?logo=angular)](https://angular.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[ðŸ“¥ **Download for Windows (.exe)**](https://github.com/Neil-Enrera/Quick-Launcher-App/releases/download/v0.1.0/Quick.Launcher.Setup.0.1.0.exe) â€¢ 
[View All Releases](https://github.com/Neil-Enrera/Quick-Launcher-App/releases) â€¢ 
[Report an Issue](https://github.com/Neil-Enrera/Quick-Launcher-App/issues)

</div>

---

## ðŸ“– About Quick Launcher

Do you start every day repeating the same manual routine â€” opening work tabs, documentation, Spotify, VS Code, Discord, and terminals one by one?

**Quick Launcher** turns your startup routine into a single click. Organize websites and desktop tools into customized **Presets**, set your preferred browser, and fire up your entire workspace instantly.

---

## ðŸ“¥ How to Download & Install

### Windows 10 / 11

1. **Download the Installer**:
   ðŸ‘‰ Click here to download **[Quick Launcher Setup 0.1.0.exe](https://github.com/Neil-Enrera/Quick-Launcher-App/releases/download/v0.1.0/Quick.Launcher.Setup.0.1.0.exe)** (or visit the [Releases page](https://github.com/Neil-Enrera/Quick-Launcher-App/releases)).
2. **Install**:
   Double-click the downloaded `.exe` installer. Quick Launcher will install and automatically start.
3. **Desktop & Start Menu**:
   A shortcut will be created on your Desktop and in your Windows Start Menu for easy access.

> [!TIP]
> **Windows SmartScreen Note**: Because Quick Launcher is an open-source indie application without an expensive commercial code-signing certificate, Windows SmartScreen may show a prompt on first launch. Simply click **"More info"** and then **"Run anyway"**.

---

## ðŸš€ How to Use Quick Launcher

### 1. Interactive Onboarding Walkthrough
When you open Quick Launcher for the first time, a guided spotlight tour will automatically introduce each feature step-by-step. You can navigate with `Next` / `Back` buttons or arrow keys, skip with `Esc`, and replay the tour anytime from the **Settings** dialog.

### 2. Create a Preset
- Click the primary **New preset** button in the top bar.
- Name your preset (e.g., *Morning Standup*, *Web Dev Stack*, or *Gaming*).

### 3. Add URLs and Desktop Apps
- **Web Links**: Click **+ URL** and enter the website address (e.g. `https://github.com`, `https://chatgpt.com`).
- **Desktop Software**: Click **+ App** to open the built-in **Installed Applications Picker**. Search through all detected applications on your PC (e.g., VS Code, Spotify, Discord, Steam) or click *Browse file on disk...* to pick any custom `.exe` file.
- **Custom CLI Arguments**: Need to launch an app with flags (e.g. `--incognito`, `-n`, or project paths)? Click the **CLI Arguments** button to add comma-separated parameters.

### 4. Choose Target Browser & Launch Delay
- **Target Browser**: Select which browser opens the web links for this preset (Google Chrome, Microsoft Edge, Mozilla Firefox, Brave, Opera, Vivaldi, or System Default).
- **Launch Delay**: Set the stagger delay between items (default 800 ms) to keep your PC fast and prevent focus clashes.

### 5. Launch with One Click
- Click **Launch preset** to fire up all your configured items in sequence.
- Need to stop mid-way? The button dynamically becomes **Stop launch** so you can cancel anytime.

---

## âŒ¨ï¸ Shortcuts & System Integration

| Shortcut / Action | What it does |
|---|---|
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>L</kbd> | Global hotkey to summon or hide Quick Launcher from anywhere in Windows |
| **Window Close (X)** | Minimizes Quick Launcher quietly to the system tray |
| **System Tray Icon** | Click to restore the dashboard, or right-click to Quit |
| **Start at Login** | Enable in Settings to have Quick Launcher ready whenever you boot your PC |

---

## âœ¨ Feature Highlights

- âš¡ **One-Click Multi-Launch**: Fire up web links and local applications in automated sequence.
- ðŸŽ¯ **Interactive Guided Tour**: Beautiful spotlight walkthrough for beginners, replayable anytime.
- ðŸ”Ž **Installed App Scanner**: Auto-detects desktop software installed on your machine.
- ðŸŒ **Per-Preset Browser Choice**: Send work tabs to Chrome and personal links to Brave or Edge.
- ðŸ›¡ï¸ **Safe & Concurrency-Locked**: Only one launch runs at a time with real-time Stop/Cancel controls.
- âš™ï¸ **Custom Arguments**: Optional CLI parameter support for developer tools and scripts.
- ðŸŒ™ **Modern Dark Theme**: Curated dark UI with responsive layouts and green desktop accents.

---

## ðŸ› ï¸ For Developers (Source Code)

To build and run Quick Launcher from source:

### Prerequisites
- **Node.js**: v20 or v22+
- **npm**: v10+

### Clone & Run Locally
```bash
# Clone the repository
git clone https://github.com/Neil-Enrera/Quick-Launcher.git
cd quick-launcher

# Install dependencies
npm install

# Start development mode (Electron + Angular hot reload)
npm run dev
```

### Testing & Packaging
```bash
# Run unit & smoke tests
npm run smoke

# Run full Playwright desktop end-to-end test suite (19 tests)
npm run test:e2e

# Build the Windows NSIS installer in release/
npm run dist
```

---

## ðŸ“„ License

This project is open-source under the [MIT License](LICENSE).

## ðŸ‘¤ Author

**Neil Enrera**
- GitHub: [@Neil-Enrera](https://github.com/Neil-Enrera)
- Public App Repository: [Quick-Launcher-App](https://github.com/Neil-Enrera/Quick-Launcher-App)

