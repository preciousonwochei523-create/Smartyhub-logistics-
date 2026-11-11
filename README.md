# SmartyHub Logistics

Rider, fleet (3PL) and hub-admin app in a single static `index.html`. Demo data only; the Supabase backend comes next.

## Files
- `index.html` rider and logistics-company app
- `admin.html` separate hub admin (demo passcode admin123, not linked from the app)
- `manifest.webmanifest`, `sw.js` installable PWA and offline shell (needs HTTPS)
- `assets/` official logo (logo-trim.png is the login logo), hex, wordmark and app icons

## Push to GitHub
```
git init
git add .
git commit -m "SmartyHub Logistics app"
git branch -M main
git remote add origin https://github.com/<you>/smartyhub-logistics.git
git push -u origin main
```

## Deploy
- Vercel: import the repo, framework preset "Other", no build command.
- GitHub Pages: Settings, Pages, deploy from `main` / root.
