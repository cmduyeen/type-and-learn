# Type & Tell

A cozy, zero-bloat typing workshop in a single HTML file — practice with funny meme decks, chase song lyrics in real time, or outrun the Monday Monster in a 2D Canvas runner game.

**Live Web App:** https://cmduyeen.github.io/type-and-learn/

## Features

- **Funny Decks**: Built-in **Memes & Internet**, **Funny Quotes**, and **Daily Chaos** packs with instant WPM, accuracy, and combo streak tracking.
- **Lyrics Chase (Sing-Along Typing)**:
  - **1-Click Synced Lyrics Search** via [LRCLIB](https://lrclib.net/) (`.lrc` timestamps).
  - **YouTube Mini-Player** (IFrame API) & **Local Audio Player** (`MP3`, `WAV`, `OGG`, `M4A`).
  - Supports **YouTube Transcript** copy-paste, **`.srt`**, **`.vtt`**, **`.lrc`**, and plain multi-line text.
  - **Playback Speed (`1x` / `0.75x` / `0.85x`)** and **`Wait-for-me`** mode (auto-pauses music until you finish typing the current line).
- **Visual Runner Game**: HTML5 Canvas typing race where accurate keystrokes sprint toward the finish flag while typos cost hearts and trigger bonk animations.
- **Retro Web Audio SFX**: Synthesized keystroke & level-up chimes with a mute toggle (no external audio assets).
- **100% Local & Private**: Runs entirely in your browser tab; no accounts, no tracking, no server uploads.

## Run Locally

Because YouTube IFrame embeds require an HTTP origin, serve the folder with any static server:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## License

[MIT](LICENSE) © 2026 [cmduyeen](https://cmduyeen.github.io/)
