<div align="center">

<img src="assets/logo.png" width="116" alt="lomme application icon">

# lomme

**A simple, Mac-like archive utility for Windows — calm, clean, and easy to use.**

Windows 11 · ZIP / 7Z / RAR · Eight languages

[**Download (coming soon)**](https://github.com/so1fr1d/lomme/releases) · [Features](#features) · [Installation](#installation)

</div>

<p align="center">
  <img src="assets/main-light-dark.png" alt="lomme showing a ZIP archive in light and dark themes" width="900">
</p>

## Meet lomme

A small native Windows archive utility, with a familiar interface for browsing, creating, and extracting archives. No clutter, just the essentials.

| Format | Create | Extract |
| :--- | :---: | :---: |
| **ZIP** | ✓ | ✓ |
| **7Z** | ✓ | ✓ |
| **RAR** | — | ✓ |

## In action

Double-click a supported archive when lomme is its default app to extract it right away.

<p align="center">
  <img src="assets/extract-demo.gif" width="480" alt="lomme automatically extracting a ZIP archive">
</p>

*For smaller archives, extraction may finish so quickly that the progress window never appears.*

To look inside an archive instead, select **Open with lomme** from File Explorer's context menu.

## Features

lomme works with archives much like File Explorer: browse folders, drag files in or out, double-click to open, and add or remove items in supported formats.

- **Quick extract:** double-click an associated archive to extract it without bringing the main app to the foreground. Small archives may finish before a progress window appears.
- **Password protection:** create encrypted archives; 7Z supports Unicode passwords and file-name encryption, while ZIP creation uses ASCII passwords for compatibility.
- **ESC shortcuts:** close an idle window or dismiss a dialog with ESC, while active operations are protected from accidental closing.

Light and dark themes, eight interface languages, and File Explorer integration are included.

### Explore an archive

<p align="center">
  <img src="assets/archive-window.png" alt="A ZIP archive opened in lomme" width="900">
</p>

### Choose your language

<p align="center">
  <img src="assets/languages.png" alt="lomme language selection menu" width="300">
</p>

## Installation

**Version 1.0.0 is being prepared for its first public release.** When available, download the installer from [GitHub Releases](https://github.com/so1fr1d/lomme/releases).

The installer supports eight languages and installs for the current Windows account. It doesn't automatically change your default apps: to associate `.zip`, `.7z`, and `.rar` with lomme, visit **Windows Settings → Apps → Default apps**.

<p align="center">
  <img src="assets/installer.png" alt="lomme Windows installer" width="600">
</p>

### File Explorer commands

- **Open with lomme** — browse archive contents.
- **Extract here** — extract alongside the archive.
- **Compress with lomme** — create ZIP or 7Z archives from files and folders.

On Windows 11, these commands appear under **Show more options**.

## Notes

- **RAR extraction only:** creating or modifying RAR archives is not supported.
- Use ASCII passwords when creating ZIP archives. 7Z supports Unicode passwords.
- Files opened temporarily from an archive are not automatically written back if edited.
- **Windows 11 x64** is the tested platform. Windows 10 is not verified.
- The public installer is planned to be **unsigned**. Its SHA-256 checksum will be provided with the release; keep Windows security protection enabled.
- The 1.0 installer is **not** an automatic in-place upgrade for older lomme 0.4.x installations.

## Uninstall

Remove lomme via **Windows Settings → Apps → Installed apps**. App-specific settings are deleted on uninstall, while your personal archive files are preserved. Uninstall remains available even if lomme is your default archive app.

## Credits & licenses

Made by **so1fr1d**.

lomme is free for personal and commercial use under its [freeware license](LICENSE.txt); the proprietary installer may not be redistributed without permission. Third-party rights remain separate. See [third-party notices](THIRD-PARTY-NOTICES.txt) and the source/license archives included with the release.
