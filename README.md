# Airsite — Web Designer & UI/UX Developer

Bilingual (English / Arabic) portfolio. The whole site is one static file, `index.html`
(HTML, CSS, JS, images and the example sites are embedded). No build step.

## Deploy (important)
Unzip, then upload the FILES INSIDE the folder so that `index.html` sits at the top level
of your repo (next to `vercel.json`). If `index.html` ends up inside a sub-folder, the site
shows a 404.

### GitHub + Vercel
1. Create a repo, upload all files from this zip (not a folder that contains them).
2. In Vercel: Add New Project, import the repo. Framework Preset: Other. Build command: empty. Output directory: empty.

### GitHub Pages
Settings, Pages, Source: GitHub Actions. Push to `main`; the workflow publishes the site.

### Netlify
Drag the unzipped folder onto app.netlify.com/drop.

## Notes
- `index.html` is about 16 MB, so the first load is slow on weak connections.
