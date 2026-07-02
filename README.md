# Silo — Privacy & Support Site

A single-page Hugo site that hosts the Privacy Policy and Support pages required
for the Silo iOS app's App Store submission. No theme, no dependencies — just
Hugo's built-in templating and the official GitHub Pages deployment workflow.

## Before you deploy — 2 required edits

1. **Your email.** Replace `REPLACE-WITH-YOUR-EMAIL@example.com` (appears 4 times
   in `content/_index.md`, plus once in `hugo.toml`) with a real support address
   you monitor. Apple requires a working support contact.

2. **Your base URL.** In `hugo.toml`, replace
   `https://REPLACE-WITH-YOUR-DOMAIN-OR-GH-PAGES-URL/` with either:
   - your GitHub Pages URL (e.g. `https://justinb57.github.io/silo-site/`), or
   - your custom domain once you have one (e.g. `https://silosupport.app/`).

   Note: the deploy workflow overrides baseURL automatically for GitHub Pages,
   so this value mainly matters for local preview and a custom domain.

## Preview locally (optional)

If you have Hugo installed on your Mac:

```
hugo server
```

Then open http://localhost:1313 — you'll see the full page.

## Deploy to GitHub Pages

1. Commit and push this folder to your `silo-site` repo on the `main` branch.
2. On GitHub, go to the repo's **Settings → Pages**.
3. Under **Build and deployment → Source**, select **GitHub Actions**.
4. That's it. The included workflow (`.github/workflows/deploy.yml`) builds and
   deploys automatically on every push to `main`. Watch progress under the repo's
   **Actions** tab; when it finishes, your site is live at the URL shown there.

## Custom domain (after you source one from Cloudflare)

1. In **Settings → Pages → Custom domain**, enter your domain and save.
2. At your DNS provider (Cloudflare), add the records GitHub tells you to add.
3. Update `baseURL` in `hugo.toml` to your custom domain and push.

## The two URLs Apple needs

Once live, your App Store Connect fields are:

- **Privacy Policy URL:** `https://your-site/#privacy`
- **Support URL:** `https://your-site/#support`

(The single page carries both sections; the `#privacy` and `#support` anchors jump
to each. If Apple prefers distinct pages, tell me and I'll split them.)
