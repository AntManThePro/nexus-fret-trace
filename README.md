# NEXUS FRET TRACE

Live guitar line to tablature. Real-time pitch detection, fretboard monitors, and continuity-aware tabs. Built by DoubleA (@AntManThePro). Not perfect, just real.

**Live:** https://antmanthepro.github.io/nexus-fret-trace/

## How to use it

1. Open the live site, tap **MIC**, and play a clear single-note line — one note at a time.
2. Hit **REC** to capture, then **QUANTIZE** to snap it to the grid.
3. Edit on the timeline: click to select, drag to move in time, drag up/down to change pitch, DEL to delete.
4. **LOCK POS** to hold a position, transpose or capo as needed, then export MIDI or copyable ASCII tab.

No guitar handy? Tap **TEST** — it should capture E2, A2, D3, G3, B3, E4, G3, E2. Tap **B/S TEST** — it should capture A2, then D3 slid into, then D3 bent about 3 semitones and back.

## What it does

- Mic or file input, with autocorrelation pitch detection
- Capture a clear single-note line, quantize to an 8th-note grid
- Editable timeline: click to select, drag to move in time, wheel to change pitch, right-click to delete
- Playability scorer with LOCK POS, transpose, capo, and Open G / Drop D / DADGAD tunings
- Loop and speed playback (1.0x / 0.75x / 0.5x), MIDI download, and copyable ASCII tab with bars
- Bend and slide detection: a note ending in `s` was slid into, a note ending in `b` was bent, with a Bends line under the tab
- Built-in tests that need no file download: TEST and B/S TEST
- Full 22-fret board — detection allows frets 0–22, and the board draws all 22

## Honest limits

Monophonic only, best on clear leads and solos. No polyphony yet, and no full piano-roll drag editor yet. A real chord needs more than one pitch at once, so the live display shows the note's root, not a detected chord.

## Links

- Live site: https://antmanthepro.github.io/nexus-fret-trace/
- Test notebook: https://antmanthepro.github.io/nexus-fret-trace/test-notebook.html
- NEXUS hub: https://nexus-world-hub.netlify.app/
- Repo: https://github.com/AntManThePro/nexus-fret-trace

## Files

- `index.html` — the app
- `test-notebook.html` — the visual live test notebook
- `icons/` — home-screen icon set (favicon.ico, favicon-192.png, favicon-512.png, apple-touch-icon.png)
