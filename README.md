# Swiss Design — Student Project (International Style)

**Author:** Your Name
**Repo:** https://github.com/YOUR_USERNAME/swiss_design_lineage_vibecoding
**Deployed site:** https://YOUR_USERNAME.github.io/swiss_design_lineage_vibecoding/  (update after deployment)

## Project overview
This site documents the Swiss / International Typographic Style (history, examples) and demonstrates Swiss principles in layout and typography across the site.

## Pages
- `index.html` — overview and links
- `history.html` — timeline & sources
- `examples.html` — gallery with placeholders (replace with real images and credit lines)
- `demo.html` — editorial/grid demo showing Swiss layout principles

## How to run locally
```bash
git clone https://github.com/YOUR_USERNAME/swiss_design_lineage_vibecoding.git
cd swiss_design_lineage_vibecoding
# open index.html in your browser, or serve with a static server:
# python -m http.server 8000
```

## Replacing placeholders with real images
1. Find public-domain or CC-licensed Bauhaus/Swiss images (Wikimedia Commons, museum collections).
2. Save images to `images/` (e.g., `images/muller-brockmann-poster.jpg`).
3. Edit `examples.html`: replace the `<svg>...</svg>` block with
```html
<img src="images/muller-brockmann-poster.jpg" alt="Poster by Muller-Brockmann, 1954">
```
4. Update the `<figcaption>` to include title, designer, year and license/source.

## Deploy to GitHub Pages (step-by-step)
1. Create a new repo on GitHub named `swiss_design_lineage_vibecoding` (or the instructor-required name). Do NOT initialize with README (you already have one locally).
2. In your terminal:
```bash
git init
git add .
git commit -m "Initial Swiss design project"
git branch -M main
git remote add origin git@github.com:YOUR_USERNAME/swiss_design_lineage_vibecoding.git
git push -u origin main
```
3. On GitHub, go to the repository → Settings → Pages. Set the source to `main` branch and root `/` (or select `gh-pages` branch if you use that).
4. After a minute, the site will be available at `https://YOUR_USERNAME.github.io/swiss_design_lineage_vibecoding/`. Paste that URL into your README and submit to your instructor.

## Notes for submission
- Replace "Your Name" and `YOUR_USERNAME` with your real name and GitHub username.
- Add at least 6 real example images with captions/attributions before final submission.
- Check accessibility: alt text, heading order, contrast.
