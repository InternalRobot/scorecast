# Scorecast

A static Malibu-area surf forecast dashboard for Malibu / Point Dume, El Porto, and Topanga.

## Run locally

Open `index.html` directly in a browser, or serve the repository with any static web server.

## Deploy with GitHub Pages

1. Push the repository to GitHub with the default branch named `main`.
2. Open **Settings → Pages** and set the source to **GitHub Actions**.
3. Push to `main` or run **Deploy Scorecast to GitHub Pages** from the Actions tab.

The site has no build step or package dependencies. It requests public marine and weather data from Open-Meteo and NOAA's weather.gov API in the browser.
