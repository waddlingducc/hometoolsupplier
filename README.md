# Home Tool Supplier — GitHub Pages

This is the built website. No npm install, Node server, API server, or build step is needed.

## Upload and publish
1. Unzip the download.
2. Upload the CONTENTS of the `site` folder to the root of your GitHub repository. Do not upload the ZIP or wrap these files in another folder. Include `.nojekyll`.
3. Open repository Settings → Pages.
4. Set Source to **Deploy from a branch**, select your branch (usually `main`), and select **/(root)**. Save.
5. Set the custom domain to **hometoolsupplier.net**. The included CNAME file already specifies it.
6. Point your domain's DNS to GitHub Pages using GitHub's current custom-domain documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
7. After GitHub verifies DNS and provisions HTTPS, enable **Enforce HTTPS**.

## Important
- This package is configured for the root of **hometoolsupplier.net**, not a `username.github.io/repository/` subfolder. The custom domain and DNS must be configured before using it there.
- Keep `index.html`, `assets`, `media`, `fonts`, `content.json`, and the article/category/archive folders together.
- All 78 articles and the supporting pages are included. Individual route folders allow direct links and page refreshes on GitHub Pages.
- `ads.txt` is included at the website root with the exact requested Google publisher declaration.
- No ads, analytics, Google tags, tracking pixels, or Google-hosted font requests are added.
- The contact form remains disabled until a delivery service is configured. GitHub Pages does not run a backend.
- Social profile destinations were not configured on the original site; those controls remain inactive.
- The privacy policy retains the original text and should be reviewed against the current site's features.
- Article data is a snapshot, not a live connection to WordPress.

Uploading these files does not transfer the domain registration or automatically configure DNS.
