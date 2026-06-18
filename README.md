[README.md](https://github.com/user-attachments/files/29105751/README.md)
# Guiselt Thaiz — Portfolio Website

Single-page portfolio site for artist Guiselt Thaiz.

## Structure

```
index.html      Main site (HTML/CSS/JS, single file)
fonts/           Self-hosted Cormorant Garamond font files (woff2)
images/          All site imagery (homepage, work series, contact, info)
```

## Local development

This is a static site with no build step. Just open `index.html` in a
browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`.
4. Choose the `main` branch and `/ (root)` folder, then **Save**.
5. GitHub will publish the site at `https://<username>.github.io/<repo-name>/`
   within a minute or two.

## Notes

- Fonts are self-hosted in `/fonts` so the site works fully offline and
  doesn't depend on Google Fonts at runtime.
- All image paths in `index.html` are relative to the `images/` folder,
  so the folder must sit alongside `index.html` exactly as structured here.
