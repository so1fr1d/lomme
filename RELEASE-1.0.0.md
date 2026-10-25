# lomme 1.0.0 — First public release

**A simple, Mac-like archive utility for Windows — calm, clean, and easy to use.**

The first public release of lomme, a lightweight Windows utility for creating and extracting ZIP and 7Z archives and extracting RAR archives.

## Highlights

- Clean light and dark themes with custom lomme archive icons.
- Create and extract ZIP / 7Z, and extract RAR.
- Browse archives with familiar Explorer-like interactions.
- Quick extraction from File Explorer, without bringing the main application to the foreground.
- Drag-and-drop, password-protected archives, and eight interface/installer languages.
- Per-user installation and an ordinary Windows uninstall flow.

## Installation

1. Download `lomme-setup-1.0.0.exe` from this release.
2. Run it on **Windows 11 x64**.
3. To use lomme as the default archive app, choose it in **Windows Settings → Apps → Default apps** for `.zip`, `.7z`, and `.rar`.

When lomme is the default app, double-clicking an archive extracts it. To browse it first, choose **Open with lomme** under **Show more options** in File Explorer.

## Formats

| Format | Create | Extract |
| --- | :---: | :---: |
| ZIP | ✓ | ✓ |
| 7Z | ✓ | ✓ |
| RAR | — | ✓ |

## Notes

- RAR creation is not supported.
- On Windows 11, Explorer commands appear under **Show more options**.
- Use ASCII passwords when creating ZIP archives; 7Z supports Unicode passwords and file-name encryption.
- Windows 10 is not verified.
- The installer is **unsigned**; do not disable Windows security protections to install it.
- Automatic in-place migration from older lomme 0.4.x versions is not supported.

## Release files

- `lomme-setup-1.0.0.exe`
- `SHA256SUMS.txt`
- `LICENSE.txt`
- `THIRD-PARTY-NOTICES.txt`
- `third-party-licenses.zip`
- `7z2604-src.7z`

Verify the installer against SHA256SUMS.txt. lomme is free for personal and commercial use; redistribution of its proprietary installer is restricted by LICENSE.txt. Third-party license rights remain separate.
