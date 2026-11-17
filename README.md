# Aref Shahbakhsh · Personal Academic Website

Source of my personal academic website, <https://aref-shahbakhsh.github.io>, built with [Quarto](https://quarto.org/) and hosted on GitHub Pages.

The site is adapted from the open-source (MIT) Quarto academic-website template by [Mohammad Rafiqul Islam](https://github.com/rispace/rispace.github.io).

## Structure

| File | Page |
|---|---|
| `index.qmd` | Home |
| `research.qmd` | Research, publications, theses, teaching |
| `cv.qmd` | CV (PDF in `_assets/documents/`) |
| `about.qmd` | About |
| `blog.qmd` | Blog and projects |
| `404.qmd` | Not-found page |
| `_quarto.yml` | Site configuration, navbar, footer |

## Local preview

```bash
quarto preview
```

## Deployment

The site is rendered and published to the `gh-pages` branch by GitHub Actions (`.github/workflows/publish.yml`) on every push to `main`.

```bash
git add .
git commit -m "Update site"
git push origin main
```

## License

MIT License. See [LICENSE.txt](LICENSE.txt).
