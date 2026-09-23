# AI Roaster

[简体中文](README.md) · **English** · [日本語](README.ja.md)

**Make every quota count.**

A personal dashboard for AI subscription usage: view your accounts, remaining quotas, and usage history for Codex, the Claude desktop app, and Claude Code in one place, and manage account switching locally.

[Downloads and release notes](https://github.com/winrey/ai-roaster-releases/releases) · [macOS installation guide](INSTALL.en.md) · [Report an issue](https://github.com/winrey/ai-roaster-releases/issues)

## Downloads and updates

Choose a version in Releases and download `YuHuo-AI-Roaster_<version>_macOS_universal.dmg`. The universal installer includes both Apple silicon and Intel architectures. Each release includes installation instructions, build information, and SHA-256 checksums.

The currently recommended release is the [0.2.12 stable release](https://github.com/winrey/ai-roaster-releases/releases/tag/v0.2.12). See this release's `BUILD-INFO.txt` / `NOTARIZATION.json` for signing, notarization, and verification results, and `SHA256SUMS.txt` for file checksums. See each earlier release for its own verification status. The app has not yet been tested on a physical Intel Mac.

The interface supports English, Simplified Chinese, and Japanese, and follows your system language by default. To choose a language manually, open **Settings → General → Language** and click **Save settings**; your choice takes effect and is saved. The in-app name is **余火** in Chinese and **AI Roaster** in English and Japanese. Finder and Dock use the macOS language setting independently; their displayed name may update after macOS recognizes the app again.

Starting with v0.2.5, macOS supports in-app updates. **Check for updates** in the app menu reads the public releases repository and checks stable releases by default, with an option to include prereleases. Automatic checks and downloads are enabled by default: when a newer version provides a signed update package, the app downloads it in the background and verifies its signature. Installation and restart happen only when you click **Restart and update**.

You can adjust automatic checks and downloads separately. Turning off automatic checks also stops background downloads; manual checks and downloads remain available. If a release has no signed in-app update package, you can still open its release page, download the DMG, and install it manually.

**Users on v0.2.4 or earlier must manually install v0.2.5 or later once before they can use in-app updates.**

## Features

- Detect local logins, read quotas, and switch accounts for Codex, the Claude desktop app, and Claude Code.
- Multiple accounts and quota periods, manual corrections, and history charts.
- Subscription expiration dates, Credit balances and balance history, account tags, and tag search.
- Light, dark, and system themes, with adjustable frosted-glass transparency.
- macOS menu bar support, launch at login, and local JSON import and export.

Switching accounts in a desktop client closes and reopens that client, interrupting running tasks. Complete Claude login, live quota retrieval, and switching in both directions still need more testing on real devices.

## Data and feedback

Accounts, quota history, and credentials are stored on your own computer. Installers do not include the developer's account data. Update checks require no GitHub token and do not upload email addresses, credentials, or quota records.

When reporting an issue, include your operating system, chip type, app version, and steps to reproduce it. Hide private information in screenshots, and do not upload credential files or your complete data directory.

This repository hosts public installers, release notes, and issue reports. The app's source repository remains private. No open-source license has been specified for the project.
