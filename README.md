# Fisheries Research Portal

Quarto website (R) published on GitHub Pages: map explorer, species profiles, fisheries data and publications.

## Develop locally (Positron)

```r
install.packages(c("plotly", "leaflet", "reactable", "htmltools", "rmarkdown"))
```

Then run `quarto preview` in the terminal.

## Publish

Push to `main`; the GitHub Action renders and deploys. One-time setup: **Settings → Pages → Source: GitHub Actions**.

## Structure

- `*.qmd`: pages; `species/`: one `.qmd` per species (auto-listed)
- `data/`: CSVs (currently placeholders)
- `files/`: published PDFs
