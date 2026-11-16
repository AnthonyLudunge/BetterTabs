<div align="center">

# BetterTab

### A better Alt+Tab experience for Windows.

Drag, place, and switch windows without leaving the familiar Windows workflow.

[![Latest release](https://img.shields.io/github/v/release/AnthonyLudunge/BetterTabs?style=for-the-badge&label=Latest)](https://github.com/AnthonyLudunge/BetterTabs/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/AnthonyLudunge/BetterTabs/total?style=for-the-badge&label=Downloads)](https://github.com/AnthonyLudunge/BetterTabs/releases)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=for-the-badge&logo=windows11&logoColor=white)

[Download BetterTab](https://github.com/AnthonyLudunge/BetterTabs/releases/latest) · [Report an issue](https://github.com/AnthonyLudunge/BetterTabs/issues)

</div>

---

## What is BetterTab?

BetterTab is a lightweight Windows background application that upgrades Alt+Tab with direct window placement. Switch normally, or drag a live window preview to an edge, corner, another monitor, or any free position on the screen.

It stays out of the way in the system tray and keeps the familiar Windows look—no dashboard and no unnecessary branding.

## Highlights

- **Drag to place** — move a window directly from the Alt+Tab switcher.
- **Hover to close** — reveal a Windows-style close button on any window tile.
- **Windows-native feel** — familiar layout, live previews, and keyboard behavior.
- **Flexible placement** — supports halves, corners, maximize, free positioning, and multiple monitors.
- **Two activation modes** — choose traditional **Hold** behavior or persistent **Press** behavior.
- **Tray controls** — enable, disable, start with Windows, change modes, or exit from the notification area.
- **Conflict handling** — prevents the built-in Windows switcher from opening underneath BetterTab.
- **Local-first** — no analytics, tracking, advertising identifiers, or telemetry uploads.

## Download

Get the newest Windows build from the **[Releases page](https://github.com/AnthonyLudunge/BetterTabs/releases/latest)**.

> Download `BetterTab-win-x64.zip` from the release assets. The automatically generated GitHub source archives are not the Windows application.

## Installation

1. Download `BetterTab-win-x64.zip` from the latest release.
2. Extract the ZIP to a folder of your choice.
3. Run `BetterTab.exe`.
4. Find BetterTab in the Windows notification area.

Windows SmartScreen may show a warning because the current build is not code-signed. Choose **More info**, verify the source, and continue only if you downloaded it from this repository.

## Using BetterTab

| Action | Result |
| --- | --- |
| `Alt` + `Tab` | Open BetterTab and move through available windows |
| `Shift` + `Tab` | Move backward through available windows |
| Release `Alt` in Hold mode | Activate the selected window |
| `Enter` or click | Activate the selected window |
| Drag a preview | Move and resize that window at the drop location |
| Hover a preview and click `×` | Ask that window to close without activating it |
| `Esc` | Close BetterTab without switching |

Right-click the tray icon to enable or disable BetterTab, select **Hold** or **Press** mode, configure startup, open GitHub, or exit.

## System requirements

- Windows 10 version 2004 (build 19041) or newer
- Windows 11
- 64-bit Intel or AMD processor

The release is self-contained; users do not need to install the .NET runtime separately.

## Verify your download

Each release includes `SHA256SUMS.txt`. To verify the ZIP in PowerShell:

```powershell
Get-FileHash .\BetterTab-win-x64.zip -Algorithm SHA256
```

Compare the displayed hash with the value in `SHA256SUMS.txt` before extracting the application.

## Support

Found a bug or have an idea? Open a **[GitHub issue](https://github.com/AnthonyLudunge/BetterTabs/issues/new)** and include your Windows version, BetterTab version, activation mode, and steps to reproduce the problem.

---

<div align="center">

**[Download BetterTab](https://github.com/AnthonyLudunge/BetterTabs/releases/latest)**

Built for Windows 10 and Windows 11.

</div>
