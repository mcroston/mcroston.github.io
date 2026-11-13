# mcroston.github.io

Personal academic website of Merriah Croston, built with [Quarto](https://quarto.org).

## Editing

- Pages are `.qmd` files (Markdown). Edit them in RStudio or any text editor.
- Site navigation, footer and theme live in `_quarto.yml`; styling in `custom.scss`.
- To preview locally: open the folder in RStudio and click **Render**, or run `quarto preview` in a terminal.
- To update the CV, replace `files/croston_cv.pdf`.

## Publishing

Pushing to `master` triggers the GitHub Action in `.github/workflows/publish.yml`, which renders the site and publishes it to the `gh-pages` branch. GitHub Pages serves the site from that branch.
