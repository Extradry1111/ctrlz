# $CTRLZ

Meme coin site for CTRLZ, a four winged dragon drawn in MS Paint. Static site, no build step, ready for GitHub Pages.

## Run locally
Just open `index.html` in a browser, or serve it:
```
python3 -m http.server 8000
```
then visit http://localhost:8000

## Deploy on GitHub Pages
1. Create a new repo on GitHub (e.g. `ctrlz-site`), don't initialize it with a README.
2. In this folder, run:
```
git remote add origin https://github.com/YOUR_USERNAME/ctrlz-site.git
git branch -M main
git push -u origin main
```
3. On GitHub: repo -> Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main`, folder `/ (root)` -> Save.
4. Your site goes live at `https://YOUR_USERNAME.github.io/ctrlz-site/` in a minute or two.

## Files
- `index.html` — the whole site
- `assets/ctrlz-flying.png` — transparent dragon, bounces around the screen
- `assets/ctrlz-livingroom.jpg` — original living room drawing, shown mid page
