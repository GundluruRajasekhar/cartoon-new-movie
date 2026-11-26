# Requirements - Pip and the Moon Kite

## Goal
A short cartoon movie that plays in any modern browser from a single `index.html`, with no build step, server, or API key.

## Story
Pip, a fox cub, builds a giant kite. The wind carries him up to the Moon, who gives him a star for the kite's tail and tells him to come back tomorrow.

## Functional requirements
- FR1: Start and Stop buttons run the 40-second movie; Stop resets to the title screen.
- FR2: Four scenes: sunset hill, the run, the flight, the Moon meeting and return.
- FR3: Captions for every scene, shown below the screen.
- FR4: Spoken narration script (on by default) using the browser's speech engine, plus soft background music; each can be switched off.
- FR5: Sky and hills change colour from sunset to night; stars fade in.
- FR6: An end card ("The End") closes the movie.

## Non-functional requirements
- Works offline (the font is optional and falls back to system fonts).
- Responsive from phone to desktop, 16:9 screen.
- Keyboard accessible controls with visible focus; captions use `aria-live`.
- All artwork is vector (SVG), drawn in code. No external images, audio, or video files.

## Characters and look
- Pip: orange fox cub with a white-tipped tail.
- Moon: cream, with a sleepy face that appears in scene 4.
- Kite: teal diamond with a bow tail.
- Palette: sunset orange to indigo night, cream, teal.

## Out of scope (version 1)
Background music, voice actors, exporting to MP4.
