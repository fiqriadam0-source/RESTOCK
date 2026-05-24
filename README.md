# RESTOCK

Modern stock restocking app built with React + Tailwind CSS.

## Stack

- React (Vite)
- Tailwind CSS (via `@tailwindcss/vite`)
- Google Apps Script endpoint integration for material data and restock submission

## Features

- Modern, responsive UI focused on a clean form experience
- Material list auto-loads from endpoint (`action=getMaterials`)
- Restock submission via `POST` with `material`, `kuantiti`, and `type=restock`
- Status messages for loading, success, and error states

## Run Locally

```bash
npm install
npm run dev
```

Build for production:

```bash
npm run build
```

## GitHub Pages Auto-Deploy

This repository is configured to auto-deploy to GitHub Pages using GitHub Actions.

What is already configured:
- Workflow file: [.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml)
- Vite base path is auto-set during GitHub Actions builds, so assets resolve correctly on project pages.

One-time setup on GitHub:
1. Open repository Settings.
2. Go to Pages.
3. In Build and deployment, set Source to GitHub Actions.

After that, every push to main triggers auto-deploy.
