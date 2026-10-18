# VitaliumWeb

Public website for the Vitalium app, served with GitHub Pages:

- `index.html`: support page (App Store "Support URL")
- `privacy.html`: privacy policy (App Store and Google Play "Privacy Policy URL")
- `delete-account.html`: account deletion page (Google Play "Delete account URL")

Plain HTML and one stylesheet. No build step.

## Before publishing

Replace every placeholder:

- `[YOUR FULL NAME]`
- `[CONTACT EMAIL]`
- `[RENDER REGION]` (the region of the Render service, shown in the Render dashboard)
- `[RETENTION PERIOD]` (how long de-identified workout and reward records are kept)

Find any that remain with `grep -n "\[" *.html`.

## Publishing

1. The repository must be public for free GitHub Pages.
2. On GitHub: Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)**.
3. After a minute the site is at `https://dylan-graham.github.io/VitaliumWeb/`.

Page URLs:

- `https://dylan-graham.github.io/VitaliumWeb/`
- `https://dylan-graham.github.io/VitaliumWeb/privacy.html`
- `https://dylan-graham.github.io/VitaliumWeb/delete-account.html`
