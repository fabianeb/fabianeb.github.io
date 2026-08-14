# fabianeb.github.io

Personal site of Fabián E. Bustamante — plain static HTML (Bootstrap 5 from CDN),
published to GitHub Pages by `.github/workflows/pages.yml` on every push to `main`.

Live at <https://fabianeb.github.io>.

## Layout

| Path | Contents |
| --- | --- |
| `index.html` | Home — bio, teaching, and random-bits tabs |
| `teaching.html` | Full course history |
| `personal.html`, `academicTree.html`, `borgesyyo.html`, `borgesandi.html` | Secondary pages |
| `404.html` | Shown by GitHub Pages for any URL that does not exist |
| `css/custom.css` | The only stylesheet of our own; Bootstrap comes from the CDN |
| `images/`, `FBustamante.png`, `AquaLab6.png` | Site images |
| `vita/vita.pdf` | Current CV, built from the private `fabianeb/fabianb-site` repo |

## Editing

Edit the HTML/CSS and push to `main`; the site rebuilds in well under a minute.
There is no build step — what is in the repo is what is served.

To refresh the CV, rebuild `vitae/` in `fabianeb/fabianb-site` and copy the
resulting PDF over `vita/vita.pdf` here.

All assets are local and nothing references `users.cs.northwestern.edu/~fabianb`,
so the site is independent of the CS server.

If the site ever moves to a custom domain, update the absolute URLs in
`index.html`'s `og:url`, `og:image`, and `<link rel="canonical">` — everything
else is relative and will follow on its own.
