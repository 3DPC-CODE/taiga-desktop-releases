# Taiga Personal Alerts — desktop app

Installers for **Taiga Personal Alerts**, the desktop app that reviews your Taiga projects with Claude Code on your own laptop (using your own Claude Pro or Max subscription) and shows the findings on your Taiga dashboard.

This repository only hosts the installers and the auto-update files. The source code lives in the private Taiga repository.

## Download

| Computer | Installer |
| --- | --- |
| macOS (Apple Silicon and Intel) | [Taiga-Personal-Alerts.dmg](https://github.com/3DPC-CODE/taiga-desktop-releases/releases/latest/download/Taiga-Personal-Alerts.dmg) |
| Windows | [Taiga-Personal-Alerts-Setup.exe](https://github.com/3DPC-CODE/taiga-desktop-releases/releases/latest/download/Taiga-Personal-Alerts-Setup.exe) |
| Linux | [AppImage](https://github.com/3DPC-CODE/taiga-desktop-releases/releases/latest/download/Taiga-Personal-Alerts.AppImage) · [.deb](https://github.com/3DPC-CODE/taiga-desktop-releases/releases/latest/download/Taiga-Personal-Alerts.deb) |

All versions: [Releases](https://github.com/3DPC-CODE/taiga-desktop-releases/releases).

## Install

The installers are not code-signed yet, so your computer asks once before opening them:

- **macOS:** open the `.dmg`, drag the app to **Applications**, then right-click it and choose **Open**, then **Open** again.
- **Windows:** in the SmartScreen window click **More info**, then **Run anyway**.

Then, in Taiga, open **Problem Alerts › Laptop settings › Connect a laptop** and follow the steps in the app. You do not need Node.js; the app installs Claude Code for you if it is missing.

## Updates

Windows and Linux (AppImage) update themselves. On macOS, download and install the new version from this page until the app is signed.
