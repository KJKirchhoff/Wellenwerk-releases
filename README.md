# Wellenwerk

Live loudness and spectrum analysis plus multi-format master rendering for macOS.

## ⬇ Download

**[Wellenwerk 0.9.0 for Mac (DMG, 8 MB)](https://github.com/KJKirchhoff/Wellenwerk-releases/raw/main/Wellenwerk-0.9.0.dmg)** — test version

Requires a Mac with Apple silicon (M1 or newer) and macOS 14.6 or newer.

## Install
1. Download the DMG above and open it.
2. Drag Wellenwerk onto Applications.
3. First start: macOS blocks the app because it isn't notarized yet. Go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.

Details (permissions, license, updates, uninstalling) are in `Read me first.txt` inside the DMG.

## What it does
- **Live Analysis:** loudness (LUFS, true peak, LRA), spectrum with references, stereo image, levels — from your interface or straight from whatever your Mac plays (Ableton, Spotify …), no extra driver.
- **A/B with references:** level-matched switching between your mix and reference tracks.
- **Rendering:** render masters into several formats (WAV, MP3, AAC, FLAC …) and measure the results.
- **Phone and iPad:** meter views on your phone over Wi-Fi.

## What's new in 0.9.0
First test version of the new Wellenwerk, rebuilt from scratch: one small app (18 MB instead of 465 MB), about a third of the CPU and a ninth of the memory while measuring, no Python and no BlackHole needed.
- Measure system audio directly ("Systemaudio: …") or route Mac audio through Wellenwerk, without a virtual driver
- Reference list with loudness, true peak, tonal curve and Δ to your mix; MIX | REF switch with level match
- Equal-loudness curves (ISO 226:2023) with Home / Studio / Club presets, fitted to your mix
- Third-octave view, meter and studio views for phone and iPad (also via iPhone hotspot)
- Single windows that remember size and position and can stay on top of full-screen apps

Known limitations: not notarized yet (see Install), macOS may ask for permissions again after an update, and without a license key Wellenwerk runs as a demo.

## License
Wellenwerk is not open source. Use is governed by the [license agreement](License%20Agreement.txt). Without a license key it runs as a demo. This test version is shared with friends; licenses are issued by Kilian Kirchhoff.

Third-party components (FFmpeg, LAME, libogg, libvorbis, Opus, libsoxr, libFLAC) are used under their own licenses, included in the app under `Contents/Resources/Licenses`.
