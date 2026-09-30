# Zhengning Xu — Academic Homepage

A static English academic homepage with two layouts. The traditional academic version is at `/`; the earlier visual version is at `/visual/`. Each version has separate About, Research, Highlights, and Contact pages, with links to switch between matching pages. Open `index.html` directly in a browser, or run `python3 -m http.server 8000` inside this directory and visit `http://localhost:8000`.

## GitHub Pages

This directory is the root of the GitHub Pages user repository `OwenxuSH/OwenxuSH.github.io`. The public site is `https://owenxush.github.io/`, published from the `main` branch root.

The site intentionally contains no local project manuscripts or PDFs. The source materials in `../resources/` are for drafting only, and are not needed by the deployed site.

## Updating content

- Edit the academic version in the root HTML files and `styles.css`.
- Edit the visual version in `visual/`. It shares images with the root version through `../assets/` paths.
- Keep factual updates, especially publication status, in sync across both versions.
- Before publishing, verify any manuscript and acceptance status against the latest version from the authors or venue.
