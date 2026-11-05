# Portal de Investigação Pesqueira

Site Quarto (R) publicado no GitHub Pages: explorador de mapas, fichas de espécies, dados das pescas e publicações.

## Desenvolver localmente (Positron)

```r
install.packages(c("plotly", "leaflet", "reactable", "htmltools", "rmarkdown"))
```

Depois execute `quarto preview` no terminal.

## Publicar

Faça push para `main`; a GitHub Action gera e publica o site (Settings → Pages → Source: GitHub Actions).

## Estrutura

- `*.qmd`: páginas; `species/`: um `.qmd` por espécie (listado automaticamente)
- `data/`: CSV (atualmente provisórios)
- `files/`: PDF publicados
