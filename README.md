# Flat purchase planner

A static interactive property due-diligence checklist for GitHub Pages.

## Deploy

1. Create a new public GitHub repository (for example `flat-purchase-planner`).
2. Upload `index.html` to the default `main` branch at the repository root.
3. Open **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then `main` and `/(root)`, and save.
4. The URL will typically be `https://USERNAME.github.io/flat-purchase-planner/`. Verify that Pages reports the deployment as successful.

## Persistence

The planner stores checklist completion, notes, mortgage inputs and running costs under the `flat_purchase_planner_v2` localStorage key. Data is scoped to the **exact website origin and browser profile**; it is not synced between devices, browsers or private-browsing sessions. Clearing site data will remove it. The **Export progress** button creates a JSON backup. No data is uploaded to GitHub by using the site.

## Privacy

GitHub Pages is public; the HTML contains the property's example offer value and other facts. Do not commit personal notes or financial records into the repository. Your changes saved in localStorage remain in the browser only.
