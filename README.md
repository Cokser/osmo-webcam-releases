<p align="center"><img src="https://cokser.github.io/osmo-webcam-releases/assets/osmo-webcam.png" width="160" alt="Osmo Webcam app icon"></p>

# Osmo Webcam

**Your camera. Your point of view.**

USB pan, tilt and zoom controls for Osmo Pocket 4 on Mac. Save the camera angles you use and recall them from the desktop app, Stream Deck or other local software. OBS keeps your direct USB video.

[**Downloads & release availability**](https://cokser.github.io/osmo-webcam-releases/#downloads) · [Setup guide](https://cokser.github.io/osmo-webcam-releases/setup.html) · [Support](https://cokser.github.io/osmo-webcam-releases/support.html) · [Release history](https://github.com/Cokser/osmo-webcam-releases/releases)

## What you can do

- Save up to twenty named pan/tilt/zoom presets per camera, with grid and list layouts.
- Choose transitions and replace an ongoing recall with your next selection.
- Adjust pan, tilt and zoom, use Stop, and use guarded Recenter for a reviewed setup.
- Use the companion Stream Deck plugin for live preset discovery, slots 1–20 and individual controls. Empty slots are no-ops.
- Connect other local software through the optional HTTP preset bridge or API v1. The app’s Integrations page has instructions and copy buttons.
- Keep presets and credentials on your Mac, without an app account or cloud preset storage.

## Preview configuration

| Component | Target configuration |
| --- | --- |
| Mac | Apple Silicon, macOS 26 or later |
| Camera | Standard DJI Osmo Pocket 4, firmware 01.03.14.04 |
| Video | Direct USB capture in OBS; OBS Virtual Camera for the optional app preview |
| Stream Deck | Optional companion plugin; Stream Deck 6.6 or later |

Intel Macs, older macOS, Windows, Linux, other cameras and other firmware versions are not supported by this build. Camera hardware, OBS and Stream Deck software are provided separately. The companion plugin is distributed directly; do not assume Marketplace availability.

## Install and start

Check the [downloads page](https://cokser.github.io/osmo-webcam-releases/#downloads) for public release availability. Published releases include versioned app/plugin installers, release notes and SHA-256 checksums. Local development builds are separate from public releases.

1. Download the official app installer when available and choose **Install for This User**. The app lives in `~/Applications/Osmo Webcam.app`.
2. Connect the Pocket 4 over USB in webcam mode. Keep video in OBS, then enable OBS Virtual Camera for the app preview.
3. Confirm a stationary, fixed setup with tracking off and a clear motion window before enabling controls.
4. Capture a view with **Add Preset**. Open **Integrations** for Stream Deck pairing and local HTTP examples.

The preview is experimental. Read the compatibility and qualification notes for the exact release you install. Camera readback and completed requests do not establish physical arrival or immediate motor stop. Stop cancels further scheduling; a finite command already accepted by the camera may finish. Interrupted movement is never replayed.

## Updates and help

Use **App Updates → Update & Restart** for an installed app. Recovery checks saved state before reopening with controls disarmed. Update the Stream Deck plugin separately with its compatible installer.

[Report an issue](https://github.com/Cokser/osmo-webcam-releases/issues/new) with app/plugin versions, macOS, camera firmware, reproduction steps and the visible error code. Issues are public: remove tokens, HTTP keys, device identifiers and private recordings. **Reveal Diagnostics** opens local files and does not upload them.

## About this repository

This repository contains public downloads, documentation and issue tracking. Application source is maintained separately and is private.

The free preview is available under the [preview license](https://cokser.github.io/osmo-webcam-releases/LICENSE.txt). Read the [privacy information](https://cokser.github.io/osmo-webcam-releases/privacy.html) and [third-party notices](https://cokser.github.io/osmo-webcam-releases/third-party.html).

Independent software; not affiliated with or endorsed by DJI, Elgato or OBS. All third-party trademarks belong to their respective owners.
