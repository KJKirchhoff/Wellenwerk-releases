# Wellenwerk

Live loudness and spectrum analysis plus multi-format master rendering for macOS.

## ⬇ Download

**[Wellenwerk 0.10.0 for Mac (DMG, 20 MB)](https://github.com/KJKirchhoff/Wellenwerk-releases/releases/download/v0.10.0/Wellenwerk-0.10.0.dmg)** — test version

All versions and release notes: [Releases](https://github.com/KJKirchhoff/Wellenwerk-releases/releases) · **[Manual (PDF)](Wellenwerk%20Manual.pdf)**

Requires a Mac with Apple silicon (M1 or newer) and macOS 14.6 or newer.

## Install
1. Download the DMG above and open it.
2. Drag both apps onto Applications.
3. First start: macOS blocks the app because it isn't notarized yet. Go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.

The DMG contains two apps: **Wellenwerk Live Analysis** and **Wellenwerk Rendering** (each with its own license; a bundle key covers both). Details (permissions, license, updates, uninstalling) are in `Read me first.txt` inside the DMG.

## What it does
- **Live Analysis:** loudness (LUFS, true peak, LRA), spectrum with references, stereo image, levels — from your interface or straight from whatever your Mac plays (Ableton, Spotify …), no extra driver.
- **A/B with references:** level-matched switching between your mix and reference tracks.
- **Rendering:** render masters into several formats (WAV, MP3, AAC, FLAC …) and measure the results.
- **Phone and iPad:** meter views on your phone over Wi-Fi.

## What's new in 0.10.0
- **Two apps:** Wellenwerk Live Analysis and Wellenwerk Rendering (opens straight into its window, no Wi-Fi access needed). Existing license keys work for both.
- **Listen part** per reference with a bigger waveform, zoom, rename / duplicate / delete with undo, own hotkey per reference
- **No reference** row, and one **Match** switch for hearing and seeing the reference at your loudness
- New look and a new default layout; windows always open fully on screen, also on smaller Macs
- Updated manual (PDF)

Updating from 0.9.0: quit Wellenwerk, move the old **Wellenwerk** app to the Trash (settings, references and license stay), then drag both new apps onto Applications.

Known limitations: not notarized yet (see Install), macOS may ask for permissions again after an update, and without a license key each app runs as a demo.

## License
Wellenwerk is not open source. Use is governed by the [license agreement](License%20Agreement.txt). Without a license key it runs as a demo. This test version is shared with friends; licenses are issued by Kilian Kirchhoff.

Third-party components (FFmpeg, LAME, libogg, libvorbis, Opus, libsoxr, libFLAC, the fonts Montserrat and Karla) are used under their own licenses, included in the app under `Contents/Resources/Licenses`.
