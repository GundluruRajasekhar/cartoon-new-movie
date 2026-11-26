# Pip and the Moon Kite

A 40-second cartoon movie made of four files. Everything is drawn with SVG and animated with plain JavaScript.

## Files
| File | Purpose |
|---|---|
| `index.html` | The movie: artwork, animation timeline, and player controls |
| `requirements.md` | What the movie must do |
| `README.md` | This guide |
| `tasks.md` | Build checklist and ideas for next versions |

## Run it
1. Put the four files in one folder.
2. Open `index.html` in Chrome, Edge, Firefox, or Safari.
3. Press **Start movie** (or **Start**). Press **Stop** at any time to end it and return to the title screen.
4. Turn up your volume: narration and soft music play with the movie.

## Controls
- **Start** plays the movie from the beginning; **Stop** ends it and resets.
- **Narration voice** reads each caption aloud using your browser's voice.
- **Music** plays a soft lullaby made with Web Audio.
- The full narration script is listed under the captions.

## Deploy
Upload the folder to GitHub and turn on GitHub Pages, or drag it into Vercel or Netlify. No build command is needed.

## Change the story
- Captions and their start times: the `CAPS` list in `index.html`.
- Sky and hill colours over time: `SKY` and `HILL`.
- Movement of Pip and the kite: the `frame()` function.
- Movie length: the `D` constant (also update the slider `max`).

## Story
Pip builds his biggest kite, the wind lifts him to the Moon, and the Moon gives him a star.
