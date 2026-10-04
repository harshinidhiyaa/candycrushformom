# Happy Birthday Amma - Candy Game

Add your pictures to the `images/` folder:

- `banner-amma.jpg` : photo in the top banner
- `win-photo.jpg`   : photo shown in the win popup
- `candy1.png` ... `candy6.png` : the 6 candy pictures (square, transparent PNG works best)

Missing pictures fall back to emoji, so the game always works.
- `cake-bomb.png` : optional picture for the Cake Bomb (otherwise a cake emoji)

Optional music: put a song at `audio/music.mp3` and it plays instead of the built-in tune.

If your pictures are transparent cut-outs (not photos), change `--fit: cover` to `--fit: contain` in the CSS.
