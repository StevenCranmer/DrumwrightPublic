# DRUMWRIGHT

A drum rhythm game for Windows designed to teach you proper drumming technique. Supports a MIDI drum kit (the intended experience), controller, keyboard, or touchscreen.

![test](https://github.com/StevenCranmer/DrumwrightPublic/blob/main/assets/drumwright%20demo%20page.png?raw=true)

![Test](https://github.com/StevenCranmer/DrumwrightPublic/blob/main/assets/drumwright%20demo%20page%202.png)

![test](https://github.com/StevenCranmer/DrumwrightPublic/blob/main/assets/Drumwright_Accidentally_in_Love_Normal_20260409_000950.png?raw=true)

> **Alpha build — v0.1.** Expect rough edges. Bug reports welcome via GitHub Issues.

---

## Download

Grab the installer from the [Releases](../../releases) page.

Requires Windows 10 or later.

---

## Songs

Drumwright uses Clone Hero-compatible song folders. If you already have a Clone Hero library, point Drumwright at it during setup, no duplication required.

Songs are imported on first load. Drumwright writes a small `.dcht` file into each song folder alongside the existing audio; everything else stays untouched.

**I don't think this breaks Clone Hero, as all it does is add a ".dcht" chart file and optionally a "preview.ogg" audio file. Please let me know if it causes issue.**

---

## Setup

1. Run the installer
2. Launch Drumwright — the setup wizard will open automatically
3. Choose your input method and bind your controls
4. Point the game at your songs folder
5. Run audio calibration so hit timing lines up with your hardware

Library loading will take a long time on your first launch while it caches your library and will be substantially faster on subsequent launches.

---

## Input

| Method | Notes |
|---|---|
| MIDI drum kit | Any standard e-kit; map pads to lanes in settings |
| Controller | Xbox / PlayStation / generic gamepad |
| Keyboard | Fully rebindable |
| Touchscreen | Tap lanes on screen |

---

## Game Modes

**Gamepad** - 4 lanes. Designed for gamepad and playtesting.

**Normal** — 5 lanes. Kick, snare, and three toms. Good starting point for learning the drums.

**Pro** — 8 lanes. Adds the hi-hat, ride cymbal and snare cymbal. Functionally equivalent to Rock Band Pro Drums.

**Authentic** — 8 lanes. Full chart including ghost notes, rimshots, foot splashes, and hi-hat modifiers (open/closed notes). As close to actually playing the song as I can manage.

Higher modes earn more XP. You can switch mode at any time between songs.

---

## Features

- Dynamic Difficulty — notes adapt per-section based on your accuracy history
- Practice mode — loop any section, adjustable difficulty band
- Calibration — separate audio and display offset, built-in tap calibration tool
- XP & levelling — persistent across sessions with one-time accuracy bonuses
- Playlists and favourites
- Song search, sort, and filter

---

## Known Issues / Limitations

- Windows only
- Song import requires `batch_convert.exe` to be present alongside `drumwright.exe`
- Windows Defender may flag `batch_convert.exe` on first run — this is a false positive; allow it through if prompted
- Some Clone Hero charts with non-standard stems may not import correctly

---

## Credits

Built with [Godot Engine](https://godotengine.org).
