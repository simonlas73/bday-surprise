# 🎉 Birthday Surprise — Scotland Holiday Reveal

A mobile-first, single-page birthday surprise website that progressively reveals a 1-week holiday to Scotland across 4 animated steps.

## 🌐 Live Site

**[https://bday-surprise.vercel.app](https://project-0g400-git-copilot-deploy-ap-ededbe-simonlas73s-projects.vercel.app/)]([https://bday-surprise.vercel.app](https://project-0g400-git-copilot-deploy-ap-ededbe-simonlas73s-projects.vercel.app/))**

Scan the QR code below to open it directly on your mobile device:

![QR Code](qr.png)

## How it works

| Step | Description |
|------|-------------|
| 1 🎂 | **Happy Birthday!** — festive greeting |
| 2 🔮 | **A Mystery Awaits…** — builds suspense |
| 3 ✈️ | **Pack Your Bags!** — five Scotland clues |
| 4 🏴󠁧󠁢󠁳󠁣󠁴󠁿 | **Scotland!** — full reveal with confetti, trip details and tartan accent |

## Deployment

The site is automatically deployed to [Vercel](https://vercel.com/) via the included GitHub Actions workflow (`.github/workflows/deploy.yml`) whenever changes are pushed to the `main` branch.

### Setup

Before the workflow can run, add the following secrets to your GitHub repository (**Settings → Secrets and variables → Actions**):

| Secret | How to obtain |
|--------|--------------|
| `VERCEL_TOKEN` | [Vercel dashboard](https://vercel.com/account/tokens) → create a token |
| `VERCEL_ORG_ID` | Run `vercel link` locally, then check `.vercel/project.json` |
| `VERCEL_PROJECT_ID` | Same `.vercel/project.json` file after linking |
