# Personal website — Xunmei (May) Liu

Static site for GitHub Pages.

## Deploy

1. Create a GitHub repo named `<your-github-username>.github.io` (e.g. `xunmeiliu.github.io`).
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial personal website"
   git branch -M main
   git remote add origin git@github.com:<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```
3. On GitHub: Settings → Pages → Source: `main` branch. The site goes live at `https://<your-github-username>.github.io` within a few minutes.

## TODO before publishing

- Replace `#` placeholder links in `index.html`: Google Scholar, GitHub, LinkedIn, VFIG ArXiv/project page, eKichabi paper link.
- Replace the two publication placeholder thumbnails with real figures (drop images into `assets/img/` and swap the `.pub-thumb.placeholder` divs for `<img class="pub-thumb" src="...">`).
- Review the intro paragraphs and news items.
