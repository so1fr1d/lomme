<div align="center">

# lomme

**A simple, Mac-like archive utility for Windows — calm, clean, and easy to use.**

Create and extract ZIP and 7Z archives. Extract RAR archives, too.

**Windows 11 · ZIP / 7Z / RAR · 8 interface languages**

<!-- The approved hero artwork and download link will be added for the first release. -->

</div>

---

## At a glance

| Format | Create | Extract |
| :--- | :---: | :---: |
| **ZIP** | Yes | Yes |
| **7Z** | Yes | Yes |
| **RAR** | No | Yes |

- A compact native Windows interface with light and dark themes.
- Distinct ZIP, 7Z, and RAR document icons.
- Korean, English, Japanese, Simplified Chinese, Traditional Chinese, French, Spanish, and German.
- Password-protected archives and selected-item extraction.
- File Explorer commands to **open**, **extract**, or **compress** files and folders with lomme.

<!-- Add genuine, approved final-version screenshots here before launch. -->

## Download & install

**Version 1.0.0 is being prepared for its first public release.** The installer will be available under [Releases](https://github.com/so1fr1d/lomme/releases) once published.

Installation is per-user and does not require administrator privileges in the tested Windows 11 setup. During installation, you can choose from eight languages.

Windows does **not** automatically make lomme the default app for `.zip`, `.7z`, or `.rar`. If you want that behavior, open **Settings → Apps → Default apps** and select lomme for each extension.

**Note:** When lomme is the default app, double-clicking an archive in File Explorer extracts the archive rather than opening its contents list. Use **Open with lomme** to browse an archive.

### File Explorer

- **Open with lomme** — browse archive contents.
- **Extract with lomme** — extract beside the archive.
- **Compress with lomme** — create ZIP or 7Z archives from selected files or folders.

On Windows 11, these commands appear under **Show more options** in the right-click menu.

## Notes & limitations

- **RAR extraction only.** RAR creation is not supported.
- Use ASCII passwords when creating ZIP archives; 7Z supports Unicode passwords. ZIP AES compatibility depends on the receiving software.
- Files opened from inside an archive are temporary copies. Changes are not automatically saved back to the archive.
- Windows 11 x64 is the tested target. Windows 10 has not been verified.
- The first installer is planned to be **unsigned**. Check the published checksum and follow your system's security guidance.
- This installer is not an in-place upgrade for older lomme 0.4.x installations.

## Uninstall

Go to **Windows Settings → Apps → Installed apps → lomme → Uninstall**. You can remove lomme even while it is selected as a default archive app. App-specific settings are removed on uninstall; your personal archives are not removed.

## Credits & licenses

Developed by **so1fr1d**.

lomme uses third-party components including **7-Zip 26.04** and **Pretendard 1.3.9**. Their respective notices and applicable source-availability material will accompany the release.

lomme's own distribution terms will be published with the first release. Third-party license terms remain separate.
