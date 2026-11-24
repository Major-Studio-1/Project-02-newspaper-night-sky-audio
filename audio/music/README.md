# The music's recordings

**Played by:** the site's music (`music.js`), in its Piano and Concerto sounds. Wood makes its notes in the browser and needs no file here.

**Where the site reads them:** this folder beside the pages first (a local copy, an offline exhibition). Otherwise it reads the audio site, which serves `audio/` as its root, so the address is `…/Project-02-newspaper-night-sky-audio/music/`. `index.json` lists the files and their credits.

**Contents:**

- `piano/`: 32 notes of the **Salamander Grand Piano**, a Yamaha C5 recorded by Alexander Holm.
  - 16 pitches every minor third from A1 to F♯5, each at two of its 16 loudness levels: `v5` soft, for the left hand; `v9` fuller, for the right.
  - From the MP3 edition made for the web by Tone.js's piano (`tambien.github.io/Piano/audio/`).
  - **Licence: [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/). The site must credit it:** "Piano: Salamander Grand Piano by Alexander Holm (CC BY 3.0)".
- `flute/` and `clarinet/`: six long notes each from the **VSCO 2 Community Edition** orchestra (Versilian Studios).
  - Flute: `Woodwinds/Flute/susvib`, with vibrato, C4 to A5.
  - Clarinet: `Woodwinds/Clarinet/susLong`, a B♭ clarinet, A♯3 to F5.
  - **Licence: [CC0 1.0](https://github.com/sgossner/VSCO-2-CE/blob/master/LICENSE), public domain.** No credit is required; the site names it all the same.
  - The original files name their octaves one lower than scientific pitch. These are renamed by their measured, sounding pitch (within 6 cents), cut from first sound to last, and saved as 128 kbps MP3.

How they were chosen and measured is in the project's `docs/notes/2026-11-23-music-discovery.md` (not part of this repository).
