# melodyteng.github.io

The live site is currently a placeholder (just "Melody Teng" centered on the page).

## Restoring the full site

The full site as of 2026-11-13 is saved on GitHub in two places, both pointing to commit `c070ec7`:

- Branch: `archive/full-site-2026-11-13`
- Tag: `full-site-2026-11-13`

To bring it back, run from the repo root:

```sh
git checkout main
git pull
git checkout full-site-2026-11-13 -- index.html
git commit -m "Restore full site"
git push origin main
```

GitHub Pages republishes melodyteng.com within a minute or two. Only `index.html` was replaced when the site was taken down; every other file is still on `main`.

Without a terminal: on GitHub, switch to the `archive/full-site-2026-11-13` branch, open `index.html`, copy its contents, then edit `index.html` on `main` and paste them in.
