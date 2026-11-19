# Robo Bass

A bass sequencer with synthesized sounds, sibling of ROBO/SOLO and ROBO/BEAT for Robo Galaktika. Make a pattern once, then press a key (C, D, Am, G…) and the pattern follows that key. Runs in a phone browser, no app store install needed.

## How it works

- **Patterns are written as scale degrees,** not fixed notes: 1, 2, 3, 4, 5, 6, b7, octave (8va), and the fifth below (5↓).
- **Two rows of key buttons:** top row major, bottom row minor. In minor, the 3 and 6 drop a semitone.
- **Press a key to play.** If stopped, the pattern starts playing in that key. If playing, it moves to the new key from the next note, like a bassist following the chord changes. Press STOP to stop.

## Features

- **16-step grid.** Tap a cell: hit → accent → clear. The **HOLD** row sustains a note into the next step.
- **9 synthesized sounds:**
  - Close to a real bass: Finger Bass and Slap Bass (modal synthesis: each string partial is modelled with pickup position, string stiffness, pitch glide on the attack and an amp/cabinet chain), plus Pick Bass and Fretless.
  - 80s synth bass: Moog Saw, Juno Square, FM Bass DX7, Resonant Acid, Sub Sine.
- **10 preset patterns:** Synth Pop 8ths, New Wave Pick, Disco Octaves, Walking Blues, 80s Funk, 80s FM, Ballad Fretless, Reggae, Acid, Empty.
- **Tempo** with tap tempo, **click metronome**, **swing**, **note length**, and **octave −1 to +2**.
- **PATTERN / KEYS views.** On tall enough screens, both show at once.
- **Auto-save** on the device, with an Undo button. Keyboard: space to play/stop.

Phone speakers can't reproduce low bass notes clearly. Use headphones or an amp, or raise the octave while practising.

## Put it online with GitHub Pages

1. Create a new GitHub repo, e.g. `robo-bass`.
2. Upload all files in this folder (**Add file → Upload files**).
3. Open **Settings → Pages**, set *Source* to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Wait 1–2 minutes. The app will be at `https://<username>.github.io/robo-bass/`.

On your phone: open that address in Chrome or Safari and choose **Add to Home Screen**.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Data for "Add to Home Screen" |
| `icon-192.png`, `icon-512.png` | App icons |
| `.nojekyll` | Makes GitHub Pages serve the files as they are |
