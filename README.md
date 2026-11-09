# YouMod Repo

Automated YouMod IPA builds delivered straight to your AltStore, SideStore, or Feather. 100% no need to fork GitHub repos or find your own decrypted IPA files!

---

## How to Add This Repo

1. Open **AltStore / SideStore / Feather** on your device
2. Navigate to **Sources** or **Repos**
3. Tap **+** and paste the URL below:

```
https://raw.githubusercontent.com/MountainofPenguin/Altstore-Repository/main/apps.json
```

4. YouMod will appear under Browse — tap **Get** to install

> **Note:** You must have a signing method set up (AltStore, SideStore, Feather, Signulous, etc.) to install the IPA.

---

## Currently Supported

| | |
|---|---|
| **YouTube version** | 21.45.4 |
| **YouMod version** | 2.0.0 |
| **Last built** | November 9, 2026 |
| **Min iOS** | 14.0 |

---

## Included Tweaks

Only these tweaks are compiled in — nothing else. YTVideoOverlay is a hard runtime
dependency of YTUHD (its reload button registers through YTVideoOverlay), so it rides along.

| Tweak | Description |
|---|---|
| [YouMod](https://github.com/Tonwalter888/YouMod) | The core tweak. Ad removal, background playback, UI customisation, and more — without a paywall. |
| [YTUHD](https://github.com/Tonwalter888/YTUHD) | Unlocks 1440p and 2160p resolutions in the iOS YouTube app. |
| [Return YouTube Dislikes](https://github.com/PoomSmart/Return-YouTube-Dislikes) | Brings back the dislike count on YouTube videos. |
| [DontEatMyContent](https://github.com/therealFoxster/DontEatMyContent) | Prevents the player from hiding behind the notch or Dynamic Island. |
| [YTVideoOverlay](https://github.com/PoomSmart/YTVideoOverlay) | Not a separate feature — YTUHD is built as a YTVideoOverlay plugin and crashes without it, so it ships alongside. |

---

## How Automatic Builds Work

This repo builds and publishes a new YouMod IPA automatically.

```
Scheduled workflow checks for a new YouMod release (every 2 hours)
        ↓
config.yml is bumped to the new YouMod version
        ↓
GitHub Actions compiles the four tweaks from source
        ↓
cyan injects them into the decrypted YouTube IPA
        ↓
apps.json and a GitHub release updated with the new version, size and changelog
```

The YouTube version and its decrypted IPA URL are pinned in [`config.yml`](config.yml) — edit either value and push to trigger a new build manually.

A failed build is retried by the next scheduled check, so the repo does not get stuck on a broken version.

---

## 🙏 Credits

| Developer | Tweaks |
|---|---|
| [Tonwalter888](https://github.com/Tonwalter888) | YouMod, YTUHD |
| [PoomSmart](https://github.com/PoomSmart) | Return YouTube Dislikes, YTVideoOverlay |
| [therealFoxster](https://github.com/therealFoxster) | DontEatMyContent |
| [asdfzxcvbn](https://github.com/asdfzxcvbn) | cyan (IPA injection tool) |
