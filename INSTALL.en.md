# AI Roaster — macOS preview guide

[简体中文](INSTALL.md) · **English** · [日本語](INSTALL.ja.md)

[Back to the overview](README.en.md) · [Downloads and release notes](https://github.com/winrey/ai-roaster-releases/releases)

Make every quota count.

## Installation

1. Download `YuHuo-AI-Roaster_<version>_macOS_universal.dmg` from [Releases](https://github.com/winrey/ai-roaster-releases/releases) and open it.
2. Drag **余火 · AI Roaster** into **Applications**.
3. Open **余火 · AI Roaster** from Applications.

The currently published v0.2.3 installer still uses the app name shown above, and its interface is in Chinese. The English and Japanese guides retain the Chinese control names to help you find them.

If you installed an older version named AI Roaster, quit it before starting this version. The app's internal identifier is unchanged, so your existing accounts, credentials, settings, and history will continue to be used.

The universal installer includes both Apple silicon and Intel architectures. Runtime testing has been performed on macOS 26.1 with Apple silicon. Intel Macs and earlier macOS versions have not yet been tested on real devices.

The currently recommended release is the [v0.2.3 notarized preview](https://github.com/winrey/ai-roaster-releases/releases/tag/v0.2.3). Both the app and DMG are Developer ID signed, notarized by Apple, and stapled with notarization tickets; Gatekeeper checks passed. You may still see the normal confirmation that the app was downloaded from the internet when you first open it.

If macOS says it cannot verify the developer or blocks the app, first confirm that the installer came from this repository's Releases, then report the full message. For other versions, check the build information included with the installer for their notarization status.

If you have a **signed but unnotarized test build**, macOS may block it on first launch. After confirming its source, go to System Settings → Privacy & Security, choose Open Anyway, and confirm Open. This creates an exception for this app; you do not need to disable system-wide security protections. See [Apple's instructions](https://support.apple.com/en-us/102445).

## First use

- If Codex, the Claude desktop app, or Claude Code is installed and signed in, the app reads the current account's subscription and remaining quotas. If it does not detect the client, check the corresponding client path in “软件设置” (Software settings) at the upper right.
- You can also add accounts and quota records manually. Platforms such as Gemini currently require manual updates.
- The upper-right menu lets you choose “跟随系统” (System), “日间模式” (Light mode), or “夜间模式” (Dark mode).
- The current account updates automatically at your selected interval. Other accounts can be refreshed individually on their cards.
- Switching Codex or Claude desktop accounts closes and reopens the corresponding client, interrupting running tasks. Claude Code switches apply to new sessions; reopen existing sessions.
- The Claude desktop app and Claude Code share the quota for the same account, but store credentials separately. Sign in normally in the relevant client first. Then open “使用这个账号” (Use this account) on the account card, select that client in the dialog, and save its credentials so you can switch back later.
- If the app reports that the target email's login has expired (401), you can cancel, or confirm and sign in again in the corresponding client. The account is marked as active only after its identity has been verified.

## Data

The installer does not include the developer's accounts, credentials, or quota records. Your accounts and credentials are stored on your computer. Quota JSON exports do not include credential files.

History starts with existing snapshots and subsequent collection. Earlier usage is not reconstructed or invented.

## Feedback

Include your macOS version, whether you use Apple silicon or Intel, the app version, and the steps and screenshots that show the issue. Do not send account credential files, keys, or your complete data directory.
