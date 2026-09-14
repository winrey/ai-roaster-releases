# AI Roaster

[简体中文](README.md) · **English** · [日本語](README.ja.md)

**Make every quota count.**

A personal dashboard for AI subscription usage: view your accounts, remaining quotas, and usage history for Codex, the Claude desktop app, and Claude Code in one place, and manage account switching locally.

[Downloads and release notes](https://github.com/winrey/ai-roaster-releases/releases) · [macOS installation guide](INSTALL.en.md) · [Report an issue](https://github.com/winrey/ai-roaster-releases/issues)

## Downloads and updates

Choose a version in Releases and download `YuHuo-AI-Roaster_<version>_macOS_universal.dmg`. The universal installer includes both Apple silicon and Intel architectures. Each release includes installation instructions, build information, and SHA-256 checksums.

The currently recommended release is the [0.2.3 notarized preview](https://github.com/winrey/ai-roaster-releases/releases/tag/v0.2.3). Both the app and DMG are Developer ID signed, notarized by Apple, and stapled with notarization tickets; Gatekeeper checks passed. See each earlier release for its own verification status. The app has not yet been tested on a physical Intel Mac.

In the currently published v0.2.3 installer, the app is still named **余火 · AI Roaster** and its interface is in Chinese. The English and Japanese links on this page are translations of the documentation.

Starting with 0.2.1, the upper-right menu includes “检查软件更新” (Check for software updates), which checks this repository's public GitHub Releases for newer versions. By default, it checks stable releases only; select “包含预发布版本” (Include prereleases) to receive preview releases. Update checks provide a download link; you install updates yourself.

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
