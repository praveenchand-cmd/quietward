# Quietward website (support + privacy policy)

Static pages for the App Store's required Support URL and Privacy Policy URL. No build step, no trackers.

## Publish free with GitHub Pages

Free GitHub accounts can only publish Pages from a **public** repository, so the website lives in its own
public repo, separate from the private app code.

1. Create a GitHub account at github.com, using your personal email, if you don't have one.
2. Click **New repository**, name it `quietward`, make it **Public**, and create it.
3. Click **Add file → Upload files**, drag in `index.html`, `privacy.html`, `style.css` and `icon.png`, then
   click **Commit changes**.
4. Open **Settings → Pages**. Under Build and deployment choose **Deploy from a branch**, set Branch to
   `main` and folder to `/ (root)`, then click **Save**.
5. After a minute or two the site is live:
   - Support URL: `https://<your-username>.github.io/quietward/`
   - Privacy Policy URL: `https://<your-username>.github.io/quietward/privacy.html`
6. Replace `praveenchand-cmd` in `App/Core/AppLinks.swift` and `docs/APP_STORE_LISTING.md`.

Before submitting to the App Store, replace `[publication date]` in `privacy.html` with the real date.
