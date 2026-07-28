# Gull Real Estate & Builders - Shab-e-Barat Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Shab-e-Barat** (15th Shaban — the Night of Forgiveness and Blessings). It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be published with visual variety year over year.

All posts are event-oriented, mystical, ethereal, and contemplative. Shab-e-Barat is a sacred night of reflection and prayer — never a celebration. The visual register is closer to "moonlit stillness" than "festive gathering."

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
❌ NO celebration elements (confetti, balloons, fireworks)
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
- No element may overlap the logo space or the CTA bar.
```

### 2.4 Decorative Discipline
```
- Decorative elements are SYMBOLIC, never literal.
- Allowed motifs: crescent, star, full moon, lantern (chiragh),
  arch/mihrab, geometric pattern, constellation, mist/fog, water,
  arabesque window (jali), constellation lines.
- No more than TWO decorative motifs per post. Typically ONE hero
  motif and ONE supporting micro-element.
- Decorative opacity: hero motif 60-100%, micro-element 20-40%.
- Patterns are reserved for backgrounds only, at ≤15% opacity.
- No decorative element may be placed inside the logo space.
- Lanterns, when used, must NOT show a literal flame. Use a glow gradient.
- Full moons, when used, must read as serene and still — not dramatic.
```

### 2.5 Mood Discipline
```
Shab-e-Barat is a mystical, ethereal, sacred night.

ALLOWED MOODS:
  - Mystical
  - Ethereal
  - Contemplative
  - Reverent
  - Peaceful
  - Hopeful (for forgiveness)

NOT ALLOWED MOODS (would betray the spirit of the night):
  - Celebratory
  - Festive
  - Bright
  - Loud
  - Decorative-for-its-own-sake
  - Horror-adjacent (no skulls, no dark symbolism beyond color)

If a layout choice starts to read as "Halloween card" or "Eid card",
stop. Shab-e-Barat is a night of stillness, not spectacle.
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

## 3. The 10 Shab-e-Barat Layouts

Each layout is a complete design system: visual theme, color logic, type logic, composition grid, decorative element, and a worked full prompt. Pick the layout that matches this year's mood, then run the prompt.

### Layout 01 — Full Moon Halo
**Mood:** Serene, vast, still
**Type:** Centered, hierarchical below the moon
**Aspect:** 1:1

**Visual Theme:**
- A large, soft-edged full moon occupies the upper-center as the hero focal point
- A faint silver halo radiates from the moon
- Type sits in the lower third, in the dark sky below the moon
- Background: deep purple-to-near-black vertical gradient
- A few scattered silver stars in the corners as micro-elements

**Color Logic:**
- Primary: deep purple (background)
- Secondary: pale silver (moon, text)
- Accent: moonlight blue (halo, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│        ✦                    ✦       │
│             ╭─────────╮             │
│            │           │            │
│            │   MOON   │            │
│            │  + halo  │            │
│            │           │            │
│             ╰─────────╯             │
│                                     │
│          "Shab-e-Barat"             │
│          "Mubarak"                  │
│                                     │
│       "May Allah accept             │
│        our prayers"                 │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Full Moon Halo
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — background)
- Secondary: #D9D6E0 (pale silver — moon, text)
- Accent: #6B8BC9 (moonlight blue — halo, CTA icons)

VISUAL ELEMENTS:
- Large soft-edged full moon in the upper-center
- Faint silver halo radiating from the moon
- Background: deep purple-to-near-black vertical gradient
- A few scattered silver stars in the corners (4-6 max)
- ONE focal motif (the moon) + tiny supporting stars

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Moon: upper-center, ~30% of post width
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- Calm, mystical mood — not festive
- ONE focal point (the moon)
- Maximum one decorative motif (moon + corner stars as one field)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 02 — Lantern Procession
**Mood:** Warm, intimate, communal quiet
**Type:** Centered, above the lanterns
**Aspect:** 1:1

**Visual Theme:**
- Three traditional lanterns (chiragh) sit in a row along the lower third
- Each lantern has a soft inner glow (no literal flame)
- Type sits in the upper two-thirds, in the dark sky
- Background: deep purple gradient, calm
- A single crescent in the upper third as a micro-element

**Color Logic:**
- Primary: deep purple (background)
- Secondary: warm silver/cream (text)
- Accent: moonlight blue (lantern glow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│              ☾                      │
│                                     │
│       "Shab-e-Barat Mubarak"        │
│       "Night of forgiveness         │
│        and blessings"               │
│                                     │
│   ┌─────┐   ┌─────┐   ┌─────┐       │
│   │ glow│   │ glow│   │ glow│       │
│   │     │   │     │   │     │       │
│   └─────┘   └─────┘   └─────┘       │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Lantern Procession
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — background)
- Secondary: #E8E2D5 (warm cream-silver — text, lantern body)
- Accent: #6B8BC9 (moonlight blue — lantern glow, CTA icons)

VISUAL ELEMENTS:
- Three traditional lanterns (chiragh) in a row along the lower third
- Each lantern has a soft inner glow (no literal flame)
- Type sits in the upper two-thirds
- Background: deep purple gradient
- A single crescent in the upper third as a micro-element

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Lanterns: lower third, evenly spaced, equal sizes
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the lantern row)
- Lanterns must NOT show a literal flame — use glow gradient only
- Maximum one decorative motif (lanterns) + one micro (crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 03 — Reflection Pool
**Mood:** Still, mirrored, contemplative
**Type:** Centered, hovering over the horizon
**Aspect:** [VERTICAL] 4:5 (1080 × 1350)

**Visual Theme:**
- The post is split horizontally at the mid-line
- Top half: deep purple night sky with a full moon
- Bottom half: the same moon mirrored in a calm water surface
- A thin silver horizon line separates sky and water
- Type sits across the horizon, hovering

**Color Logic:**
- Primary: deep purple (sky and water)
- Secondary: pale silver (moon, text, horizon)
- Accent: moonlight blue (water ripples, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│        ╭─────────╮                  │
│       │   MOON   │                  │
│        ╰─────────╯                  │
│                                     │
│   "Shab-e-Barat Mubarak"            │
│   "Night of forgiveness             │
│    and blessings"                   │
│   ─────────────────── (horizon)     │
│                                     │
│        ╭─────────╮                  │
│       │  MOON    │                  │
│       │  (mirror)│                  │
│        ╰─────────╯                  │
│       (water ripples)               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 4:5 (1080x1350) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Reflection Pool [VERTICAL]
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — sky and water)
- Secondary: #D9D6E0 (pale silver — moon, text, horizon line)
- Accent: #6B8BC9 (moonlight blue — water ripples, CTA icons)

VISUAL ELEMENTS:
- Post split horizontally at the mid-line
- Top half: deep purple night sky with a full moon
- Bottom half: the same moon mirrored in a calm water surface
- A thin silver horizon line separates sky and water
- Subtle water ripples below the mirrored moon
- ONE focal motif (the moon + its mirror) — a single visual idea

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Moon: upper-center, ~25% of post width
- Mirrored moon: lower-center, matching size
- Type: hovers across the horizon, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the moon + mirror)
- The mirrored moon must read as STILL WATER, not choppy waves

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 04 — Starlit Dome
**Mood:** Vast, humbling, peaceful
**Type:** Centered in the negative space
**Aspect:** 1:1

**Visual Theme:**
- A full dome of small silver stars fills the entire background
- A single thin silver constellation line connects 5-6 stars in the upper third
- A small crescent sits in the constellation as its anchor
- Type sits in a calm negative-space pocket in the center-lower
- Background: deep purple, almost black at the edges

**Color Logic:**
- Primary: deep purple (background)
- Secondary: pale silver (stars, text, constellation)
- Accent: moonlight blue (constellation line, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]    ✦                         │
│        ✦    constellation line      │
│      ✦         ☾                    │
│    ✦     ✦                          │
│                                     │
│  ✦         "Shab-e-Barat"           │
│             Mubarak"                │
│                                     │
│    ✦    "May Allah accept           │
│            our prayers"             │
│                                     │
│   ✦        ✦     ✦                  │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Starlit Dome
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — background)
- Secondary: #D9D6E0 (pale silver — stars, text)
- Accent: #6B8BC9 (moonlight blue — constellation line, CTA icons)

VISUAL ELEMENTS:
- A full dome of small silver stars (~30-50 stars, varied sizes)
- A single thin constellation line connecting 5-6 stars in the upper third
- A small crescent as the constellation's anchor
- Background: deep purple, slightly darker at the edges (vignette)
- ONE focal motif (the star field + constellation) — a single idea

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Star field: distributed across the entire background
- Constellation: upper third, asymmetric
- Type: centered in the lower-middle negative space
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the star field)
- Stars must be SMALL and varied — not large and uniform

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 05 — Arabesque Window
**Mood:** Sacred geometry, screened light, reverent
**Type:** Centered inside the arch
**Aspect:** 1:1

**Visual Theme:**
- A stylized pointed arch (jali screen / arabesque window) frames the post
- Behind the arch, soft silver moonlight pours through as a gradient
- Type sits in the clear center, inside the arch
- Background outside the arch: deep purple
- The jali pattern is line work in accent blue at low opacity

**Color Logic:**
- Primary: deep purple (outside the arch, background)
- Secondary: pale silver (moonlight gradient inside the arch, text)
- Accent: moonlight blue (jali line work, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│            ╱    ╲                    │
│           │░░░░░░│                   │
│           │░░░░░░│  "Shab-e-Barat"  │
│           │░ jali │                  │
│           │░░░░░░│  "Mubarak"       │
│           │░░░░░░│                   │
│           │░░░░░░│  "May Allah      │
│           │░░░░░░│   accept our     │
│           ╲░░░░░╱    prayers"       │
│            ╲____╱                    │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Arabesque Window
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — outside the arch)
- Secondary: #D9D6E0 (pale silver — moonlight gradient inside arch, text)
- Accent: #6B8BC9 (moonlight blue — jali line work, CTA icons)

VISUAL ELEMENTS:
- Stylized pointed arch (jali screen) framing the post
- Behind the arch: a soft silver moonlight gradient
- The jali pattern is line work in accent blue at 25-35% opacity
- Background outside the arch: solid deep purple
- Type sits in the clear center, INSIDE the arch
- ONE focal motif (the arch + its inner moonlight)

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
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the arch + its inner moonlight)
- The jali pattern must be SUBTLE — line work, not filled

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 06 — Calligraphy in the Dark
**Mood:** Type-driven, intimate, quiet
**Type:** Massive, dominant, the design itself
**Aspect:** 1:1

**Visual Theme:**
- The event title is THE design — rendered in a calligraphic serif at huge scale
- Title appears to glow softly, as if written in moonlight
- A single hairline silver rule separates title from message
- Background: deep purple, calm and even
- No other ornament

**Color Logic:**
- Primary: deep purple (background)
- Secondary: pale silver (text)
- Accent: moonlight blue (hairline rule, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│     S H A B - e - B A R A T         │
│         M U B A R A K               │
│         ──────────── (rule)         │
│         "May Allah accept           │
│          our prayers"               │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Calligraphy in the Dark
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — background)
- Secondary: #D9D6E0 (pale silver — text)
- Accent: #6B8BC9 (moonlight blue — hairline rule, CTA icons)

VISUAL ELEMENTS:
- The event title is THE design — calligraphic or display serif
  at massive scale (~12-14% of post height per line)
- Title appears to glow softly, as if written in moonlight
- ONE single hairline silver rule in accent blue, ~30% of post width
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
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal point (the title) — type-driven
- Maximum one decorative element (the hairline rule)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + accent palette naturally.
```

---

### Layout 07 — Silver Mist
**Mood:** Soft, atmospheric, dreamlike
**Type:** Centered, floating
**Aspect:** 1:1

**Visual Theme:**
- Horizontal bands of soft silver mist layer across the post
- Each band is at low opacity, creating depth
- A single small crescent breaks through the topmost band
- Type sits in a calm band of negative space between the mists
- Background: deep purple

**Color Logic:**
- Primary: deep purple (background, base)
- Secondary: pale silver (mist bands, text)
- Accent: moonlight blue (crescent, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│ ░░░░░░░ mist ░░░░░░░ ☾             │
│ ░░░░░░░░░░░░░░░░░░░░░░              │
│                                     │
│       "Shab-e-Barat Mubarak"        │
│                                     │
│ ░░░░░░░░░░░░░░░░░░░░░░              │
│       "May Allah accept             │
│        our prayers"                 │
│                                     │
│ ░░░░░░░░░░░░░░░░░░░░░░              │
│ ░░░░░░░░░░░░░░░░░░░░░░              │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Silver Mist
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — background)
- Secondary: #D9D6E0 (pale silver — mist bands, text)
- Accent: #6B8BC9 (moonlight blue — crescent, CTA icons)

VISUAL ELEMENTS:
- 3-4 horizontal bands of soft silver mist layered across the post
- Each mist band at 20-40% opacity, creating depth
- A single small crescent breaking through the topmost band
- Type sits in calm negative space between the mists
- Background: solid primary
- ONE focal motif (the mist field) + ONE micro (crescent)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Mist bands: horizontal, asymmetric heights, varied opacities
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the mist field) + ONE micro (crescent)
- Mist must feel SOFT and atmospheric — not hard-edged

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 08 — Constellation Map
**Mood:** Connected, ordered, mystical
**Type:** Centered, in the open negative space
**Aspect:** 1:1

**Visual Theme:**
- Multiple thin silver lines connect stars across the post, forming an
  abstract constellation map
- The lines are delicate, never dominant
- A small crescent anchors one of the constellations
- Type sits in a clear, unlined pocket in the center-lower
- Background: deep purple, almost black

**Color Logic:**
- Primary: deep purple (background)
- Secondary: pale silver (stars, text)
- Accent: moonlight blue (constellation lines, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]   ✦                          │
│          \                          │
│       ✦───✦                         │
│         /        "Shab-e-Barat"     │
│      ✦        Mubarak"              │
│       \                            │
│        ✦─☾─✦                       │
│         \                           │
│          ✦    "May Allah accept     │
│              our prayers"           │
│                                     │
│     ✦         ✦                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Constellation Map
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — background)
- Secondary: #D9D6E0 (pale silver — stars, text)
- Accent: #6B8BC9 (moonlight blue — constellation lines, CTA icons)

VISUAL ELEMENTS:
- Multiple thin silver constellation lines connecting ~10-15 stars
- The lines are delicate, never dominant
- A small crescent anchors one of the constellations
- Type sits in a clear, unlined pocket in the center-lower
- Background: deep purple
- ONE focal motif (the constellation field) — a single connected idea

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Constellation: distributed across the post, with clear negative space
  around the type
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the constellation field)
- Constellation lines must be DELICATE, not bold

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 09 — Twin Crescents
**Mood:** Balanced, symbolic, still
**Type:** Centered between the crescents
**Aspect:** 1:1

**Visual Theme:**
- Two crescents sit on opposite sides of the post (left and right),
  mirrored like open parentheses
- They face inward, framing the centered text
- A single small star sits between the crescents at the top
- Background: deep purple, calm and even
- The symmetry IS the design

**Color Logic:**
- Primary: deep purple (background)
- Secondary: pale silver (crescents, text)
- Accent: moonlight blue (star, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│              ✦                      │
│                                     │
│   )                    (            │
│    )   "Shab-e-Barat  (             │
│    )    Mubarak"      (             │
│    )                  (             │
│   )                    (            │
│                                     │
│       "May Allah accept             │
│        our prayers"                 │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 09:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Twin Crescents
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — background)
- Secondary: #D9D6E0 (pale silver — crescents, text)
- Accent: #6B8BC9 (moonlight blue — star, CTA icons)

VISUAL ELEMENTS:
- Two crescents on opposite sides of the post (left + right)
- They face inward, framing the centered text like parentheses
- A single small star sits between the crescents at the top
- Background: solid deep purple
- The SYMMETRY is the design
- ONE focal motif (the twin crescents) + ONE micro (star)

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Left crescent: left third, mid-height
- Right crescent: right third, mid-height, mirrored
- Type: centered between them
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (twin crescents) + ONE micro (star)
- Symmetry must be PRECISE — not approximate

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 10 — Crescent Crown
**Mood:** Heroic-celestial, elevated, reverent
**Type:** Centered, beneath the arching crescent
**Aspect:** 1:1

**Visual Theme:**
- A large crescent arches over the top half of the post like a crown
- A single small star sits at the crescent's apex
- The crescent's inner edge has a soft silver glow
- Type sits in the lower half, beneath the crescent
- Background: deep purple, calm

**Color Logic:**
- Primary: deep purple (background)
- Secondary: pale silver (crescent, text)
- Accent: moonlight blue (inner glow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│         ╱⌒⌒⌒⌒⌒⌒⌒╲                  │
│       ╱  crescent   ╲                │
│      │    + glow     │               │
│      │               │               │
│       ╲             ╱                │
│         ╲_________╱                  │
│              ✦                      │
│                                     │
│       "Shab-e-Barat Mubarak"        │
│       "May Allah accept             │
│        our prayers"                 │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Barat Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Crescent Crown
EVENT TITLE: "Shab-e-Barat Mubarak"
GREETING SUBTITLE: "Night of forgiveness and blessings"
WISH MESSAGE: "May Allah accept our prayers"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F0F3A (deep purple — background)
- Secondary: #D9D6E0 (pale silver — crescent, text)
- Accent: #6B8BC9 (moonlight blue — inner glow, CTA icons)

VISUAL ELEMENTS:
- A large crescent arching over the top half of the post
- A single small star at the crescent's apex
- The crescent's inner edge has a soft silver/blue glow
- Type sits in the lower half, beneath the crescent
- Background: solid deep purple
- ONE focal motif (the crescent + star) — a single hero idea

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Crescent: top half, ~50% of post width, arching
- Star: at the crescent's apex
- Type: lower half, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the crescent + star)
- The crescent must read as ELEVATED and reverent, not Halloween

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given year's Shab-e-Barat post.

| Year's Tone | Recommended Layouts |
|-------------|---------------------|
| Default / classic | 01 Full Moon Halo, 03 Reflection Pool |
| Quiet, intimate | 02 Lantern Procession, 07 Silver Mist |
| Type-driven, brand-led | 06 Calligraphy in the Dark |
| Architectural, geometric | 05 Arabesque Window, 09 Twin Crescents |
| Vast, humbling | 04 Starlit Dome, 08 Constellation Map |
| Elevated, special occasion | 10 Crescent Crown |
| Default rotation | 01, 03, 06, 08 (one of these per cycle) |

**Recommended rotation pattern (4 years):**
- Year 1: Layout 01 — Full Moon Halo
- Year 2: Layout 03 — Reflection Pool
- Year 3: Layout 06 — Calligraphy in the Dark
- Year 4: Layout 08 — Constellation Map

This guarantees 4 visually distinct posts over a 4-year cycle, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_islamic_shab_e_barat_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_islamic_shab_e_barat_01_20260224_v1.png   (Layout 01)
gull_real_estate_builders_islamic_shab_e_barat_03_20260224_v1.png   (Layout 03, vertical)
gull_real_estate_builders_islamic_shab_e_barat_08_20260224_v1.png   (Layout 08)
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

Use this for every Shab-e-Barat post.

```
□ Layout number selected (01-10)
□ Color palette confirmed (3 colors, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-1 micro = max 2)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary ground, secondary icons
□ Aspect ratio: 1:1 default, 4:5 for Layout 03
□ Mood check: mystical/ethereal/contemplative/reverent/peaceful
□ Prohibited elements reviewed (faces, prayer scenes, religious text, etc.)
□ Filename follows convention
```

## 8. Post-Generation Checklist

```
□ No faces or identifiable people
□ No mosque with worshippers or prayer scenes
□ No religious text, verses, or Arabic script
□ No political party logos or symbols
□ No celebration elements (confetti, balloons, fireworks)
□ No bird, nest, or emblem in or near the logo space
□ Logo space is clean and properly reserved
□ User-uploaded logo colors harmonize with the post's palette
□ Text is readable at 200×200 thumbnail size
□ Colors match the selected 3-color palette (no fourth color crept in)
□ Only two typefaces are used
□ Maximum two decorative motifs (one hero + optional micro)
□ CTA bar matches Section 6 spec exactly
□ Aspect ratio matches layout choice
□ Mood is mystical and contemplative, never festive
□ Lanterns (if used) have glow gradients, no literal flames
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Shab-e-Barat-Specific)

Shab-e-Barat (15th Shaban) is a sacred night observed in many Muslim communities as a night of prayer, reflection, and seeking forgiveness. The visual treatment must respect that:

- **No worship scenes.** The night is honored in the greeting, not depicted literally.
- **No religious text.** A greeting in English is fine. Verses and Arabic script are not used.
- **No mosque imagery with people.** A stylized arch or window is fine. A mosque with worshippers is not.
- **Mystical, not macabre.** This is a night of hope and forgiveness, not dark symbolism. No skulls, no somber imagery beyond the calm deep purple.
- **Dignified, not ostentatious.** Silver and moonlight blue are used as accent only, in restrained amounts.
- **The night sky is the canvas.** Stars, moons, crescents, mist — all evoke the night, not any specific religious symbol.

When in doubt: **subtract, don't add.** A simpler post is more respectful than a busier one. If a layout choice starts to read as "Halloween card" or "horror movie poster," stop.

---

**Document Version:** 1.0 - Shab-e-Barat Post Specification
**Last Updated:** July 13, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Shab-e-Barat annual posts
