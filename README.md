# Grammarlix

A small floating grammar checker for Windows, powered by Harper. Checks run locally on your device.

[Download the latest Windows installer](https://github.com/FarzadAziziZade/Grammarlix/releases)

## How to use it

1. Select text in the app where you are working.
2. Click the floating **G** icon, or right-click it and choose **Check selected text**.
3. Review the suggestions and accept the changes you want.
4. Choose **Copy text**, then paste the result into your editor.

If selected text is unavailable, choose **Paste text for review**. Right-click the icon to move it, open settings, or hide it. Restore it from the Windows notification area.

Grammarlix starts in manual mode. Optional automatic checking is available from the notification area menu. The right-click menu belongs to the Grammarlix icon, rather than to other applications.

## Updates (including betas)

Settings offers **Check for updates** and a preference for daily automatic updates. Updates come from this repository's GitHub Releases and are verified against Grammarlix's updater signing key before installation. Restart after an update when requested.

## Requirements

Windows 10 version 1809 or later, or Windows 11, on x64-compatible hardware. Microsoft WebView2 is required; Setup can install it with an internet connection. Some apps do not expose selected text through Windows accessibility. Use the paste workflow in those apps.

This repository contains release downloads, documentation, update metadata, and license notices. It does not contain the Grammarlix application source code. Windows installers are not Authenticode signed; updater signatures are a separate verification mechanism.

## Credits and licenses

Developed by [FarzadAziziZade](https://github.com/FarzadAziziZade). Grammar checking uses [Harper](https://github.com/Automattic/harper), licensed under Apache 2.0. License and third-party notices are included with the application.

GitHub automatically labels repository archives as "Source code". These archives contain only the documentation and update metadata in this repository, not the Grammarlix application source.
