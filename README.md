# Scoop Bucket

This is my personal [Scoop](https://scoop.sh/) bucket for custom and curated Windows applications.

## Manifests

This bucket includes the following manifests:

| App | Description | Install | Manifest | Website | Changelog |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **Click Paste** | Pastes clipboard contents as keystrokes to whatever location clicked | `scoop install clickpaste` | [📄](./bucket/clickpaste.json) | [🌐](https://github.com/Collective-Software/ClickPaste) | [🔗](https://github.com/Collective-Software/ClickPaste/releases) |
| **Helium Browser** | Chromium-based web browser focused on privacy, ad-blocking, and zero bloat | `scoop install helium-browser` | [📄](./bucket/helium-browser.json) | [🌐](https://helium.computer) | [🔗](https://github.com/imputnet/helium-windows/releases) |
| **Inter Font** | The Inter typeface family, carefully crafted & designed for computer screens | `scoop install inter-font` | [📄](./bucket/inter-font.json) | [🌐](https://rsms.me/inter/) | [🔗](https://github.com/rsms/inter/releases) |
| **Morphe Desktop** | CLI and GUI application using Morphe Patcher to patch Android apps | `scoop install morphe-desktop` | [📄](./bucket/morphe-desktop.json) | [🌐](https://github.com/MorpheApp/morphe-desktop) | [🔗](https://github.com/MorpheApp/morphe-desktop/releases) |
| **Pano Scrobbler** | Feature-rich music scrobbler for Windows, Linux & Android | `scoop install pano-scrobbler` | [📄](./bucket/pano-scrobbler.json) | [🌐](https://github.com/kawaiiDango/pano-scrobbler) | [🔗](https://github.com/kawaiiDango/pano-scrobbler/releases) |
| **Sonora** | Native music streaming client built with Rust and GPUI | `scoop install sonora` | [📄](./bucket/sonora.json) | [🌐](https://github.com/nolight132/sonora) | [🔗](https://github.com/nolight132/sonora/releases) |
| **Stremio Kai** | Refined all-in-one Stremio build with enhanced UI, metadata, and features | `scoop install stremio-kai` | [📄](./bucket/stremio-kai.json) | [🌐](https://github.com/allecsc/Stremio-Kai) | [🔗](https://github.com/allecsc/Stremio-Kai/releases) |
| **Umpv** | An mpv wrapper implementing single instance mode | `scoop install umpv` | [📄](./bucket/umpv.json) | [🌐](https://github.com/zhongfly/umpv-go) | [🔗](https://github.com/zhongfly/umpv-go/releases) |
| **VacuumTube** | Desktop YouTube Leanback (Smart TV UI) wrapper with built-in adblocker | `scoop install vacuumtube` | [📄](./bucket/vacuumtube.json) | [🌐](https://github.com/shy1132/VacuumTube) | [🔗](https://github.com/shy1132/VacuumTube/releases) |
| **WindHawk** | Customization marketplace and mod manager for Windows programs | `scoop install windhawk` | [📄](./bucket/windhawk.json) | [🌐](https://windhawk.net/) | [🔗](https://github.com/ramensoftware/windhawk/releases) |
| **Winhance** | C# application to debloat, optimize, and customize the Windows experience | `scoop install winhance` | [📄](./bucket/winhance.json) | [🌐](https://winhance.net/) | [🔗](https://github.com/memstechtips/Winhance/releases) |
| **Zen Browser** | Firefox-based browser focused on privacy and productivity | `scoop install zen-browser` | [📄](./bucket/zen-browser.json) | [🌐](https://zen-browser.app/) | [🔗](https://github.com/zen-browser/desktop/releases) |

## Installation

To add this bucket and install apps from it, run the following PowerShell commands:

### 1. Add the Bucket

```pwsh
scoop bucket add <bucketname> https://github.com/fahim-ahmed05/scoop-bucket
```

Replace `<bucketname>` with your preferred local name for the bucket (for example, `fahim` or `fahim-bucket`).

### 2. Install Apps

Once added, install any app from the bucket:

```pwsh
scoop install <app-name>
```

If an app name conflicts with another bucket, prefix it with the bucket name:

```pwsh
scoop install <bucketname>/<app-name>
```

### 3. Install Directly via URL

You can also install any manifest directly without adding the bucket first:

```pwsh
scoop install https://raw.githubusercontent.com/fahim-ahmed05/scoop-bucket/master/bucket/<app-name>.json
```

## Contributing

Want to add or improve a manifest?
Please read the following guides before submitting changes:

- [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
- [App Manifests Wiki](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)

Pull requests are always welcome!
