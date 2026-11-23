# Futurebound Books

Official author and book website for Futurebound Books, initially featuring *Meridian* by Steven Earl Sims.

## Local preview

This is a static site with no build step. From the repository root, run:

```sh
python -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages deployment

The site is designed for GitHub Pages at `https://stevesims2.github.io/futurebound-books/` and uses relative paths for its local assets.

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Push updates to `main`; GitHub Pages will publish them automatically.

## Site files

- `index.html` — homepage, metadata, and page content
- `assets/styles.css` — responsive visual design
- `assets/meridian-cover.jpg` — Meridian eBook cover
- `assets/steven-earl-sims.jpg` — author photograph

The page does not include analytics, tracking scripts, or visitor data collection. The video loads from YouTube's privacy-enhanced embed domain when opened by a visitor.
