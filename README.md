# Values Cards — GitHub Pages (No build needed)

This version runs entirely in the browser using React + Babel from a CDN — so you can host on **GitHub Pages** without running a build.

## How to deploy on GitHub

1. Create a new repo on GitHub (Public).
2. Download and unzip this folder.
3. Drag **all files** (`index.html`, `styles.css`, `cardsData.json`, `scenarios.json`) into your repo via the web UI.
4. (Optional) Replace `cardsData.json` and `scenarios.json` with your full versions.
5. In the repo, go to **Settings → Pages → Build and deployment** and set:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`), and folder: `/root`
6. Save. Your site will be live at the Pages URL shown.

### Using your team JSON
Click **Choose team JSON** on the page and upload the exported team from Phase 1 (must contain 5 heroes).

> Note: Because this version uses CDNs, it requires an internet connection to load React/Babel.
