# Ke Liu · Academic Homepage

Personal academic website built with React and Vite, adapted from [Anleeno Academic](https://github.com/Anleeno/anleeno-academic) (upstream commit 763fd7a64c2fbc9434dc6f04f4e0f64561faaee2). Original code licensing is retained in LICENSE. Original author personal materials are excluded.

Intended website: https://ke1505218-lang.github.io/academic-homepage/

## Edit content

Update config/hero.json, config/about.json, config/publications.json and config/education.json. Assets live in src/assets/. The KL monogram is a placeholder, not a photograph. Full publication bibliographic details and paper link await confirmation.

## Run and validate

Use Node.js 22 or later. Run npm ci, npm run lint, npm test, and npm run build. Use npm run dev for local preview.

## Deploy

In repository Settings → Pages, set Source to GitHub Actions. Pushes to main trigger .github/workflows/deploy-pages.yml. The Vite base is /academic-homepage/; no custom domain is configured.
