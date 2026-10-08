# Ampere — downloads

**[⬇ Download the latest release](https://github.com/ghostmodel/ampere-releases/releases/latest)**

Ampere is a desktop music player built with Electron:

- Classic Webamp-style skin
- Milkdrop visuals (Butterchurn)
- Worldwide internet radio via Radio Browser, SomaFM and Radio Paradise
- Local music library and playlists
- Tray icon and media keys

## Which file do I download?

Replace `X` with the version number (e.g. `0.6.1`).

| Your computer | Download |
| --- | --- |
| Mac with Apple Silicon (M1/M2/M3/M4) | `Ampere-X-arm64.dmg` |
| Mac with Intel processor | `Ampere-X.dmg` (the one *without* `arm64`) |
| Windows (installer, recommended) | `Ampere-Setup-X.exe` |
| Windows (portable, no install) | `Ampere-X-win.zip` |
| Linux (any distro, auto-updates) | `Ampere-X.AppImage` |
| Linux (Ubuntu/Debian, manual updates) | `ampere-electron_X_amd64.deb` |

You don't need the other files: the Mac `.zip` files, the `.blockmap` files and `latest*.yml` are used by Ampere's built-in updater.

## Updates

Once installed, Ampere keeps itself up to date:

- It checks for a new version shortly after it starts, and downloads it in the background.
- You can also check any time with **Help → Check for Updates…**
- When an update is ready you can restart right away, or choose **Later** and it installs the next time you quit.

Automatic updates work with the Mac apps, the Windows installer and the Linux AppImage. The Windows portable zip and the `.deb` don't update themselves; download the new version from this page.

## Security notes

- **Mac** builds are signed and notarized by Apple.
- **Windows** builds are currently **not code-signed**, so Windows SmartScreen may warn about an unrecognized app. Click **More info → Run anyway** to continue.

## About this repo

The source code is private; this repo only hosts release downloads. The "Source code (zip / tar.gz)" links GitHub adds to every release just contain this README.

License: MIT. Not affiliated with Winamp, Llama Group, Radionomy or TuneIn.
