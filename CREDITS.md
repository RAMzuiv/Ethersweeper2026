# Credits

## Original credits

Design and Programming by MRPW
Music by MRPW (including game over motif)

Sound effects:
Many effects are from the Pythonista default libraries
"success 1" by Leszek_Szary — freesound.org/s/171671 (CC0)
"decide.mp3" by fumiya112 — freesound.org/s/144319 (CC0)
ivan_luzan-next-level.mp3 is from https://pixabay.com/sound-effects/film-special-effects-next-level-160613/

Visual assets:
Many assets are from Pythonista libraries

---

## Additions in this Swift / WebAssembly / three.js version

*(Written by Claude, which is credited below. MRPW may ask for this section to be rewritten.)*

The game design, the music and the game-over motif are MRPW's. This web version follows MRPW's Python design.

- **Swift port, 3D rendering and web build:** Claude (Anthropic), working to MRPW's direction. This covers the game
  logic ported to Swift, the three.js scene, the touch and pointer handling, and the single-file web build.
- **Swallow, the Swift-to-WebAssembly compiler** that this game is compiled with: written by Claude (Anthropic), working
  to MRPW's direction.
- **Artwork:** the 3D tiles, the minefield-marker flag and the eight-spoke mine models and textures were drawn in code by
  Claude. They replace the Pythonista icon assets used in the original.
- **Sound effects:** the effects that the original takes from Pythonista's default libraries are re-created here by
  synthesis in Web Audio (`audio.js`), written by Claude. They are new sounds, not copies of the Pythonista files. The
  three sound files named above ("success 1", "decide.mp3" and "next-level") are the original files, used unchanged and
  played at the volumes and pitches the original uses.
- **Voice lines:** the five spoken lines ("Congratulations", "You win", "Objective achieved", "Mission completed" and "Wrong") are
  from the Voiceover Pack #1 by Kenney Vleugels (Kenney.nl), CC0, with voices by Giselle (female) and Jeffrey M. Smith (male).
  They are the same lines as the Pythonista voices the original uses. The pack's licence and credits are kept in
  `audio/voices-LICENSE.txt`; the files were converted to AAC and otherwise used unchanged.

### Third-party components embedded in the web build

- **three.js**: MIT License, © three.js authors. https://threejs.org
- **Lora** (title and finale screens): SIL Open Font License 1.1, © The Lora Project Authors. https://github.com/cyrealtype/Lora-Cyrillic
