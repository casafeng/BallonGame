# The Balloon (BART)

A standalone Balloon Analogue Risk Task: 3 practice balloons, then 30 scored balloons (blue, yellow, orange in random order). The score is shown at the end. **Nothing is saved**, so each game is independent and past scores are not kept.

## Put it online with GitHub Pages

1. Create a new repository on GitHub and upload `index.html` (and this README).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and click **Save**.
4. After a minute the game is live at `https://<your-username>.github.io/<repo-name>/`.

GitHub Pages on a private repo requires a paid GitHub plan; on a free account the repo must be public.

## Changing the game

Open `index.html` and edit the `CONFIG` block near the bottom:

- `pointsPerPump`: points per pump (default 5)
- `conditions`: colours, burst range (`maxPumps`) and how many balloons of each
- `practice`: which practice balloons come first
- `allowReplay`: show or hide the "Play again" button

## Fonts

The page falls back to system fonts. To use GM Seagal, add the font files to the repo and paste their `@font-face` block at the top of the second `<style>` tag.
