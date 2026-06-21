# Basar Labs — Landing Page

Official landing page for Basar Labs, published with GitHub Pages.

- **Live site:** https://basarlabs.com.tr
- **Stack:** Static HTML + CSS (no build step)

## Structure

```
basarlabs-site/
├── index.html      # Page markup
├── styles.css      # Styling
├── CNAME           # Custom domain for GitHub Pages
├── .nojekyll       # Serve files as-is (skip Jekyll processing)
└── assets/         # Images and other static assets
```

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```powershell
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Pushing to the `main` branch triggers the GitHub Pages deployment automatically.

```powershell
git add .
git commit -m "Update landing page content"
git push origin main
```

Deployment status: repository **Actions** tab → *pages build and deployment*.
