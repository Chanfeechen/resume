# Peijie Chen — personal website

A personal site built with Hugo and the MIT-licensed [Terminal theme](https://github.com/panr/hugo-theme-terminal) by panr. The theme is vendored under `themes/terminal/` so builds do not depend on a moving upstream branch.

## Local preview

Use Hugo Extended 0.147.9:

```sh
hugo server
```

Open http://localhost:1313/. Build a production copy with `hugo --minify`.

## Editing

- `hugo.toml`: site URL, navigation, and theme settings.
- `personal-content/_index.md`: homepage introduction.
- `personal-content/project/`: selected projects and their images.
- `personal-content/about/`: background and contact links.
- `personal-content/notes/`: future writing; no template posts are published.
- `static/style.css`: small customizations to Terminal.
- `static/uploads/`: the single ML engineering resume (`Peijie_Chen_Resume.pdf`). Refresh it from the jobs workspace after resume changes; verify master PDF/source hashes before copying.

Original Academic content remains under `content/`; its configuration and README are preserved in `legacy/`. Hugo publishes only `personal-content/`.

## Publishing

Only pushes to `main` trigger `.github/workflows/publish.yaml`. The `redesign/terminal` branch is a review version and does not replace the live website. The workflow uses GitHub Pages settings for the production base URL. Keep the Pages custom domain set to `peijiechen.fyi` and enable Enforce HTTPS.
