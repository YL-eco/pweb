
# Academic Site Skeleton (GitHub Pages + Jekyll)

## Quick Start
1. Create a repo named `yourusername.github.io` on GitHub.
2. Download this folder and **push** its contents to that repo.
3. Go to the repo **Settings → Pages** and ensure GitHub Pages is enabled (it usually is by default).
4. Edit `_config.yml` with your name, description, and URLs.
5. Replace `assets/img/profile.jpg` with your headshot.
6. Add your PDFs to `assets/papers/` and your CV to `assets/cv/your_name_cv.pdf`.
7. Edit `index.md`, `bio.md`, `research.md`, `cv.md`, `code.md` with your content.

## Local Preview (optional)
If you have Ruby/Jekyll installed:
```bash
bundle init
bundle add jekyll
bundle exec jekyll serve
```
Then open http://localhost:4000

## Notes
- This uses the built-in `jekyll-theme-minimal`. You can switch to the remote theme version by uncommenting lines in `_config.yml`.
- Navigation links are plain HTML in each page for simplicity.
- Keep PDFs small (< 1 MB) and use descriptive filenames.
