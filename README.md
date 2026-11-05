# FirstClub Creator Circle

Landing page for the FirstClub Creators Circle programme — *Find it. Film it. Get rewarded.*

`index.html` is a single self-contained file: fonts, icons, images and the Platter design-system code are all embedded, so it runs with no build step and works offline. It adapts to desktop, tablet and mobile widths.

## Run locally
Open `index.html` in any modern browser (Chrome, Edge, Safari, Firefox).

## Publish on GitHub Pages
1. Push this folder to a new repository on the `main` branch.
2. In the repo, go to **Settings → Pages** and set **Source** to **GitHub Actions**.
3. The included workflow (`.github/workflows/pages.yml`) deploys on every push to `main`.
   The site appears at `https://<your-username>.github.io/<repo-name>/`.

## Push from the command line
```bash
cd creator-circle
git remote add origin https://github.com/<your-username>/creator-circle.git
git push -u origin main
```

## Editing
The source lives in the FirstClub website project in Claude Design (page: *FirstClub Creator Circle Responsive*). Make changes there and re-export `index.html`.

Notes: creator photos in the "Circle today" orbit and avatar rows load from Google Drive links, so they need an internet connection.
