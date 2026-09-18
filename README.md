# Kaalbela: Extreme Events

A single-page site for *Kaalbela*, a digital anthology on climate catastrophe and resilience — part of the third annual Climate Futures Studio cohort of climate storytelling.

## Structure

```
.
├── index.html      # the full page (hero, Our Land Our Resilience, The Story Behind Kaalbela)
├── images/         # all images referenced by index.html
│   ├── hero.jpg
│   ├── lotus.webp
│   └── land-1.jpg … land-6.jpg
└── README.md
```

## Running it

No build step — open `index.html` directly in a browser, or serve the folder with any static file server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repo settings, go to **Pages** and set the source to the branch/root containing `index.html`.
3. Your site will be published at `https://<username>.github.io/<repo>/`.

## Fonts

Anton, DM Sans, and Noto Sans Bengali are loaded from Google Fonts via a `<link>` in `index.html` — no local font files needed.
