# Landing

A simple, responsive landing page ready to deploy on GitHub Pages.

## Local preview

Open `index.html` in your browser or use a simple static file server such as:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

GitHub Actions will publish the site to GitHub Pages on every push to the `work` branch using [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

1. In the repository settings, enable GitHub Pages with the "GitHub Actions" source.
2. Push to `work` (or trigger the workflow manually). Pages will deploy to the `github-pages` environment with the URL reported in the workflow summary.
