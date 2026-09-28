# Infusion Manager — diagnostic prototype

Browser-based testing prototype only. Not validated for medication preparation or administration.

## GitHub Pages deployment

1. Create a public repository named `infusion-manager` under your own GitHub account.
2. Upload `index.html` into the repository root, on the `main` branch.
3. Open Settings → Pages → Build and deployment, select **Deploy from a branch**, branch `main`, folder `/(root)`, and Save.
4. Visit `https://Sammi-Nelson.github.io/infusion-manager/` once GitHub Pages reports deployment.

This code should not include real patient/animal/session records. Browser-local session data is specific to its origin and device; a local file's existing session data will not automatically transfer to the hosted URL. Export any test session separately if needed. Do not rely on local browser storage as a sole record.
