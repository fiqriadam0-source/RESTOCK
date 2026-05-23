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
