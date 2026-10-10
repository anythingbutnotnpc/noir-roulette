# NOIR 001 — Roulette Instrument

A single-file, retro-futurist European roulette simulator built with HTML, CSS, and JavaScript.

## Publish with GitHub Pages

1. Create a **public** GitHub repository named `noir-roulette`.
2. In the repository, select **Add file → Upload files**.
3. Upload `index.html`, `README.md`, and `.nojekyll` from this folder (not the ZIP itself).
4. Commit the files to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
7. Select branch `main` and folder `/(root)`, then select **Save**.
8. Wait for the deployment to finish. The website should be available at:
   `https://YOUR-GITHUB-USERNAME.github.io/noir-roulette/`

Replace `YOUR-GITHUB-USERNAME` with your exact GitHub username. The first deployment can take several minutes.

## How spins and history work

- The game is entirely client-side; there is no server or database to configure.
- Each person's history is saved in their own browser on their own device. It is not shared with other visitors.
- The most recent 300 spins are kept locally, subject to the browser allowing local storage.
- Google Fonts are loaded from Google Fonts when internet access is available; system fallback fonts are used if they are unavailable.
- This is a simulation only, with no real-money wagering.

## Updating the site

Upload the replacement `index.html` to the repository root and commit the change. GitHub Pages will publish the new version automatically after the deployment completes.
