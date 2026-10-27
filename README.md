# profile-fortune

No-cache SVG fortune endpoint for [kjodhpur](https://github.com/kjodhpur) profile README.

## Live right now

Until this repo is imported to its own Vercel project, the profile uses:

**https://events-portfolio-ivory.vercel.app/api/fortune**

(`events-portfolio` → `app/api/fortune`)

## Deploy this repo as the dedicated host

1. Open [vercel.com/new](https://vercel.com/new) → Import `kjodhpur/profile-fortune`
2. Deploy (no env vars / secrets)
3. Update `kjodhpur/kjodhpur` README `<img src="…">` to the new URL (`/` or `/api/fortune`)

## API

`GET /` or `GET /api/fortune` → random AVI-style terminal SVG  
Headers: `Cache-Control: no-store, no-cache, must-revalidate, max-age=0`
