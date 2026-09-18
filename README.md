# Mujtaba Ali Bhutto — Personal Website

A static portfolio and research website prepared for deployment to the GitHub Pages user repository `mujtababhutto.github.io`.

## Structure

- `index.html` — homepage
- `projects/` — research, models, tools and trackers
- `articles/` — article index
- `about/` — background, selected experience, education and references
- `assets/` — shared styles and project images

## Preview locally

Serve this directory from its root so absolute links resolve correctly. For example:

```powershell
python -m http.server 8790
```

Then open `http://127.0.0.1:8790/`.

## Deploy

Create a public GitHub repository named exactly `mujtababhutto.github.io` and upload the contents of this directory to the root of the repository. In repository settings, configure GitHub Pages to deploy from the `main` branch root.

## CV

The public CV has intentionally not been added. When it is ready, place the PDF at `assets/Mujtaba-Ali-Bhutto-CV.pdf` and add a `CV` link to the navigation on each page.
