# JohnFoodLanding

Static landing page for the **John Foods** food-delivery app.
Pure HTML + CSS + vanilla JS. No build step.

- Live: `https://johnfoodlanding.vercel.app` (Vercel, root of this repo)
- App repo: https://github.com/merjohnpagente/JohnFood
- Download Now points to
  https://github.com/merjohnpagente/JohnFood/releases/latest (Android APK)

## Deploy

Pushing to `main` redeploys automatically if the Vercel project is
connected to this repo. Manual deploy:

```
npx -y vercel@latest deploy --prod --yes
```

## Rules

Prices in PHP only (`peso()` in `menu.js`), Material Symbols icons only,
no emoji. Menu data mirrors the app's `sample_data.dart`.
