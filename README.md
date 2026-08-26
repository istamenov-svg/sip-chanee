# Sip Channé — Homepage Concept

A static, single-page design concept. No build step, no dependencies.

## Deploy to GitHub Pages

1. Create a new repository (public — GitHub Pages needs public on free accounts).
2. Upload every file in this folder, keeping the structure intact.
3. Repo **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save.**
4. Wait about a minute. The URL appears at the top of that same Pages screen:
   `https://<username>.github.io/<repo-name>/`

Or from the command line:

```bash
git init
git add .
git commit -m "Sip Channé homepage concept"
git branch -M main
git remote add origin https://github.com/<username>/<repo-name>.git
git push -u origin main
```

## Adding the photography

Drop the files into `images/` using exactly these names. The page picks them up
automatically — no code changes needed. Until a file exists, that block shows a
tinted placeholder, so the page always looks intentional.

| File | What it is | Ratio | Suggested size |
|---|---|---|---|
| `hero.jpg` | Bottle in Provence light. Landscape, subject left of center, generous sky for the headline. | ~16:9 | 2400×1400 |
| `routes-wines.jpg` | Both bottles, styled still life. | 4:3 | 1200×900 |
| `routes-story.jpg` | Provence vineyard or the domaine. | 4:3 | 1200×900 |
| `routes-society.jpg` | Table setting, glasses poured, evening light. | 4:3 | 1200×900 |
| `founder.jpg` | Kavita — editorial portrait, with or beside the bottle. | 4:5 | 1200×1500 |
| `bottle-rose.jpg` | Rosé bottle, square crop, soft shadow. | 1:1 | 1400×1400 |
| `bottle-blanc.jpg` | Blanc bottle, square crop — match the light and shadow of the Rosé. | 1:1 | 1400×1400 |
| `locator.jpg` | Restaurant or poolside setting, bottle on the table. | ~16:11 | 1400×960 |
| `giving.jpg` | Event or community photograph. | 3:2 | 1400×930 |

Use `.jpg`, sRGB, quality ~80. Keep the hero under about 400KB and the rest
under 250KB each — it loads over hotel wifi in a meeting.

Every image is cropped with `object-fit: cover`, so anything close to the ratio
works. To nudge a crop, add a `--pos` value to that slot, e.g.
`style="--pos:center 30%"`.

## The two toggles

Bottom-right of the page, and they do not appear in print.

- **Design notes** — the reasoning behind each section. Leave off for a clean
  first impression; switch on to walk someone through the thinking.
- **Image specs** — swaps the placeholder captions for the full photo brief.
  Useful while shooting; irrelevant once the images are in.

## Notes

- `noindex, nofollow` is set in the head so this concept never competes with
  sipchanne.com in search results. Leave it there.
- `.nojekyll` stops GitHub from running Jekyll over the files. Keep it.
- The logo ships in two versions: `logo-dark.png` for light backgrounds and
  `logo-light.png` for the dark footer and Sip Society sections.
- Replace both with SVG when the vector files are available.
