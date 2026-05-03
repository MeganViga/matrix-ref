# Matrix → row echelon form

Static practice page: random integer matrices, **exact fractions** (e.g. `R3 → R3 - (59/31)R1`), reduced-fraction matrix display (no decimals), **your own** row operations, **Check REF / RREF**, plus a built-in reference elimination using the same rational arithmetic.

## Run locally

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Publish on GitHub Pages

1. Create a GitHub repository and push this folder (or only the `matrix-row-echelon` contents as the repo root).

2. In the repo: **Settings → Pages**.

3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder **`/ (root)`** (if `index.html` is at the repository root).

   If this project lives inside a monorepo, either publish the **`/docs`** folder and copy these files into `docs/`, or use a GitHub Action to deploy the subdirectory.

4. Your site will be at `https://<username>.github.io/<repo>/`.

All asset paths are relative (`./styles.css`, `./app.js`), so it works on project Pages URLs with a path prefix.
