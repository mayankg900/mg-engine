# MG Legendarious Engine

A single-file, browser-based auto music editor. Decodes audio, analyzes BPM and key, splits into 4-band DSP stems, applies multiband mastering, and exports studio-grade WAV / MP3 — no backend, no build step.

**© MG — Legendarious Engine. All rights reserved.**

---

## Features

- **Ingest** — local files, drag-and-drop, clipboard paste, or direct audio URL
- **Analysis** — BPM, key, Camelot, energy curve, section segmentation
- **Stem split** — 4-band DSP (vocals / drums / bass / other)
- **Arrangement** — automatic radio edit with downbeat snapping
- **Mastering** — 3-band multiband compression, harmonic exciter, stereo widening, LUFS target, true-peak limiter
- **Export** — 24-bit WAV with RIFF INFO metadata, MP3 320 via WebCodecs
- **VFX** — liquid-gold waveform, particle field, neural point-cloud visualizer

## Presets

Tiger Mode · Clean · Festival · Lo-Fi · Bollywood · Drill · Cinematic · Reel 15s · Reel 30s · Podcast · Karaoke

## Usage

Open `index.html` in any modern browser.

**Important:** Load via `https://` or `http://localhost` — **not** `file://` or `content://`. Opening directly from a file manager breaks audio decoding on Android.

## Keyboard shortcuts

| Key | Action |
|---|---|
| `Space` | Play / pause |
| `←` / `→` | Seek 5 seconds |
| `E` | Export WAV |
| `S` | Solo vocals (toggle) |
| `M` | Toggle auto-duck |
| `Ctrl/Cmd + Z` | Undo |
| `Ctrl/Cmd + Shift + Z` | Redo |
| `Ctrl/Cmd + Enter` | Run pipeline |

## Tech

Web Audio API · Canvas 2D · WebCodecs · vanilla JS · zero dependencies.

## License

MIT — see [LICENSE](LICENSE).
