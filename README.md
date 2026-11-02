# universal-concierge-sdk-documentation

Shared developer documentation for the Universal Concierge Android and iOS SDKs.

Placeholder site only — Docusaurus and guides will be added later.

## GitHub Pages (use branch deploy)

The **Deploy Pages** GitHub Action cannot enable Pages in this org (`Resource not accessible by integration`). Use **Deploy from a branch** instead:

1. Open **Settings → Pages** (repo admin required).
2. **Build and deployment → Source:** **Deploy from a branch**.
3. **Branch:** `main` → **`/ (root)`** → **Save**.
4. Leave **Custom domain** empty.

Live URL (after a minute or two):

**https://rakutenailab.github.io/universal-concierge-sdk-documentation/**

No workflow run is required; GitHub publishes `index.html` from the repo root.

When we add Docusaurus later, we can switch to **GitHub Actions** as the source after an admin has enabled Pages once, or keep publishing the `build/` output via branch deploy.
