# Legal Neural Map

Pick a judgment from the library and watch its legal map animate: cards fade in, then wires draw out from the main case.
Followed cases sit on the left; issues, outcome, cited cases, statutes and doctrines on the right; reliefs beyond them. Claimants wire in from the left, defendants from the right. A ↔ badge marks anything that also appears in other judgments. Static site: no build step.

## Host on GitHub Pages
1. Upload the contents of this folder to a repo (index.html at the root).
2. Settings → Pages → Deploy from a branch → `main` / `(root)`.
3. Open `https://<user>.github.io/<repo>/`. Links like `.../#case3` open a specific judgment.

## Add or change judgments
Put a `schememetadata*.json` file in `data/cases/` and add its filename to `data/index.json`.
(index.html also holds an embedded copy of the original 20, used if the data folder can't be fetched, e.g. when opened from disk.)
