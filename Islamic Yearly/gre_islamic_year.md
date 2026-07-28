# Gull Real Estate & Builders - Islamic New Year Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Islamic / Hijri New Year** (1st Muharram). It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be published with visual variety year over year.

All posts are event-oriented, fresh, hopeful, and renewing. The Hijri New Year is a fresh start — a moment to wish peace, blessings, and renewal. The visual register is "new beginning" rather than "celebration" or "somber reflection." The post should always feel like the first light of a new day.

---

## 1. Core Identity (Carried Over From Main Spec)

### Company Information
| Element | Value | Implementation |
|---------|-------|----------------|
| Company Name | Gull Real Estate & Builders | Stylized text overlay or subtle wordmark |
| Contact Number | 0314 9393930 | SVG phone icon + number, bottom-left of CTA bar |
| Website | gullrealestate.github.io | SVG globe icon + URL, bottom-right of CTA bar |
| Logo | User-provided | Harmonized with the post's dominant palette |

### Logo Rules (Strict)
```
RULE: DO NOT generate any bird, nest, or decorative emblem
RULE: Reserve a clean empty space at the TOP-LEFT corner for the logo
RULE: The actual logo will be provided by the user at generation time
RULE: DO NOT place any graphic, icon, or placeholder in the logo space
RULE: The image generator must recolor/tint the uploaded logo so its
      colors harmonize with the dominant palette of the post
RULE: Logo color adaptation must feel natural — not forced or clashing
RULE: Minimum padding around logo space: 8% of post width on all sides
RULE: The logo is the FIRST thing the eye should find, after the title
```

### Prohibited Elements (All Posts)
```
❌ NO faces or identifiable people
❌ NO mosques with worshippers or prayer scenes
❌ NO religious text (Quran verses, Hadith, Arabic script as content)
❌ NO political party logos or symbols
❌ NO flags of other nations
❌ NO weapons, violence, or aggressive imagery
❌ NO nudity or suggestive content
❌ NO bird, nest, or decorative emblem in or near the logo space
❌ NO excessive gold or gaudy presentation
❌ NO celebration elements (confetti, balloons, fireworks, party hats)
❌ NO low-quality, pixelated, or busy backgrounds
❌ NO content that could be read as inflammatory or disrespectful
```

---

## 2. Strict Design Language (Applies to All 10 Layouts)

This is the spine of the spec. The 10 layouts all live inside these rules.

### 2.1 Color Discipline
```
- Maximum THREE colors per post: Primary / Secondary / Accent
- No fourth color. No gradients that introduce a new hue.
- Gradient stops are allowed ONLY between Primary and Secondary.
- The Accent color is reserved for: CTA icons, the company wordmark,
  and a single decorative micro-element. Never used for large fills.
- Backgrounds: Solid, gentle duotone gradient, or pattern at ≤15% opacity
- Text contrast: AAA where possible, AA at minimum
```

### 2.2 Typography Discipline
```
- Use EXACTLY TWO typefaces per post:
  * One display face (the EVENT TITLE)
  * One body face (subtitle, message, CTA)
- The display face must be either a refined serif (Didone, modern
  transitional, or a calligraphic Latin) or a clean modern sans.
  No display face mixing. No script faces mixed with serifs.
- The body face is always a clean, highly legible sans-serif.
- Type sizes (as % of post height):
  * Event Title: 9-11%
  * Subtitle / Greeting: 4-5%
  * Wish Message: 3-4%
  * CTA: 3%
- Letter spacing on the title: +1% to +3% (slightly expanded)
- Title and message must remain readable at 200×200 thumbnail size
```

### 2.3 Composition Discipline
```
- One focal point only. The eye should land on it within 0.5 seconds.
- Grid: 12-column virtual grid; elements snap to thirds or halves.
- Negative space: minimum 12% of the post must be empty breathing room.
- The CTA bar always sits in the bottom 12% of the post.
- The logo space always sits in the top-left 18% × 18% box.
- The event title is always centered on the dominant axis
  (vertical center for centered layouts, optical center for off-center).
- RESET RULE: when possible, the eye should travel from a calm
  "starting point" toward a single bright moment of renewal. Avoid
  heavy, dense, or overly decorated compositions.
- No element may overlap the logo space or the CTA bar.
```

### 2.4 Decorative Discipline
```
- Decorative elements are SYMBOLIC, never literal.
- Allowed motifs: crescent, star, sunrise, calendar/clock (abstract),
  stylized arch (threshold), sprouting plant, fresh leaf, water drop,
  layered rings (year's cycle), single gold beam, geometric pattern.
- No more than TWO decorative motifs per post. Typically ONE hero
  motif and ONE supporting micro-element.
- Decorative opacity: hero motif 60-100%, micro-element 20-40%.
- Patterns are reserved for backgrounds only, at ≤15% opacity.
- No decorative element may be placed inside the logo space.
- No firework bursts, party confetti, or celebration explosions.
  Freshness, not festivity.
```

### 2.5 Mood Discipline
```
The Islamic New Year is a moment of fresh start, hope, and renewal.

ALLOWED MOODS:
  - Fresh
  - Hopeful
  - Renewed
  - Optimistic
  - Calm
  - Reflective (in a forward-looking, not backward-looking, way)

NOT ALLOWED MOODS (would betray the spirit of the day):
  - Celebratory (this is NOT Eid)
  - Festive with confetti/balloons
  - Loud
  - Partying
  - Decorative-for-its-own-sake
  - Somber (it is not a mourning occasion)

If a layout choice starts to read as "Eid card", "birthday card",
or "party invite", stop. The Hijri New Year is a quiet, hopeful
turning of the page, not a party.
```

### 2.6 Aspect Ratio & Resolution
```
- All layouts default to 1:1 (1080 × 1080 px)
- Layouts marked [VERTICAL] use 4:5 (1080 × 1350 px)
- Layouts marked [STORY] use 9:16 (1080 × 1920 px) for IG/FB stories
- Resolution: minimum 1080px on the short edge
- Color mode: RGB
- Format: PNG (preferred) or JPG
```

---

## 3. The 10 Islamic New Year Layouts

Each layout is a complete design system: visual theme, color logic, type logic, composition grid, decorative element, and a worked full prompt. Pick the layout that matches this year's mood, then run the prompt.

### Layout 01 — Dawn of the Year
**Mood:** Fresh, hopeful, the first light
**Type:** Centered, in the calm below
**Aspect:** 1:1

**Visual Theme:**
- A soft sunrise gradient at the lower third of the post
- Above the horizon: a fresh teal sky, calm
- A small new crescent rising in the upper third
- Type sits in the calm below the horizon
- A few small gold stars in the upper sky as micro-elements

**Color Logic:**
- Primary: fresh teal (sky)
- Secondary: warm gold (horizon glow, crescent, text)
- Accent: deep navy (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│              ☾                      │
│   ✦                       ✦         │
│                                     │
│                                     │
│   ░░░░ horizon line ░░░             │
│   ▓▓▓ dawn glow ▓▓▓                 │
│                                     │
│       "Islamic New Year Mubarak"    │
│       "A year of blessings          │
│        and peace"                   │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Dawn of the Year
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0D9488 (fresh teal — sky)
- Secondary: #D4AF37 (warm gold — horizon glow, crescent, text)
- Accent: #1A365D (deep navy — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- Soft sunrise gradient at the lower third of the post
- Above the horizon: a fresh teal sky, calm
- A small new crescent rising in the upper third
- A few small gold stars in the upper sky (3-5 max)
- ONE focal motif (the rising crescent) + small supporting stars

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Horizon: at the lower third
- Crescent: upper third, slightly off-center
- Type: below the horizon, centered, in the calm
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- Fresh, hopeful mood — not festive, not somber
- ONE focal motif (the rising crescent)
- Maximum one decorative motif + small supporting stars

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 02 — Crescent & Calendar
**Mood:** Marking time, abstract, ordered
**Type:** Centered, paired with the calendar motif
**Aspect:** 1:1

**Visual Theme:**
- A stylized circular calendar motif (concentric rings + tick marks) sits
  in the upper half
- A small new crescent overlaps the calendar as a "first day" marker
- Type sits in the lower half, beneath the motif
- Background: fresh teal, calm
- A few small gold stars as supporting micro-elements

**Color Logic:**
- Primary: fresh teal (background)
- Secondary: warm gold (calendar motif, crescent, text)
- Accent: deep navy (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│         ╱─────╲       ☾             │
│       ╱  tick  ╲      (overlap)     │
│      │   marks  │                    │
│       ╲       ╱                      │
│         ╲___╱                        │
│                                     │
│                                     │
│       "Islamic New Year Mubarak"    │
│       "Beginning of the Hijri year" │
│                                     │
│       "A year of blessings          │
│        and peace"                   │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Crescent & Calendar
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0D9488 (fresh teal — background)
- Secondary: #D4AF37 (warm gold — calendar motif, crescent, text)
- Accent: #1A365D (deep navy — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A stylized circular calendar motif in the upper half:
  concentric rings with 12 tick marks (abstract, not literal clock face)
- A small new crescent overlapping the calendar as a "first day" marker
- A few small gold stars as supporting micro-elements (3-5 max)
- Background: solid fresh teal
- ONE focal motif (the calendar + crescent) — a single time-marking idea

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Calendar motif: upper half, ~40% of post width
- Crescent: overlapping the calendar's right edge
- Type: lower half, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- Calendar motif must be ABSTRACT — concentric rings with tick marks,
  NOT a literal clock face with numbers/hands
- NO Western numerals, NO clock hands, NO date numbers
- ONE focal motif (the calendar + crescent)
- Maximum one decorative motif + small supporting stars

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 03 — Open Gate
**Mood:** Threshold, fresh start, hopeful
**Type:** Centered, inside the arch
**Aspect:** 1:1

**Visual Theme:**
- A stylized pointed arch (open gate) frames the post's center
- Inside the arch: a soft gold-to-teal gradient suggesting "stepping into"
- Type sits in the arch, in the gradient
- Background outside the arch: deep navy
- A small crescent sits at the arch's apex as a micro-element

**Color Logic:**
- Primary: deep navy (outside the arch)
- Secondary: warm gold (arch line, gradient inside, text)
- Accent: fresh teal (gradient inside the arch, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│            ╱    ╲                    │
│           │░░░░░│                   │
│           │░░░░░│ "Islamic New      │
│           │░░░░░│  Year Mubarak"     │
│           │░░░░░│                   │
│           │░░░░░│ "Beginning of     │
│           │░░░░░│  the Hijri year"  │
│           ╲░░░░╱                    │
│            ╲____╱ ☾                  │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Open Gate
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A365D (deep navy — outside the arch)
- Secondary: #D4AF37 (warm gold — arch line, gradient inside, text)
- Accent: #0D9488 (fresh teal — gradient inside the arch, CTA icons)

VISUAL ELEMENTS:
- A stylized pointed arch (open gate) framing the post's center
- Inside the arch: a soft gold-to-teal gradient suggesting "stepping into"
- The arch's outline is a thin gold line
- Type sits in the arch, in the gradient
- Background outside the arch: solid deep navy
- A small crescent at the arch's apex as a micro-element
- ONE focal motif (the arch) + ONE micro (crescent)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Arch: optically centered, ~55% of post width, ~70% of post height
- Gradient: gold at the top, teal at the bottom
- Type: centered inside the arch
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- The arch reads as a THRESHOLD to a new year, not a doorway to a
  building. Abstract, not architectural.
- ONE focal motif (the arch) + ONE micro (crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 04 — Seedling
**Mood:** Growth, freshness, organic
**Type:** Centered, around or above the sprout
**Aspect:** 1:1

**Visual Theme:**
- A single stylized sprouting plant (one stem, two small leaves) sits
  in the lower-center as the hero motif
- The plant is rendered as gold line work on the teal background
- A small new crescent floats above the plant like a "blessing"
- Type sits in the upper half, above the plant
- Background: fresh teal, calm
- The composition reads as growth, not decoration

**Color Logic:**
- Primary: fresh teal (background)
- Secondary: warm gold (plant, crescent, text)
- Accent: deep navy (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│              ☾                      │
│                                     │
│       "Islamic New Year Mubarak"    │
│       "A year of blessings          │
│        and peace"                   │
│                                     │
│            │╲ │╱                    │
│            │ ╳│                     │
│            │╱ │╲                    │
│            │   │                    │
│            ╲___╱                    │
│           (sprout)                  │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Seedling
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0D9488 (fresh teal — background)
- Secondary: #D4AF37 (warm gold — plant, crescent, text)
- Accent: #1A365D (deep navy — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A single stylized sprouting plant in the lower-center
- Plant: one stem, two small leaves, gold line work
- A small new crescent floats above the plant like a "blessing"
- Type sits in the upper half, above the plant
- Background: solid fresh teal
- ONE focal motif (the sprout) + ONE micro (crescent)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Sprout: lower-center, ~25% of post height
- Crescent: above the sprout
- Type: upper half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- The plant must be STYLIZED and ABSTRACT — gold line work, not
  photorealistic. A simple sprout, not a full plant or tree.
- ONE focal motif (the sprout) + ONE micro (crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 05 — Constellation Reset
**Mood:** Ordered, fresh, hopeful
**Type:** Centered, in a clear negative-space pocket
**Aspect:** 1:1

**Visual Theme:**
- A fresh, ordered star field fills the background (~25-35 stars)
- Stars are arranged in a subtle but visible ORDER (gentle grid or
  curved arc), not random scatter
- A few stars are slightly larger, forming a faint pattern
- A small new crescent anchors one corner
- Type sits in a clear, unstarred pocket in the center

**Color Logic:**
- Primary: fresh teal (background)
- Secondary: warm gold (stars, text)
- Accent: deep navy (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]   ✦         ✦                │
│        ✦               ✦            │
│     ✦      "Islamic New   ✦         │
│            Year Mubarak"            │
│   ✦                                   │
│        "A year of blessings          │
│          and peace"                  │
│     ☾   ✦          ✦                │
│        ✦        ✦                    │
│           ✦                          │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Constellation Reset
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0D9488 (fresh teal — background)
- Secondary: #D4AF37 (warm gold — stars, text)
- Accent: #1A365D (deep navy — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A fresh, ordered star field fills the background (~25-35 stars)
- Stars arranged in a SUBTLE order (gentle grid or curved arc), not
  random scatter
- A few stars slightly larger, forming a faint pattern
- A small new crescent anchors one corner (lower-left or lower-right)
- Type sits in a clear, unstarred pocket in the center
- ONE focal motif (the ordered star field) + ONE micro (crescent)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Star field: distributed, but ordered (not random scatter)
- Type pocket: clear, unstarred, in the center
- Crescent: in one corner
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- Stars must be ORDERED, not chaotic. The composition feels fresh
  and reset, not random.
- ONE focal motif (the star field) + ONE micro (crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 06 — Geometric Renewal
**Mood:** Ordered, cyclic, eternal
**Type:** Centered inside the rings
**Aspect:** 1:1

**Visual Theme:**
- A series of concentric rings (4-5 rings) sits in the post's center
- The rings are gold line work, each at a different radius
- A small new crescent sits at the top of the outermost ring (the
  "starting point" of the cycle)
- Type sits in the clear center inside the innermost ring
- Background: fresh teal, calm

**Color Logic:**
- Primary: fresh teal (background)
- Secondary: warm gold (rings, crescent, text)
- Accent: deep navy (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│             ☾                       │
│        ╭─────────╮                  │
│       │  ╭─────╮  │                 │
│      │  │  ╭──╮  │  │                │
│      │  │ │ TY│ │  │                │
│      │  │  ╰──╯  │  │                │
│       │  ╰─────╯  │                 │
│        ╰─────────╯                  │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Geometric Renewal
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0D9488 (fresh teal — background)
- Secondary: #D4AF37 (warm gold — rings, crescent, text)
- Accent: #1A365D (deep navy — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- 4-5 concentric rings sit in the post's center
- The rings are gold line work at varying radii
- A small new crescent sits at the top of the outermost ring
  (the "starting point" of the cycle)
- Type sits in the clear center inside the innermost ring
- Background: solid fresh teal
- ONE focal motif (the rings) + ONE micro (crescent)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Rings: centered, ~70% of post width
- Crescent: at the top of the outermost ring
- Type: in the innermost ring's clear center
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- The rings read as a CYCLE of time, not a target, not a planet
- The crescent sits at the TOP of the ring (not orbiting, not below)
- ONE focal motif (the rings) + ONE micro (crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 07 — Calligraphy of Beginning
**Mood:** Type-driven, hopeful, intimate
**Type:** Massive, the design itself
**Aspect:** 1:1

**Visual Theme:**
- The event title is THE design — rendered in a calligraphic or display
  serif at huge scale
- Title appears to glow softly, as if written in gold light
- A single hairline gold rule separates title from message
- Background: fresh teal, calm and even
- No other ornament

**Color Logic:**
- Primary: fresh teal (background)
- Secondary: warm gold (text)
- Accent: deep navy (hairline rule, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│     I S L A M I C   N E W   Y E A R │
│              M U B A R A K          │
│         ──────────── (rule)         │
│         "A year of blessings        │
│          and peace"                 │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Calligraphy of Beginning
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0D9488 (fresh teal — background)
- Secondary: #D4AF37 (warm gold — text)
- Accent: #1A365D (deep navy — hairline rule, CTA icons)

VISUAL ELEMENTS:
- The event title is THE design — calligraphic or display serif
  at massive scale (~12-14% of post height per line)
- Title appears to glow softly, as if written in gold light
- ONE single hairline gold rule in accent color, ~30% of post width
- Background: solid primary, no pattern, no other ornament
- NO second decorative motif. The title is the art.

TYPOGRAPHY:
- Display face: calligraphic Latin OR Didone serif
- Body face: clean sans-serif
- Title: 12-14% of post height, multi-line if needed, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Title: vertically and horizontally centered, dominates the frame
- Negative space: minimum 18% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- ONE focal point (the title) — type-driven
- Maximum one decorative element (the hairline rule)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + accent palette naturally.
```

---

### Layout 08 — First Light Beam
**Mood:** Awestruck, fresh, single
**Type:** Centered, in the calm below the beam
**Aspect:** 1:1

**Visual Theme:**
- A single soft gold light beam descends from the upper-center
- The beam is the "first light" of the new year
- The beam's center is brightest; edges fade to teal
- Type sits in the lower half, in the calm
- Background: fresh teal, slightly deeper at the top
- A small new crescent sits in the upper sky as a micro-element

**Color Logic:**
- Primary: fresh teal (background)
- Secondary: warm gold (beam, crescent, text)
- Accent: deep navy (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│              ☾                      │
│            ╲   │   ╱                │
│             ╲  │  ╱                 │
│              ╲ │ ╱                  │
│               ╲│╱                   │
│               ╱│╲                   │
│              ╱ │ ╲                  │
│             ╱  │  ╲                 │
│            ╱   │   ╲                │
│                                     │
│       "Islamic New Year Mubarak"    │
│       "A year of blessings          │
│        and peace"                   │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: First Light Beam
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0D9488 (fresh teal — background)
- Secondary: #D4AF37 (warm gold — beam, crescent, text)
- Accent: #1A365D (deep navy — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A single soft gold light beam descending from the upper-center
- The beam is the "first light" of the new year
- The beam's center is brightest; edges fade to teal
- Type sits in the lower half, in the calm
- Background: fresh teal, slightly deeper at the top
- A small new crescent in the upper sky as a micro-element
- ONE focal motif (the beam) + ONE micro (crescent)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Beam: upper-center, descending, soft and wide
- Type: lower half, centered, in the calm
- Crescent: in the upper sky
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- The beam must read as FIRST LIGHT — soft, hopeful, single
- Not a spotlight, not a sun-burst, not aggressive
- ONE focal motif (the beam) + ONE micro (crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 09 — Orbit Reset
**Mood:** Cosmic, ordered, time renewed
**Type:** Centered, in a calm pocket
**Aspect:** 1:1

**Visual Theme:**
- A central gold star sits at the post's center as a "fixed point"
- 3-4 concentric gold arcs orbit the star at different radii
- The arcs are thin, elegant, and partial (not full circles)
- A small new crescent sits at the top of the outermost arc
- Type sits in a calm negative space pocket in the lower half
- Background: fresh teal, calm

**Color Logic:**
- Primary: fresh teal (background)
- Secondary: warm gold (star, arcs, crescent, text)
- Accent: deep navy (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾                │
│       ╱─────────╲                    │
│      │   ╱─────╲  │                  │
│      │  │  ╱─╲  │ │                  │
│      │  │ │✦│  │ │                  │
│      │  │  ╲─╱  │ │                  │
│      │   ╲─────╱  │                  │
│       ╲─────────╱                    │
│                                     │
│       "Islamic New Year Mubarak"    │
│       "A year of blessings          │
│        and peace"                   │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 09:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Orbit Reset
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0D9488 (fresh teal — background)
- Secondary: #D4AF37 (warm gold — star, arcs, crescent, text)
- Accent: #1A365D (deep navy — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A central gold star at the post's center as a "fixed point"
- 3-4 concentric gold arcs orbiting the star at different radii
- The arcs are THIN, ELEGANT, and PARTIAL (not full circles)
- A small new crescent at the top of the outermost arc
- Type sits in a calm negative space pocket in the lower half
- Background: solid fresh teal
- ONE focal motif (the orbiting system) — a single ordered idea

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Star: center of the post
- Arcs: concentric, varying radii, partial (broken circles)
- Crescent: at the top of the outermost arc
- Type: lower half, centered, in a calm pocket
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- The arcs must read as TIME'S CYCLE, not a planetary diagram or
  astronomical chart. Pure ornament, not a model.
- ONE focal motif (the orbiting system)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 10 — Stamped
**Mood:** Marked, official-feeling, refined
**Type:** Centered, around the seal
**Aspect:** 1:1

**Visual Theme:**
- A stylized circular seal/emblem sits in the post's center
- The seal is rendered as a gold geometric medallion (line work, not
  filled) with a small new crescent at its center
- A thin gold outer ring frames the seal
- Type sits inside the seal, around the crescent
- Background: fresh teal, calm
- The seal reads as a "mark of the new year" — formal but not corporate

**Color Logic:**
- Primary: fresh teal (background)
- Secondary: warm gold (seal, ring, crescent, text)
- Accent: deep navy (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│         ╭───────────╮               │
│       ╱               ╲             │
│      │  "Islamic New    │            │
│      │   Year Mubarak"  │           │
│      │       ☾          │           │
│      │  "A year of      │           │
│      │   blessings      │           │
│      │   and peace"     │           │
│       ╲               ╱             │
│         ╰───────────╯               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Islamic New Year Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Stamped
EVENT TITLE: "Islamic New Year Mubarak"
GREETING SUBTITLE: "Beginning of the Hijri year"
WISH MESSAGE: "A year of blessings and peace"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0D9488 (fresh teal — background)
- Secondary: #D4AF37 (warm gold — seal, ring, crescent, text)
- Accent: #1A365D (deep navy — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A stylized circular seal/emblem in the post's center
- The seal is gold geometric line work (NOT filled, NOT a corporate logo)
- A thin gold outer ring frames the seal
- A small new crescent sits at the seal's center
- Type wraps around the crescent, inside the seal
- Background: solid fresh teal
- ONE focal motif (the seal)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 8% of post height, centered, secondary color
- Subtitle: 3.5% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Seal: optically centered, ~70% of post width
- Outer ring: ~75% of post width
- Crescent: at the seal's center
- Type: wraps around the crescent, inside the seal
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- The seal must be a SIMPLE GEOMETRIC MEDALLION — not a corporate
  logo, not an official government mark, not a wax seal with ribbons
- Line work only, not filled
- The seal reads as a "mark of the new year" — formal but decorative,
  not authoritative or official-looking
- ONE focal motif (the seal)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given year's Hijri New Year post.

| Year's Tone | Recommended Layouts |
|-------------|---------------------|
| Default / classic | 01 Dawn of the Year, 05 Constellation Reset |
| Marking time | 02 Crescent & Calendar, 06 Geometric Renewal |
| Threshold | 03 Open Gate |
| Growth-oriented | 04 Seedling |
| Type-driven, brand-led | 07 Calligraphy of Beginning |
| Awestruck, single moment | 08 First Light Beam |
| Cosmic, ordered | 09 Orbit Reset |
| Refined, formal | 10 Stamped |
| Default rotation | 01, 06, 07, 09 (one of these per cycle) |

**Recommended rotation pattern (4 years):**
- Year 1: Layout 01 — Dawn of the Year
- Year 2: Layout 06 — Geometric Renewal
- Year 3: Layout 07 — Calligraphy of Beginning
- Year 4: Layout 09 — Orbit Reset

This guarantees 4 visually distinct posts over a 4-year cycle, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_islamic_new_year_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_islamic_new_year_01_20260617_v1.png   (Layout 01)
gull_real_estate_builders_islamic_new_year_06_20260617_v1.png   (Layout 06)
gull_real_estate_builders_islamic_new_year_09_20260617_v1.png   (Layout 09)
```

---

## 6. CTA Bar Specification (Identical Across All 10 Layouts)

The CTA bar is the ONE element that never changes. It anchors brand recognition across all the visual variety above.

```
HEIGHT: bottom 12% of the post
GROUND COLOR: primary color of the selected layout
LEFT SIDE: SVG phone icon (stroke: secondary color) + "0314 9393930" (body face)
RIGHT SIDE: SVG globe icon (stroke: secondary color) + "gullrealestate.github.io" (body face)
DIVIDER: thin vertical line in secondary color, 30% opacity, centered
PADDING: equal left/right padding (8% of post width)
ICON SIZE: 24x24 logical units, scalable
TEXT SIZE: 3% of post height
TEXT COLOR: secondary color
```

### Phone Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[SECONDARY_COLOR]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
</svg>
```

### Globe Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[SECONDARY_COLOR]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <circle cx="12" cy="12" r="10"/>
  <line x1="2" y1="12" x2="22" y2="12"/>
  <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/>
</svg>
```

---

## 7. Pre-Generation Checklist

Use this for every Islamic New Year post.

```
□ Layout number selected (01-10)
□ Color palette confirmed (3 colors, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-1 micro = max 2)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary ground, secondary icons
□ Aspect ratio: 1:1 default
□ Reset rule: composition feels FRESH, not heavy or dense
□ Mood check: fresh/hopeful/renewed/optimistic/calm
□ Prohibited elements reviewed (faces, prayer scenes, religious text,
  celebration elements, party imagery, etc.)
□ Filename follows convention
```

## 8. Post-Generation Checklist

```
□ No faces or identifiable people
□ No mosque with worshippers or prayer scenes
□ No religious text, verses, or Arabic script
□ No political party logos or symbols
□ No celebration elements (confetti, balloons, fireworks, party hats)
□ No bird, nest, or emblem in or near the logo space
□ Logo space is clean and properly reserved
□ User-uploaded logo colors harmonize with the post's palette
□ Text is readable at 200×200 thumbnail size
□ Colors match the selected 3-color palette (no fourth color crept in)
□ Only two typefaces are used
□ Maximum two decorative motifs (one hero + optional micro)
□ CTA bar matches Section 6 spec exactly
□ Aspect ratio matches layout choice
□ Mood is fresh and hopeful, never festive (no Eid feel) or somber
□ No party imagery — this is a quiet turning of the page
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Islamic New Year-Specific)

The Islamic / Hijri New Year (1st Muharram) marks the beginning of the new lunar year. It is a moment of quiet renewal, hope, and reflection on the year ahead — it is NOT an Eid and NOT a party.

- **No celebration imagery.** No confetti, no balloons, no fireworks, no party hats, no festive explosions. This is a turning of the page, not a party.
- **No Eid-style festivity.** The visual register is closer to "first light of a new day" than "festival." A post that reads as "Eid card" has missed the mark.
- **No mourning imagery either.** The Hijri New Year is a hopeful, forward-looking moment. It is not a somber occasion.
- **No worship scenes.** The day is honored in the greeting, not depicted literally.
- **No religious text.** A greeting in English is fine. Verses and Arabic script are not used.
- **No mosque imagery with people.** A stylized arch or geometric mark is fine. A mosque with worshippers is not.
- **The new crescent is the recurring motif.** It is the first visible sign of each new lunar month, and it marks the new year. Use it tastefully, not as a logo replacement.
- **Calendar/clock motifs stay abstract.** Concentric rings and tick marks are fine. Real clock faces with numbers and hands are not — they read as Western/secular timekeeping, which is not the right register.

The single most important rule for this spec:
> **Fresh, not festive. Hopeful, not heavy. A new page turning, not a party starting.**

When in doubt: **subtract, don't add.** A simpler post is more respectful than a busier one. If a layout choice starts to read as "Eid card", "birthday card", or "party invite", stop.

---

**Document Version:** 1.0 - Islamic / Hijri New Year Post Specification
**Last Updated:** July 18, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Islamic / Hijri New Year annual posts
