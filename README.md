# Aref Shahbakhsh · Personal Academic Website

Source of my personal academic website, <https://aref-shahbakhsh.github.io>, built with [Quarto](https://quarto.org/) and hosted on GitHub Pages.

The site is adapted from the open-source (MIT) Quarto academic-website template by [Mohammad Rafiqul Islam](https://github.com/rispace/rispace.github.io).

## Structure

| File | Purpose |
|---|---|
| `index.qmd` | Home: intro, research spotlight, news, latest posts |
| `about.qmd` | Background and interests |
| `research.qmd` | Publications and theses |
| `projects.qmd` | Software and hardware projects |
| `blog.qmd` | Blog index (lists everything in `posts/`) |
| `cv.qmd` | CV (PDF in `_assets/documents/`) |
| `posts/` | One folder per blog post (`posts/<name>/index.qmd`) |
| `_quarto.yml` | Site configuration, navbar, footer |

## Writing a post

1. Copy `posts/_post-template/` to `posts/my-new-post/`.
2. Edit `index.qmd` (title, date, categories, content). Put images in the same folder.
3. Commit and push. The post appears on the Blog page and the home page automatically.

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
