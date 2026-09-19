# Museum After Hours

**Museum After Hours** is a browser-based educational serious game about museum curation, interpretation, evidence, and multiple perspectives. It is designed for secondary-school students and first-year university students.

The player takes the role of a junior curator preparing an exhibition around six real museum objects. During the day, they inspect evidence and make curatorial decisions. After the museum closes, the objects begin to speak back to those decisions.

## What the game explores

- evidence-based interpretation
- how labels and categories shape meaning
- accessibility and clarity for visitors
- multiple perspectives and source communities
- curatorial coherence and trade-offs
- the difference between identifying an object and interpreting it

## Objects in the prototype

The prototype includes six objects from the collection of The Metropolitan Museum of Art:

- Large Kneeling Statue of Hatshepsut
- Terracotta neck-amphora of Panathenaic shape
- Planispheric Astrolabe
- Byzantine Reliquary in the Shape of a Sarcophagus
- Mangaaka Power Figure (Nkisi N'Kondi)
- Hokusai's *The Great Wave*

## Controls

The game is designed for a controller but also supports keyboard input.

- **D-pad / Arrow keys** — navigate
- **A / Enter** — select or continue
- **B / Esc** — back
- **X** — replay the current exhibit voice
- **Y** — show a hint

Subtitles remain visible during all voiced sequences.

## Project structure

```text
index.html
assets/
  exhibits/
    hatshepsut.jpg
    amphora.jpg
    astrolabe.jpg
    reliquary.jpg
    mangaaka.jpg
    wave.jpg
  audio/
    hatshepsut_good.mp3
    hatshepsut_weak.mp3
    amphora_good.mp3
    amphora_weak.mp3
    astrolabe_good.mp3
    astrolabe_weak.mp3
    reliquary_good.mp3
    reliquary_weak.mp3
    mangaaka_good.mp3
    mangaaka_weak.mp3
    wave_good.mp3
    wave_weak.mp3
```

No build process or server-side code is required. Open `index.html` directly for local use, or publish the repository through GitHub Pages.

## GitHub Pages

The project can be published directly from the `main` branch and repository root using **Settings → Pages → Deploy from a branch → main / root**.

## Credits and sources

Historical object information is based on records from **The Metropolitan Museum of Art**. The fictional museum staff and the dramatic voices of the exhibits are original narrative elements created for this educational prototype.

Image and audio materials should be used in accordance with their respective source and generation licences.

## Status

Educational prototype for demonstration and playtesting.
