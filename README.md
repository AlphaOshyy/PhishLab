# PhishLab

PhishLab is a security-awareness training demo featuring a polished, responsive fictional social sign-in page.

## Safety by design

- The interface uses fictional branding (Loop Social), not a copied Facebook or Instagram identity.
- The demo never reads, stores, or transmits the username or password field values.
- Submitting the form clears both fields and opens a learning panel.
- Only a simulation event name, event source, and timestamp are stored in the current browser session using `sessionStorage`.
- No backend or database is configured, and no credentials are collected.

## Run locally

Open `index.html` in a modern browser, or serve the repository with any static web server.

## GitHub Pages

1. Open the repository settings.
2. Select **Pages**.
3. Under the build source, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. Wait for the Pages deployment link to appear.

## Possible next steps

Add a consent-based training dashboard that aggregates non-sensitive event metadata only. Do not collect real passwords or imitate a real service in a way that could mislead people outside an authorized exercise.

## Project

https://github.com/AlphaOshyy/PhishLab
