# Sip Channé — Image Brief

> **Status: all nine images are in place.** This document is the brief they were
> made from — keep it for reshoots, replacements, and for the eventual real
> photography. See the note at the foot on what still needs a camera.

Nine images. Filenames are fixed — drop them into `images/` and the page picks
them up with no code changes.

Two of the nine cannot be credibly generated (see **Read this first**). The
other seven can, and this brief gives you a ready-to-paste prompt for each.

---

## Read this first — two images AI cannot do

**`founder.jpg` — do not generate a likeness of Kavita.** Generating a
photorealistic image of a real, identifiable person and presenting it as her is
both unreliable and a bad idea in a document going to that person. Three
options, in order of preference:

1. Use a real photograph. There are plenty on her channels and in press coverage.
2. Shoot a new one — it is on the content line in Section 7 of the proposal.
3. If you need a placeholder for the demo, generate a **non-identifiable**
   composition: hands pouring, an over-the-shoulder view, a figure out of focus
   in the background. The prompt below does that.

**`bottle-rose.jpg` and `bottle-blanc.jpg` — the label will be wrong.** No image
model reproduces a specific label, and a mangled version of their own bottle is
the one error the client will spot instantly. Options:

1. Cut out the bottle from an existing product shot — best result, ten minutes
   in any editor.
2. Generate a bottle and composite the real label over it.
3. Use the prompts below and accept an unbranded stand-in for the demo only.

Everything else on this list generates well.

---

## Global style — prepend this to every prompt

> Editorial luxury wine photography, Côtes de Provence in late summer. Natural
> daylight, soft and diffused, no harsh contrast. Warm neutral palette: pale
> copper, blush pink, sand, cream, weathered stone, muted olive. Medium-format
> film aesthetic, Kodak Portra 400, fine grain, gentle highlight roll-off.
> Shallow depth of field. Generous negative space. Calm, unhurried, expensive
> but not flashy.

**Global negative prompt:**

> text, letters, logos, watermarks, signatures, labels with writing, harsh
> flash, oversaturated colors, HDR, teal-and-orange grade, plastic skin, busy
> background, clutter, tourists, crowds, cartoon, illustration, 3D render,
> lens flare, vignette, tilted horizon, red wine, white wine in a rosé glass

**Settings:** photorealistic, highest quality, sRGB, export as `.jpg` at ~80%.
Keep `hero.jpg` under 400KB and the rest under 250KB each — it has to load over
hotel wifi in a meeting.

---

## 1. `hero.jpg` — 2400×1400 · 12:7 (≈16:9)

**Correction to my earlier spec:** I originally wrote "subject left of center."
That was wrong. The headline sits **bottom-left**, so the bottle needs to be on
the **right**, with the lower-left third kept calm.

> A single pale copper rosé wine bottle standing on a weathered limestone ledge,
> positioned in the right third of the frame. Behind it, a soft-focus Provençal
> landscape — dry grasses, distant olive trees, hazy afternoon light. The left
> and lower-left of the frame is open sky and out-of-focus warm haze with no
> detail. Late golden hour, sun low and behind, gentle backlight catching the
> glass. Wide landscape composition.

- **Keep clear:** left half, and the bottom third across the full width. Both
  carry white text.
- **Tonally:** midtones in the lower-left, not bright white — the page darkens
  it slightly but very pale imagery will still wash out the headline.
- **Avoid:** lavender fields. Every rosé brand uses them and it reads as stock.

---

## 2. `routes-wines.jpg` — 1200×900 · 4:3

> Two wine bottles side by side — one pale copper rosé, one pale straw white —
> on a cream linen surface. Styled still life from a slight three-quarter angle.
> A few loose apricots and a sprig of white flowers nearby. Soft window light
> from the left, long gentle shadows falling right. Muted, airy, minimal.

- Both bottles fully in frame with breathing room. Nothing cropped.

---

## 3. `routes-story.jpg` — 1200×900 · 4:3

> An old Provençal stone farmhouse at the edge of a vineyard, warm afternoon
> light on the walls. Rows of mature vines with gnarled trunks lead toward it.
> Dry grass, cypress trees, pale blue sky with high thin cloud. Wide, quiet,
> unpeopled. Documentary rather than promotional.

- Old vines specifically — theirs are 40 to 60 years old and it shows in trunk
  thickness. It is the kind of detail a winemaker notices.

---

## 4. `routes-society.jpg` — 1200×900 · 4:3 · **darker image**

> An outdoor table at dusk, four glasses of pale rosé poured and catching the
> last light. Linen tablecloth, olive branches, a few lit candles just coming
> up. Warm low light, deep shadows, blue hour sky beyond. Intimate and social
> but no faces in focus. Moody, rich, low key.

- This one sits in a dark card. Deliberately keep it darker and warmer than the
  other two beside it.

---

## 5. `founder.jpg` — 1200×1500 · 4:5 portrait

**Non-identifiable placeholder only — see Read this first.**

> A woman's hands pouring pale rosé into a glass at a sunlit table, seen from
> the side. Face not visible, cropped above the shoulders. Soft linen sleeve,
> simple gold jewelry. Warm natural window light, cream and blush tones,
> shallow focus on the pour. Editorial lifestyle photography, vertical.

- Replace with a real photograph before anyone outside your team sees it.

---

## 6. `bottle-rose.jpg` — 1400×1400 · 1:1

**Label will not render correctly — see Read this first.**

> A single tall wine bottle of pale copper rosé, standing centered on a smooth
> cream surface against a soft cream backdrop. Clean studio product photography,
> one large soft light from the upper left, gentle gradient shadow falling to
> the lower right. Minimal, elegant, generous space around the bottle. Square
> composition. Unlabeled clear glass bottle.

- "Unlabeled" is deliberate — a blank bottle reads as a placeholder, whereas a
  garbled label reads as a mistake.

---

## 7. `bottle-blanc.jpg` — 1400×1400 · 1:1

> A single tall wine bottle of pale straw-gold white wine, standing centered on a
> smooth cream surface against a soft cream backdrop. Clean studio product
> photography, one large soft light from the upper left, gentle gradient shadow
> falling to the lower right. Minimal, elegant, generous space around the bottle.
> Square composition. Unlabeled clear glass bottle.

- **Must match image 6.** Same light direction, same shadow length, same
  backdrop, same bottle scale. They sit side by side and any mismatch is
  obvious. If your tool supports seeds, reuse the seed from image 6 and change
  only the wine color.

---

## 8. `locator.jpg` — 1400×960 · ≈16:11

> A bottle of pale rosé and two poured glasses on a table beside a resort pool
> in the late afternoon. Palm shadows across pale stone, turquoise water soft
> and out of focus behind. Warm Florida light, relaxed and expensive. No people
> in the foreground.

- Florida rather than France on purpose. This section is about where to buy it
  locally, and their venues are Florida resorts.

---

## 9. `giving.jpg` — 1400×930 · 3:2

> A long outdoor table set for a gathering at golden hour, glasses of rosé
> poured, guests seated in soft focus with no faces clearly readable. Warm
> string lights overhead, linen, greenery. Candid documentary feel, generous and
> communal, not staged.

- Faces soft or turned. It is a placeholder, and identifiable strangers in a
  charity section would be the wrong signal.

---

## Aspect ratio cheat sheet

| File | Ratio | Midjourney | Pixels |
|---|---|---|---|
| `hero` | 12:7 | `--ar 12:7` | 2400×1400 |
| `routes-wines` | 4:3 | `--ar 4:3` | 1200×900 |
| `routes-story` | 4:3 | `--ar 4:3` | 1200×900 |
| `routes-society` | 4:3 | `--ar 4:3` | 1200×900 |
| `founder` | 4:5 | `--ar 4:5` | 1200×1500 |
| `bottle-rose` | 1:1 | `--ar 1:1` | 1400×1400 |
| `bottle-blanc` | 1:1 | `--ar 1:1` | 1400×1400 |
| `locator` | 16:11 | `--ar 16:11` | 1400×960 |
| `giving` | 3:2 | `--ar 3:2` | 1400×930 |

Anything close to the ratio works — the layout crops with `object-fit: cover`.
To nudge a crop, add a `--pos` value to that slot in `index.html`, for example
`style="--pos:center 30%"`.

---

## Keeping the nine consistent

They appear on one page and will be compared to each other.

- **One light direction throughout.** Every prompt above uses light from the
  left. Keep it.
- **Same time of day.** Late afternoon or golden hour, except `routes-society`
  which is deliberately dusk.
- **Reuse seeds** where your tool allows, especially for the two bottles.
- **Grade them together at the end**, not one at a time. Even a light matching
  pass in Lightroom or Photos will do more for coherence than better prompts.
- **Generate four of each and pick**, rather than iterating on one.

---

## Before they go in front of the client

These are placeholders. Say so out loud in the meeting — a client who thinks
generated imagery is the plan will react badly, and a client who understands it
is scaffolding will focus on the layout, which is the point.

The real photography is quoted in Section 7 of the proposal.


---

## What is currently in place, and what still needs a camera

| File | Currently | Status |
|---|---|---|
| `hero.jpg` | Bottle on a stone wall, Provence at sunset | Generated — usable for the concept |
| `routes-wines.jpg` | Both bottles with apricots and blossom | Generated |
| `routes-story.jpg` | Stone farmhouse above the vines | Generated |
| `routes-society.jpg` | Candlelit table at dusk | Generated |
| `founder.jpg` | Kavita with both bottles | **Real photograph** |
| `bottle-rose.jpg` | Rosé on cream, studio | Real label, correct |
| `bottle-blanc.jpg` | Blanc on cream, studio | Real label, correct |
| `locator.jpg` | Poolside with two glasses | Generated |
| `giving.jpg` | Long table at golden hour | Generated |

**Before this goes anywhere beyond a concept review**, the seven generated
images should be replaced with real photography. They are convincing at a
glance, but they depict a domaine, a landscape and events that are not
Sip Channé's, and using them as if they were is a different thing entirely from
using them to demonstrate a layout.

Real photography is quoted in Section 7 of the proposal.
