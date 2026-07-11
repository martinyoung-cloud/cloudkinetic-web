# Cloud Kinetic Solutions website

Static single page corporate site for Cloud Kinetic Solutions Ltd, served by
Azure Static Web Apps at https://cloudkinetic.co.uk.

The site is plain HTML and CSS in `src/`. Every push to `main` deploys via the
GitHub Actions workflow in `.github/workflows/deploy.yml` using the Static Web
Apps deployment token stored as the `AZURE_STATIC_WEB_APPS_API_TOKEN` secret.

Before going live the owner must replace the company registration number
placeholder in `src/index.html`.
