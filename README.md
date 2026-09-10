# Parking NS — website

Static site, no build step. Deploy on GitHub Pages:

1. Commit this `docs/` folder to the default branch.
2. Repo → Settings → Pages → Source: **Deploy from a branch**, Branch: `main`, Folder: `/docs`.
3. The site appears at `https://<user>.github.io/<repo>/`.

Notes
- All paths are relative, so it works from a repo subpath as well as a custom domain.
- Update the `<link rel="canonical">` URL in `index.html` once you know the final address.
- `.nojekyll` stops Jekyll from touching the files.
- Fonts load from Google Fonts; everything else (`styles.css`, `assets/`) is local.
