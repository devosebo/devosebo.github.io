# Moniq — new site

Drop-in replacement for the `moniq/` folder in `devosebo/devosebo.github.io`.

## What's here
- `index.html` — redesigned landing page (light/dark/auto theme, three real screenshots).
- `privacy.html` — Privacy Policy.
- `terms.html` — Terms of Use.
- `assets/moniq-icon.png` — 1024×1024 app icon (Ledger Thin).
- `assets/screen-enter.png` · `screen-insights.png` · `screen-transactions.png` — iPhone Air screenshots.

## Design notes
- **Theme**: three-state toggle — Dark / Light / Auto. Auto follows the system; first-time visitors get their OS theme.
- **Type**: system stack (`-apple-system`), tabular numerals on monetary figures.
- **Palette**: warm off-white (#f6f3ec) light mode / near-black (#0b0d0f) dark mode, with brand red and green accents matching the icon.
- **Hero**: badge → headline → lede → dual CTA (App Store + privacy). Three iPhone Air screenshots beneath.
- **Privacy promise** lives on the homepage as a teaser; full Privacy Policy is `privacy.html`.
- **App Store link** wired to the live listing.

## How to deploy
Replace the contents of `moniq/` in `devosebo.github.io` with everything in this folder, commit, push.

```
moniq-new/
├── index.html
├── privacy.html
├── terms.html
├── README.md
└── assets/
    ├── moniq-icon.png
    ├── screen-enter.png
    ├── screen-insights.png
    └── screen-transactions.png
```
