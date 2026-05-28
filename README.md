
// FILE: README.md
# MLB Player Finder

Android-friendly React + Vite web app that you can host on GitHub Pages.

## What it does
- Uses your phone camera in the browser
- Lets you upload an image if camera access is unavailable
- Searches MLB players using the public MLB Stats API
- Shows live public player profile and current-season hitting/pitching metrics

## Local setup
npm install
npm run dev

## Build
npm run build

## GitHub Pages setup
1. Create a GitHub repo named `mlb-player-finder`
2. Push all files to `main`
3. In GitHub repo settings, open **Pages**
4. Under **Build and deployment**, choose **GitHub Actions**
5. The workflow in `.github/workflows/deploy.yml` will publish the site

## Important note
This version is fully static and GitHub Pages-friendly.
Automatic image recognition of MLB players would require a backend/API later.

## Suggested repo structure
mlb-player-finder/
  index.html
  package.json
  vite.config.js
  src/
    App.jsx
    main.jsx
  .github/
    workflows/
      deploy.yml
  README.md
