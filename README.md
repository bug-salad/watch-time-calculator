# Watch Time Calculator

**Open-source** single-file web app that computes total watch time and projected end date/time in the user's local time zone.

- **Live:** [bugsalad.net](https://bugsalad.net) (or your deployed URL)
- **Source:** This repository — one HTML file, no build step.

## Features

- Episode count + per-episode length (hours/minutes)
- Optional second show with per-show totals
- 12/24 hour mode (persisted); date format follows (dd/mm in 24h, m/d in 12h)
- Light/dark theme (persisted)
- About modal (blurred backdrop, centered dialog)
- Minute-aligned clock updates (no `setInterval` drift)
- Responsive: desktop (toggles top-left) and mobile (toggles under title)
- Accessible (ARIA, focus, keyboard)

## Run locally

Open `index.html` in a browser, or serve the folder with any static server (e.g. `npx serve .`).

## Publishing to GitHub

1. **Create the repo on GitHub**
   - Go to [github.com/new](https://github.com/new).
   - Repository name: `watch-time-calculator` (or your choice).
   - Public, no README/license/ignore (we already have the files).
   - Create repository.

2. **Push this folder**
   ```bash
   cd C:\Users\YOUR_PC_NAME\watch-time-calculator
   git init
   git add .
   git commit -m "Initial commit: Watch Time Calculator (open-source)"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/watch-time-calculator.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` with your GitHub username (e.g. `bug-salad`).

3. **Update the app link**
   - In `index.html`, replace `bug-salad` in the GitHub URL with your username (also update the header comment and About dialog link).

## License

This website and all of its code is **free to use** by anyone, for any purpose. Do whatever you want with it.
