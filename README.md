# Portfolio

Roblox developer portfolio, a single self-contained page.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The whole site. Images and video are embedded as data URIs, so it works from any static host with no other files. |
| `assets/` | Original media, kept for future edits (not loaded by the page). |
| `serve.js` | Local preview server, no dependencies. |

## Run locally

```
node serve.js
```

Then open http://localhost:5173

## Deploy

Any static host works, since the site is one file.

- **GitHub Pages**: Settings, Pages, Deploy from branch, `main` / root.
- **Cloudflare Pages / Netlify / Vercel**: connect the repo, no build command, output directory is the repo root.

## Editing

`index.html` is generated with the media inlined, so the base64 blocks near the top are the hero
image and the three game icons, and there is one more inside the framework section for the video.
Edit the markup and CSS around them, or re-inline a new file from `assets/`.
