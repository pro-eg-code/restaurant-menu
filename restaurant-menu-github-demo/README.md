# Restaurant Menu — GitHub-only demo

## What it does
- GitHub Pages hosts the static site.
- `menu.json` stores product data.
- `owner.js` uses the GitHub REST API to update `menu.json` and upload images into `images/`.
- Demo owner password: `0000`.

## Before use
Open `owner.js` and replace:
- `YOUR_GITHUB_USERNAME`
- `YOUR_GITHUB_FINE_GRAINED_TOKEN`

The token should be fine-grained, limited to this repository, with Contents → Read and write.

## Important architecture limitation
The token is exposed to browser JavaScript. This is therefore a controlled demo architecture, not a production authentication system.
