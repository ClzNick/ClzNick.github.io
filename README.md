# Portfolio

Roblox developer portfolio, served at https://nicolasrbx.com.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The whole page: markup, CSS and a tiny scroll-reveal script. |
| `assets/banner.png` | Hero banner. |
| `assets/thumb-*.webp` | Game thumbnails (16:9, from the Roblox game pages). |
| `assets/combat-360.mp4`, `combat-poster.jpg` | Combat framework video and its poster. |
| `CNAME` | Custom domain for GitHub Pages. |
| `serve.js` | Local preview server, no dependencies. |

## Run locally

```
node serve.js
```

Then open http://localhost:5173

## Editing

Everything is plain HTML in `index.html`.

- **Hero stats**: the two `.stat` blocks (`11K`, `13M+`).
- **Games**: one `<article class="game">` per game. Change the thumbnail, title, visits and Play link.
  To add a game, copy an article and drop a new 16:9 image in `assets/`.
- **Colors**: the variables at the top of the `<style>` block (`--cyan`, `--pink`, `--bg`...).

## Deploy

Push to `main`. GitHub Pages serves the repo root.
