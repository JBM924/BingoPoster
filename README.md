# London Underground Bingo (Shareable)

A single-file web app to play OOH (Out-of-home) bingo around the London Underground and National Rail.

## Features
- London Underground–inspired UI (roundel colors, blue borders, red header)
- Search, shuffle, mark tiles ✓
- Attach a photo per station tile as proof
- Shareable state via URL hash (order + marks)
- Local persistence (keeps your progress in the browser)
- Print-friendly (5 columns when printing)

## Deploy (GitHub Pages)
1. Create a new GitHub repository (public).
2. Upload `index.html` to the repo root.
3. In **Settings → Pages**: set **Source** to **Deploy from a branch**, pick **main** and **/** (root).
4. After it builds, open: `https://YOUR_USERNAME.github.io/REPO_NAME/index.html`

Use the **Share Board** button to copy a link which encodes the current board in the URL hash so other players see the same state.

## Deploy (Netlify)
- Drag & drop the folder into the **Sites** area on Netlify.
