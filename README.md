# Farrington Insurance Agency — Reports

Static site of client performance reports for **Farrington Insurance Agency**
(San Jose, CA · California Auto), built on the GOAL Platform.

## Contents

| File | Report |
|------|--------|
| `index.html` | Landing page linking to the reports |
| `farrington-client-report.html` | Account Performance Review (last-30-day results) |
| `zip-code-targeting-report.html` | Zip Code Targeting Strategy |

## Deployment

Deployed on **Vercel** as a static site — no build step.

- **Framework preset:** Other (`"framework": null` in `vercel.json`)
- **Build command:** none
- **Output directory:** repository root
- **Entry point:** `index.html`

Vercel serves the HTML files directly from the repository root. Importing this
repo into a Vercel project (or connecting it to an existing one) and deploying
is all that's required; every push to `main` then produces a new deployment.
