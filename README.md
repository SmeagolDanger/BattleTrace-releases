# BattleTrace

A fun, local combat-log analyzer for SWG Legends bounty hunters. Trace damage, defensive abilities, timing evidence, ship encounters, and export encounters as PDF reports.

## Download

Get the latest desktop build from [Releases](https://github.com/SmeagolDanger/BattleTrace-releases/releases/latest):

- **Windows x64:** download the `-x64-setup.exe` installer. It adds Start-menu and desktop shortcuts, and later updates download inside the app; choose **Restart and install** when you are ready.
- **macOS Apple Silicon:** download the `-arm64.zip`, extract it, and move BattleTrace to Applications. macOS updates are manual: the app tells you when a newer version exists and opens this page.

Builds are unsigned. Windows may show a SmartScreen prompt on first launch. macOS blocks the first launch: open **System Settings → Privacy & Security** and click **Open Anyway**, or run `xattr -dr com.apple.quarantine /Applications/BattleTrace.app` once.

## Moving from the Windows portable edition

Releases up to 0.9.4 also shipped a portable `.exe`. From 0.9.5 the installer is the only Windows download. To keep your saved library, follow the steps in the [0.9.5 release notes](https://github.com/SmeagolDanger/BattleTrace-releases/releases/tag/v0.9.5) before installing.

## Your data

Combat logs and analysis stay on your device. Existing profiles are reused so your saved library and preferences remain available. The app checks this public repository for updates; no GitHub account is required to download releases.

If BattleTrace meets a combat line it does not recognize, it offers to send only the redacted line *shape* (numbers become `#`, names become `<name>`) to the developer after you review it. No raw log text or character names are sent.

This repository contains downloads and release notes. Source development is maintained separately in a private repository. The automatically generated Source code archives here contain only this repository's public documentation.

## Feedback

Please [open an issue](https://github.com/SmeagolDanger/BattleTrace-releases/issues) with the app version and steps to reproduce a problem. Only share log excerpts you are comfortable making public.

Unofficial SWG Legends fan tool.
