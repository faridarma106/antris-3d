# Antris Management Solutions — 3D Concept Site

An original, 3D-animated reimagining of the Antris Management Solutions website,
built with [Three.js](https://threejs.org/). Single self-contained page — no build step.

> This is a separate concept site. It does **not** touch the live site at antris.com.sg.

## Project files

```
antris-3d/
├── index.html        ← the whole site (HTML + CSS + 3D code)
├── netlify.toml       ← Netlify hosting config
├── assets/            ← logo + photos
│   ├── logo.png
│   ├── hero.jpg
│   ├── about.jpg      (currently unused — spare photo)
│   ├── services.jpg
│   └── standards.jpg
└── README.md
```

## View it locally

Just **double-click `index.html`** — it opens in your browser. (Needs an internet
connection: it loads the Three.js library and the Earth texture from a CDN.)

## Deploy it (pick one — both are free)

### Option A · Netlify Drop (easiest, ~1 minute)
1. Go to **https://app.netlify.com/drop**
2. Drag the whole **`antris-3d` folder** onto the page.
3. Netlify gives you a live URL instantly (e.g. `your-name.netlify.app`).
4. To use a custom domain later: Netlify dashboard → *Domain settings*.

### Option B · GitHub Pages
1. Create a new GitHub repository and upload the contents of this folder.
2. Repo → **Settings → Pages**.
3. Under *Build and deployment*, set **Source: Deploy from a branch**,
   **Branch: `main`**, folder **`/ (root)`**, then **Save**.
4. Your site appears at `https://<username>.github.io/<repo>/` after a minute.

## Notes
- All design and copy are original. The photos and logo are Antris's own assets.
- Replace any photo by dropping a new image into `assets/` with the same filename.
