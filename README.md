YouMod Repo
Automated YouMod IPA builds delivered straight to your AltStore, SideStore, or Feather. Update your YouTube version, sit back — the repo handles the rest.
Included Tweaks

YouMod — The core tweak. Ad removal, background playback, UI customisation, and more — without a paywall.
YouPiP — Enables native Picture-in-Picture on the iOS YouTube app.
YTUHD — Unlocks 1440p and 2160p resolutions in the iOS YouTube app.
Return YouTube Dislikes — Brings back the dislike count on YouTube videos.
YTABConfig — Configures A/B settings in the iOS YouTube app.
YouSpeed — View and change video playback speed faster.
YouMute — Mute/unmute videos faster.
YouLoop — Loop YouTube videos seamlessly.
YouSlider — Customises the YouTube video slider and scrubber.
YouChooseQuality — Auto-selects your preferred video quality.
YouShare — Share videos faster from the iOS YouTube app.
YouGetCaption — View and copy captions from YouTube videos.
DontEatMyContent — Prevents the YouTube player from hiding behind the notch/Dynamic Island.
iSponsorBlock — Automatically skips sponsored segments in YouTube videos.
Gonerino — Filter videos, channels, and keywords from your feed.
YTweaks — Various quality-of-life tweaks for the iOS YouTube app.
YTHoldForSpeed — Hold on the video player to toggle a selected playback speed.
youtube-native-share — Replaces YouTube's share sheet with the native iOS one.
VolumeBoostYT — Gesture-based volume control completely separate from system volume.
Open in YouTube — Safari extension to open YouTube links directly in the app.


How to Add This Repo

Open AltStore / SideStore / Feather on your device
Navigate to Sources / Repos
Tap + and paste:

   https://raw.githubusercontent.com/MountainofPenguin/Altstore-Repository/main/apps.json

YouMod will appear under Browse — tap Get to install


Note: You must have a signing method set up (AltStore, SideStore, Feather, Signulous, etc.) to install the IPA.


How Automatic Builds Work
This repo builds and publishes a new YouMod IPA automatically — no manual intervention needed.

YouMod update detected → a scheduled workflow checks the YouMod GitHub releases every 3 hours
New YouTube IPA detected → a Telegram watcher service detects new decrypted IPAs and updates the config automatically
Build triggered → GitHub Actions compiles all tweaks from source and injects them into the YouTube IPA using cyan
Repo updated → apps.json is updated with the new version, download URL, size, and YouMod changelog automatically

You will always get the latest YouMod on the latest compatible YouTube version with zero manual steps.

Currently Supported
YouTube version21.17.3YouMod version1.2.1Last builtMay 2, 2026Min iOS14.0

Credits

Tonwalter888 — YouMod, YTUHD, YouShare
PoomSmart — YouPiP, YouSpeed, YouMute, YouLoop, YouSlider, YouChooseQuality, YouGetCaption, YTABConfig, Return YouTube Dislikes
asdfzxcvbn — cyan (IPA injection tool)
therealFoxster — DontEatMyContent
castdrian — Gonerino
Galactic-Dev — iSponsorBlock
fosterbarnes — YTweaks
joshuaseltzer — YTHoldForSpeed
bhackel — YouLoop
jkhsjdhjs — youtube-native-share
VasirakCalgux — VolumeBoostYT
BillyCurtis — Open in YouTube Safari Extension
