# actuals_lander

Landing page for [Actuals](https://github.com/Hamza-Saraswat/actuals) — honest metrics for AI tools.

**Live: https://useactuals.netlify.app/**

Static `index.html` + `404.html`, zero build step, **zero external requests, no analytics** — IBM Plex is self-hosted in `fonts/` (OFL 1.1, license included) precisely so that claim stays true.

**Deploy on Netlify:** New site → Import from Git → pick this repo → no build command, publish directory `/` (already set in `netlify.toml`).

Netlify is the single canonical host — `netlify.toml` carries the security headers (`X-Frame-Options`, `nosniff`, `Referrer-Policy`, `Permissions-Policy`), which a GitHub Pages mirror would not serve. Pages was disabled for this repo deliberately; don't re-enable it without moving those headers too.

MIT licensed — see [LICENSE](LICENSE). Bundled IBM Plex fonts are OFL 1.1 ([fonts/OFL.txt](fonts/OFL.txt)).
