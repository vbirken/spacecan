# Sky Dodger

A small browser game about climbing through the sky, slipping between pillars,
collecting powerups, and trying to beat your best score.

Play it here:

https://vbirken.github.io/spacecan/

## How to Play

- Press `Space` or tap/click to start.
- Press `Space` or tap/click again to climb.
- Dodge the pillars and the ground.
- Collect health and shield powerups to survive longer.
- Your best score is saved in the browser.

## Run Locally

This is a plain static site. You can open `index.html` directly in a browser, or
serve the folder with any local static server:

```sh
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Project Structure

- `index.html` contains the game, styling, and JavaScript.
- `*.png` files are the game sprites and environment assets.
- `.github/workflows/pages.yml` deploys the site to GitHub Pages.
- `.nojekyll` keeps GitHub Pages from processing the site with Jekyll.

## Deployment

The project is set up for GitHub Pages. Push changes to `main`, then GitHub
Actions deploys the static site.

If Pages is not live yet, enable it in the repository settings:

1. Go to `Settings` -> `Pages`.
2. Set the source to `GitHub Actions`.
3. Wait for the deployment to finish.
