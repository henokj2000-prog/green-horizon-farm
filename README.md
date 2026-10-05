# Green Horizon — Layer Growth Model

A single-file web page that models growing a layer flock (starting flock → target size) by reinvesting profit into new pullets. Rebuilt from the `Horizon_Farm_PLan.xlsx` workbook.

- Optional bank loan (untick for an interest-free start with your own cash)
- Cash never goes below zero: purchases are trimmed to what cash can cover
- Editable laying curve, housing, labour and other bracket costs, and a manual purchase plan
- Inputs are saved in the browser (localStorage); no server, no build step

## Run it
Open `index.html` in a browser.

## Publish with GitHub Pages
Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / root → Save.
The page will be at `https://<your-username>.github.io/<repo-name>/`.
