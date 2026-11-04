# NEXUS FRET TRACE

Live guitar line to tablature. Real-time pitch detection, fretboard monitors, and continuity-aware tabs.

## Open it

- **The app:** [index.html](index.html)
- **The live test notebook:** [test-notebook.html](test-notebook.html)

## What it does

- Mic or file input, with autocorrelation pitch detection
- Capture a clear single-note line, quantize to an 8th-note grid
- Editable timeline: click to select, drag to move in time, wheel to change pitch, right-click to delete
- Playability scorer with LOCK POS, transpose, capo, and Open G / Drop D / DADGAD tunings
- Loop and speed playback (1.0x / 0.75x / 0.5x), MIDI download, and copyable ASCII tab with bars
- Bend and slide detection: a note ending in `s` was slid into, a note ending in `b` was bent, with a Bends line under the tab
- Built-in tests that need no file download: TEST and B/S TEST

## Try it without a guitar

1. Open the app.
2. Tap **TEST** — it should capture E2, A2, D3, G3, B3, E4, G3, E2.
3. Tap **B/S TEST** — it should capture A2, then D3 slid into, then D3 bent about 3 semitones and back.
4. Use the test notebook to record what actually happened for each step.

## Honest limits

Monophonic only, best on clear leads and solos. No polyphony yet, and no full piano-roll drag editor yet. A real chord needs more than one pitch at once, so the live display shows the note's root, not a detected chord.

## Files

- `index.html` — the app
- `test-notebook.html` — the visual live test notebook
- `icon-180.png`, `icon-192.png`, `icon-512.png` — home-screen icons
