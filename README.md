<div align="center">

# EditVault Downloader

**Download clips from YouTube, Instagram, TikTok, and more — built for video editors.**

[![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://editvault.net)
[![Version](https://img.shields.io/badge/Version-2.0.0-8B5CF6?style=for-the-badge)](https://license.editvault.me)
[![Python](https://img.shields.io/badge/Python-Not%20Required-22C55E?style=for-the-badge)](https://editvault.net)

[Website](https://editvault.net) · [Discord](https://discord.gg/9YYV5hyWKa) · [License & updates](https://license.editvault.me)

<br />

```
  ┌─────────────────────────────────────────────────────────────┐
  │  Paste URL  →  Pick quality  →  Download  →  Send to Editor │
  └─────────────────────────────────────────────────────────────┘
```

<br />

| | |
|:---:|:---:|
| **No Python. No pip. No terminal.** | Double-click `EditVault.exe` and go. |
| **Up to 8K** where the source allows | YouTube · Instagram · TikTok · and more |
| **Editor handoff** | DaVinci Resolve · Premiere Pro · After Effects |

</div>

---

## Why EditVault?

**EditVault Downloader** is a standalone Windows desktop app for creators who want fast, high-quality downloads and a smooth handoff into their NLE.

- Pick a platform and resolution (up to **8K** where available)
- Download to a dedicated folder under your **Videos** library
- Optional **Send to Editor** after each download
- Licensed through [EditVault Keygate](https://license.editvault.me) — sign in once, stay activated on your machine

> **First launch** can take 20–40 seconds while the single-file app unpacks. Later launches are faster.

---

## Quick start

<table>
<tr>
<td width="48" align="center"><strong>1</strong></td>
<td><strong>Extract</strong> the release folder anywhere (Desktop, Documents, etc.)</td>
</tr>
<tr>
<td align="center"><strong>2</strong></td>
<td>Double-click <code>EditVault.exe</code></td>
</tr>
<tr>
<td align="center"><strong>3</strong></td>
<td>Sign in with your <strong>EditVault license key</strong></td>
</tr>
<tr>
<td align="center"><strong>4</strong></td>
<td>On first launch, the app may download <strong>yt-dlp</strong> and <strong>FFmpeg</strong> once — wait until status shows <strong>Ready</strong></td>
</tr>
<tr>
<td align="center"><strong>5</strong></td>
<td>Paste a URL, choose resolution, download</td>
</tr>
</table>

---

## System requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10 or 11 (64-bit) |
| **RAM** | 4 GB+ recommended |
| **Disk** | ~500 MB for app; extra space for downloads and engine tools |
| **Network** | Required for login, downloads, and first-time engine setup |
| **Python** | **Not required** — runtime is bundled inside `EditVault.exe` |

---

## Supported platforms

<p align="center">

YouTube · Instagram · TikTok · SoundCloud · Facebook · X (Twitter) · Pinterest · Twitch · Vimeo · Patreon · LinkedIn

</p>

Playlist downloads are supported where the source allows (e.g. YouTube, SoundCloud, Vimeo, Patreon).

---

## Send to Editor

When enabled, finished files can be sent to a detected editor:

| Editor | Behavior |
|--------|----------|
| **DaVinci Resolve** | Import into the media pool |
| **Adobe Premiere Pro** | Reveal in project / import workflow |
| **After Effects** | Import into the project |

Configure editor detection and paths in **Settings**. Keep your NLE open before sending if the app reports it is not running.

---

## Where files live on your PC

EditVault keeps **portable** and **writable** data separate. You can move the `.exe` folder; settings and engines stay in your user profile.

### License, logs, and app data

| Platform | Folder |
|----------|--------|
| **Windows** | `%APPDATA%\EditVault\` |
| **macOS** | `~/Library/Application Support/EditVault/` |
| **Linux** | `~/.config/EditVault/` |

**Typical Windows path:**

```text
C:\Users\<You>\AppData\Roaming\EditVault\
```

| File / folder | Purpose |
|---------------|---------|
| `license.json` | Saved license (device activation) |
| `config.txt` | Shared EditVault config (same family as Resolve plugin) |
| `download_logs.txt` | Activity log shown in the app |
| `bin\` | Bundled **yt-dlp** (auto-downloaded) |
| `ffmpeg\` | Bundled **FFmpeg** / **ffprobe** (auto-downloaded) |
| `memory\` | App preferences (e.g. last platform, editor paths) |

> Uninstalling: delete `EditVault.exe` and, if you want a full reset, remove the `EditVault` folder under AppData above.

### Default download folder

| Platform | Default path |
|----------|----------------|
| **Windows** | `%USERPROFILE%\Videos\EditVault_Downloads` |
| **macOS** | `~/Movies/EditVault_Downloads` (or `~/Videos/EditVault_Downloads` if Movies is unavailable) |
| **Linux** | `~/Videos/EditVault_Downloads` |

You can change the folder anytime in the app with **Browse**.

---

## Updates

- **App updates**: Settings → check for a newer **EditVault** release ([license.editvault.me](https://license.editvault.me))
- **Engines**: Optional refresh of yt-dlp / FFmpeg from Settings (manual; does not run in the background)

Your installed version is shown in the app (currently **v2.0.0** for this package).

---

## Troubleshooting

| Issue | What to try |
|-------|-------------|
| Stuck on “Booting engine…” | Wait 1–2 minutes on first run; ensure internet works; check antivirus is not blocking `EditVault.exe` or `%APPDATA%\EditVault\bin\yt-dlp.exe`. |
| License invalid | Sign in again; confirm key is active at [license.editvault.me](https://license.editvault.me). |
| Download fails | Update engines in Settings; try another URL or lower resolution. |
| Send to Editor does nothing | Open the editor first; confirm only one target editor is running; check activity log in the app. |

**Activity log:** `%APPDATA%\EditVault\download_logs.txt`

---

## Links

| | |
|---|---|
| **Website** | [editvault.net](https://editvault.net) |
| **Discord** | [discord.gg/9YYV5hyWKa](https://discord.gg/9YYV5hyWKa) |
| **Licensing & API** | [license.editvault.me](https://license.editvault.me) |

---

## Legal

Use EditVault only for content you have the right to download and edit. EditVault is not affiliated with YouTube, Meta, TikTok, or other platforms. Trademarks belong to their owners.

---

<div align="center">

<sub>© EditVault · Windows desktop package · <code>EditVault.exe</code> + this README</sub>

<br /><br />

**Made for editors who'd rather be cutting than copy-pasting URLs.**

</div>
