# Slezul — Portfolio

3D animated personal portfolio for Upwork.

## Live demo

→ https://slezul99.github.io

## Stack

- HTML / CSS / JS (no build step)
- Tailwind CSS via CDN
- Three.js for 3D background (particle field + torus knot)
- Vanilla Tilt for card hover effects
- Google Fonts (Inter, Space Grotesk, JetBrains Mono)

## Local preview

```bash
# Just open index.html in browser, or:
python -m http.server 8000
# Then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this repo to GitHub (e.g. `slezul99/slezul99.github.io` for user-site,
   or any repo with Pages enabled).
2. Settings → Pages → Source: "Deploy from a branch" → main / root.
3. Done. Available at `https://<username>.github.io`.

## Customize

Search-replace these in `index.html`:

- `Slezul` — your display name
- `slezul99@gmail.com` — your email
- `@Slezul`, `@Aza_Dev0320` — Telegram handles
- `https://github.com/slezul99` — GitHub
- `~YOUR_UPWORK_ID` — replace with your real Upwork profile ID

## License

MIT — use as a template.
