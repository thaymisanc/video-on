# Fubo CTV prototypes

Interactive prototype of the live-first CTV launch, with voice and the in-game offer. Open `index.html` in Chrome (or visit the GitHub Pages link). Keyboard only.

## Keys

| Key | What it does |
| --- | --- |
| Arrow keys | Move focus. Left and Right change channel when the controls are hidden. Up shows the peek, and Up again opens the card browse. |
| Enter / OK | Select. Shows the player controls on clean video. |
| Backspace, Delete or Esc | Back. |
| Hold **M** | Real microphone (Chrome asks for permission). Try: "What's that latest Tom Cruise movie where he's an old man millionaire?" |
| **D** | Mic demo. Types the question for you and opens the answer card, no microphone needed. |
| **N** | Shows the in-game offer card. |

Videos are 8-second loops and play on the focused card after 1 second.

## Original clips

`video assets/originals/*.mov` are the full-quality source clips (about 720MB). They are stored with Git LFS, so run `git lfs install` once before cloning. The prototype itself only plays the small `.mp4` loops in `video assets`.

## Notes

- Everything loads from relative paths, so keep `index.html`, `image assets`, `video assets` and `font` together.
- Contains Fubo artwork and third-party logos and posters. Keep the repo private.
- Prototype content only. Scores, offers and titles are placeholders.
