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
| **YouTube version** | 21.17.3 |
| **YouMod version** | 1.2.2 |
| **Last built** | May 3, 2026 |
| **Min iOS** | 14.0 |

---

## Included Tweaks

| Tweak | Description |
|---|---|
| [YouMod](https://github.com/Tonwalter888/YouMod) | The core tweak. Ad removal, background playback, UI customisation, and more — without a paywall. |
| [YouPiP](https://github.com/PoomSmart/YouPiP) | Enables native Picture-in-Picture on the iOS YouTube app. |
| [YTUHD](https://github.com/Tonwalter888/YTUHD) | Unlocks 1440p and 2160p resolutions in the iOS YouTube app. |
| [Return YouTube Dislikes](https://github.com/PoomSmart/Return-YouTube-Dislikes) | Brings back the dislike count on YouTube videos. |
| [YTABConfig](https://github.com/PoomSmart/YTABConfig) | Configures A/B settings in the iOS YouTube app. |
| [YouSpeed](https://github.com/PoomSmart/YouSpeed) | View and change video playback speed faster. |
| [YouMute](https://github.com/PoomSmart/YouMute) | Mute/unmute videos faster. |
| [YouLoop](https://github.com/bhackel/YouLoop) | Loop YouTube videos seamlessly. |
| [YouSlider](https://github.com/PoomSmart/YouSlider) | Customises the YouTube video slider and scrubber. |
| [YouChooseQuality](https://github.com/PoomSmart/YouChooseQuality) | Auto-selects your preferred video quality. |
| [YouShare](https://github.com/Tonwalter888/YouShare) | Share videos faster from the iOS YouTube app. |
| [YouGetCaption](https://github.com/PoomSmart/YouGetCaption) | View and copy captions from YouTube videos. |
| [DontEatMyContent](https://github.com/therealFoxster/DontEatMyContent) | Prevents the player from hiding behind the notch or Dynamic Island. |
| [iSponsorBlock](https://github.com/Galactic-Dev/iSponsorBlock) | Automatically skips sponsored segments in YouTube videos. |
| [Gonerino](https://github.com/castdrian/Gonerino) | Filter videos, channels, and keywords from your feed. |
| [YTweaks](https://github.com/fosterbarnes/YTweaks) | Various quality-of-life tweaks for the iOS YouTube app. |
| [YTHoldForSpeed](https://github.com/joshuaseltzer/YTHoldForSpeed) | Hold on the video player to toggle a selected playback speed. |
| [youtube-native-share](https://github.com/jkhsjdhjs/youtube-native-share) | Replaces YouTube's share sheet with the native iOS one. |
| [VolumeBoostYT](https://github.com/VasirakCalgux/VolumeBoostYT) | Gesture-based volume control completely separate from system volume. |
| [Open in YouTube](https://github.com/BillyCurtis/OpenYouTubeSafariExtension) | Safari extension to open YouTube links directly in the app. |

---

## How Automatic Builds Work

This repo builds and publishes a new YouMod IPA automatically.

```
YouMod update detected
        ↓
Scheduled workflow checks YouMod releases every 3 hours
        ↓
New YouTube IPA detected via Telegram watcher service
        ↓
GitHub Actions compiles all tweaks from source
        ↓
cyan injects tweaks into the YouTube IPA
        ↓
apps.json updated with new version, size, and changelog
```

You will always get the latest YouMod on the latest compatible YouTube version with zero manual steps.

---

## 🙏 Credits

| Developer | Tweaks |
|---|---|
| [Tonwalter888](https://github.com/Tonwalter888) | YouMod, YTUHD, YouShare |
| [PoomSmart](https://github.com/PoomSmart) | YouPiP, YouSpeed, YouMute, YouLoop, YouSlider, YouChooseQuality, YouGetCaption, YTABConfig, Return YouTube Dislikes |
| [asdfzxcvbn](https://github.com/asdfzxcvbn) | cyan (IPA injection tool) |
| [therealFoxster](https://github.com/therealFoxster) | DontEatMyContent |
| [castdrian](https://github.com/castdrian) | Gonerino |
| [Galactic-Dev](https://github.com/Galactic-Dev) | iSponsorBlock |
| [fosterbarnes](https://github.com/fosterbarnes) | YTweaks |
| [joshuaseltzer](https://github.com/joshuaseltzer) | YTHoldForSpeed |
| [bhackel](https://github.com/bhackel) | YouLoop |
| [jkhsjdhjs](https://github.com/jkhsjdhjs) | youtube-native-share |
| [VasirakCalgux](https://github.com/VasirakCalgux) | VolumeBoostYT |
| [BillyCurtis](https://github.com/BillyCurtis) | Open in YouTube Safari Extension |
