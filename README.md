# VitalFusion GitHub Pages site

Static, dependency-free website for the VitalFusion app.

## Before you publish

1. In `privacy.html`, `terms.html`, and `support.html`, replace every bracketed placeholder (`[info@techcostsolutions.com]`, `[info@techcostsolutions.com]`, business name, address, and governing jurisdiction) with real values.
2. Confirm every privacy statement matches the released app and its App Store privacy disclosure. If analytics, accounts, cloud sync, third-party SDKs, subscriptions, or data sharing change, update the policy before release.
3. Have qualified legal counsel review the policy and terms for your business and regions of operation.

## Publish on GitHub Pages

1. Create a repository, for example `vitalfusion`.
2. Upload the **contents** of this folder to the repository root (not the folder itself).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main`, choose `/(root)`, then save.
5. GitHub will publish the site at `https://<your-github-username>.github.io/vitalfusion/`.

The App Store Connect Privacy Policy URL should be the published `privacy.html` address, for example `https://<your-github-username>.github.io/vitalfusion/privacy.html`.

## Files

- `index.html` — home page
- `privacy.html` — App Store-oriented privacy policy
- `terms.html` — terms of service
- `support.html` — support and FAQ
- `css/styles.css` — responsive styles and theme support
- `js/main.js` — theme and mobile navigation behavior
- `assets/` — favicon and homepage artwork
