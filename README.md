# ML!PA — ISO 9001 Awareness Training

A self-contained, bilingual (English / German) quality-awareness training web app for all ML!PA employees, supporting the ISO 9001 certified Quality Management System.

## Contents

- `index.html` — the complete training app (HTML, CSS, and JS in a single file; no build step).
- `MLPA Logo 2015-01 trans 3.png` — logo used in the header and footer.
- `staticwebapp.config.json` — Azure Static Web Apps routing and security headers.
- `.github/workflows/azure-static-web-apps.yml` — CI/CD workflow that deploys on every push to `main`.

## Run locally

Open `index.html` in a browser, or serve the folder:

```powershell
npx serve .
```

## Deploy to Azure Static Web Apps

1. In the Azure portal, create a **Static Web App** (Free tier) and connect it to this GitHub repository, branch `main`.
2. During setup choose **Custom** build presets with:
   - App location: `/`
   - Api location: *(empty)*
   - Output location: *(empty)*
3. Azure adds the `AZURE_STATIC_WEB_APPS_API_TOKEN` secret to the repo automatically. Each push to `main` then deploys via the included workflow.

Alternatively, deploy directly with the SWA CLI:

```powershell
npm install -g @azure/static-web-apps-cli
swa deploy . --env production
```
