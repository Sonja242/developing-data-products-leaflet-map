# Developing Data Products: Leaflet Map

**Author:** Sonja Sahebzad

This repository contains the R Markdown webpage for the Johns Hopkins University / Coursera Developing Data Products course. The project presents an interactive city guide to selected learning, cultural, and green locations in Amsterdam.

## View the map

- [GitHub Pages webpage](https://sonja242.github.io/developing-data-products-leaflet-map/)
- [RPubs webpage](https://rpubs.com/Sonja_Janssen/amsterdam-data-science-city-guide)
- [`Amsterdam_Leaflet_Map.Rmd`](Amsterdam_Leaflet_Map.Rmd): R Markdown source
- [`Amsterdam_Leaflet_Map.html`](Amsterdam_Leaflet_Map.html): knitted, self-contained HTML webpage
- [`index.html`](index.html): GitHub Pages version

## Files

- `Amsterdam_Leaflet_Map.Rmd`: complete reproducible webpage and map code.
- `Amsterdam_Leaflet_Map.html`: knitted, self-contained report produced in RStudio.
- `index.html`: GitHub Pages entry point for the published webpage.
- `Developing_Data_Products_Leaflet.Rproj`: RStudio project file.

## Map

The map presents eight Amsterdam locations in three themes: Learning and Science, Culture, and Green Amsterdam. Colored circle markers, labels, popups, a legend, and layer controls help readers explore the locations and compare themes.

The map uses open OpenStreetMap tiles. It does not require an API key. Readers can switch between the Humanitarian and Street map backgrounds, show or hide thematic groups, and select markers for short descriptions.

## Assignment requirements

- The creation date, September 16, 2026, appears on the webpage.
- The webpage was created and knitted from R Markdown.
- The webpage contains an interactive map created with the `leaflet` R package.
- The webpage is publicly available through GitHub Pages and RPubs.

## Rendering

Open `Developing_Data_Products_Leaflet.Rproj` in RStudio. Open `Amsterdam_Leaflet_Map.Rmd` and click **Knit** to regenerate the self-contained HTML webpage.

The project uses `leaflet`, `knitr`, and `rmarkdown`. All map tiles are loaded from open providers, so no API key is required.
