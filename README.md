# TANMAY EAT Access Token — Safety Tool

Branded static website for the `tanmayjn2015/tanmay-eat-access-token` repository.

## Security behavior
- Static site; no backend or environment variables required.
- Does **not** exchange EAT tokens for access/JWT tokens.
- Does not send pasted URLs or token values to a third-party API.
- Can display basic URL metadata (`account_id`, `region`, `nickname`) locally in the browser.
- Do not publish or share active tokens, passwords, or login links.

## Deploy
- **GitHub Pages:** Settings → Pages → Build and deployment → GitHub Actions. Push to `main`; the workflow in `.github/workflows/static.yml` deploys the static site.
- **Vercel:** Import the repository and deploy the project as a static site. `index.html` is the entry point.

## Repository
https://github.com/tanmayjn2015/tanmay-eat-access-token
