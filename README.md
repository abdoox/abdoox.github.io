# Pizza Maker – website

Static site for the Play Store listing (developer website + privacy policy). No build step.

## Publish on GitHub Pages

1. Create a public repo. Best name: `<your-username>.github.io` (see app-ads.txt below).
2. Upload the **contents** of this folder (index.html, privacy-policy.html, assets/, .nojekyll) to the repo root.
3. Repo → Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. After a minute the site is live at `https://<your-username>.github.io/`.

## Play Console

- Store presence → Store settings → **Website**: `https://<your-username>.github.io/`
- App content → **Privacy policy**: `https://<your-username>.github.io/privacy-policy.html`

## app-ads.txt (AdMob)

AdMob looks for `app-ads.txt` at the **root of the domain** set as the developer website.
That only works with a `<username>.github.io` repo (or a custom domain), not a project
page like `<username>.github.io/pizza-maker/`.

Create a file named `app-ads.txt` next to index.html with the line AdMob gives you
(AdMob → Apps → app-ads.txt → "How to set up"). It looks like:

    google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0
