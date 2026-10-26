# Earnings Watch · MGMT 6110 Problem Set 6 · Group 5 · “Watcher”

Two static pages, no build step.

| Path | What it is |
|---|---|
| `index.html` | The Group 5 page: six-minute demonstration of the watcher's output, Tuesday 27 October evidence capture, team experience, oversight findings, and backup material (requirements, risk register, proposed controls, evidence ledger, T1–T8). |
| `deck/index.html` | The 19-slide presentation deck (arrow keys to advance, `O` overview, `N` notes, `F` full screen, `P` print). |

Both pages read from the data already copied into them; nothing is fetched at run time except the fonts, the three.js
library for the opening 3D scene (with a CSS fallback if it is blocked), and the live dashboards embedded on the deck's
slide 4. The live watcher dashboard itself is at https://ywanwah-earnings-extractor-assessor.vercel.app/.

## Publish

**GitHub Pages:** Settings → Pages → Source “Deploy from a branch”, branch `main`, folder `/ (root)`.
The page is then at `https://<user>.github.io/<repo>/` and the deck at `https://<user>.github.io/<repo>/deck/`.

**Vercel:** import the repository as a new project with no framework and no build command; the page is at `/` and the deck at `/deck/`.

## First push

```bash
git init
git add .
git commit -m "Group 5 Watcher page and deck"
git branch -M main
git remote add origin https://github.com/ywanwah/<repo>.git
git push -u origin main
```

Nothing here is investment advice. The pages report company results and the checks on them.
