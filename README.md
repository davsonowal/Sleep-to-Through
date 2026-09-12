# Sleep Through Time

A single-page site tracing human sleep patterns from prehistoric hunter-gatherer
nights to the screen-lit present, built as a section for a larger e-tourism
project. It closes with a set of real-world destinations where older sleep
rhythms — biphasic rest, no artificial light, seasonal extremes — are still
part of daily life.

## Structure

```
.
├── index.html   # page content and structure
├── style.css    # all styling
└── README.md
```

No build step, no dependencies beyond two Google Fonts loaded via CDN
(`Newsreader` and `Work Sans`).

## Viewing it locally

Just open `index.html` in a browser — there's nothing to install or compile.

## Publishing with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`,
   pick the `main` branch and the `/ (root)` folder.
4. Save. GitHub will publish the site at
   `https://<your-username>.github.io/<repo-name>/`.

## Content sections

- **Hero** — framing for the topic.
- **Timeline** — four eras: firelit hunter-gatherer sleep, the pre-industrial
  "two sleeps," the arrival of artificial light, and today's screen-lit night.
- **Destinations** — onsen towns, siesta country, desert camps, and the
  Nordic midnight sun / polar night, as places where an older sleep rhythm
  is still tangible for travelers.

## Customizing

- Swap or add destinations in the `.destinations` section of `index.html`.
- Colors and type scale are defined as CSS custom properties at the top of
  `style.css` (`:root`), so palette changes are one-line edits.
