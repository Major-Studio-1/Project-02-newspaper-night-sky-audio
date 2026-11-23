# Newspaper Night Sky · radio voices

The recorded voices of the radio on [Newspaper Night Sky](https://newspapers.icare.love/): the announcer's lines, every reviewed passage, and the titles of the most widely printed stories. They were made once with the open speech model Kokoro (Apache 2.0) by `pipeline/audio_render.py` in the [main repository](https://github.com/Major-Studio-1/Project-02-newspaper-night-sky). Visitors only play these files: no speech is made on a server.

They live in a repository of their own so that the main site stays under GitHub Pages' size limit of 1 GB. The radio reads them from https://major-studio-1.github.io/Project-02-newspaper-night-sky-audio/ (a copy of the site that carries `audio/` beside its pages, such as an offline exhibition, plays its own).

| Path | What it is |
|---|---|
| `audio/index.json` | Every clip as [pack, first byte, end byte, seconds, tier] (tier 0 the announcer, 1 a reviewed passage, 2 a story's title), and aliases from a reviewed story to its first printing |
| `audio/a.mp3`, `audio/r/`, `audio/t/` | The packs: the announcer, one pack per reviewed story, one pack of titles per year. Each clip is a whole MP3 inside its pack, so a byte range of a pack plays on its own |

The voices are modern and synthetic. They read the machine transcriptions as they are, misreadings included; the reviewed passages' notes on the site say where a transcription differs from the printed page.
