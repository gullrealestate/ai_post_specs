# Gull Real Estate & Builders - Shab-e-Miraj Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Shab-e-Miraj / Isra wal Miraj** (27th Rajab — the Night of the Heavenly Journey). It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be published with visual variety year over year.

All posts are event-oriented, mystical, elevated, and hopeful. Shab-e-Miraj commemorates a sacred night of heavenly ascent — the visual register is "uplifted, ascending, hopeful" rather than "festive" or "somber." The post should always feel like the eye is being drawn upward.

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
❌ NO human figure imagery (no figures, silhouettes, or implied people)
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
- ASCENT RULE: when possible, the eye should travel from lower-third
  (where the type sits) UP toward the upper-third (where the focal
  motif lives). This reinforces the "heavenly journey" theme.
- No element may overlap the logo space or the CTA bar.
```

### 2.4 Decorative Discipline
```
- Decorative elements are SYMBOLIC, never literal.
- Allowed motifs: crescent, star, ascending stairs/arches, gold light
  beams, constellations, concentric arcs, gates/archways, gold
  gradient orbs, layered bands of sky.
- No more than TWO decorative motifs per post. Typically ONE hero
  motif and ONE supporting micro-element.
- Decorative opacity: hero motif 60-100%, micro-element 20-40%.
- Patterns are reserved for backgrounds only, at ≤15% opacity.
- No decorative element may be placed inside the logo space.
- Gold elements must always feel LUMINOUS and ELEVATED, never gaudy.
  Use gold gradients, not flat yellow fills.

### 2.4.1 Proceed With Care — Abstract Concepts Require Restraint

Shab-e-Miraj (Al-Miraj = the ladder / stairway / ascent) is loaded with
abstract, cosmic imagery. Several layouts in this spec touch concepts
that can easily be misread if rendered too literally. The following
guardrails are NON-NEGOTIABLE for the affected layouts:

```
ABSTRACT / ATMOSPHERIC — KEEP IT THAT WAY (Layouts 01, 02, 07):
  - Golden Stairway (01), Beam of Heaven (02), Layered Heavens (07):
    These represent the HEAVENS or the LADDER (Al-Miraj).
    ALLOWED: gradients, soft glowing shapes, light leaks, luminous
             gold bands, stacked atmospheric layers, soft rays.
    NOT ALLOWED: literal physical steps leading into clouds, literal
                 stairs, a literal ladder, architectural staircases,
                 pearly gates, or any object that reads as a built
                 structure meant to be climbed.
    TEST: if you covered the type and asked a stranger "what is that?"
    and they answered "stairs" or "a ladder" — you have failed.

CRESCENT CARRIAGE (05) — THE BURAQ IS NOT DRAWN:
  - The 'carriage' alludes to the Buraq (the heavenly steed of the
    Mi'raj tradition). We do NOT depict the Buraq in any form.
  - ALLOWED: the crescent as a pure geometric symbol, the crescent
            cradling a single star, the crescent cradling typography,
            the crescent as a vessel (symbolic, not narrative).
  - NOT ALLOWED: a winged horse, a horse with a face, a creature of
                 any kind, anything with eyes, a saddle, reins, hooves,
                 or any figure standing/sitting on the crescent.
  - The crescent is geometry, not a vehicle. It carries meaning, not
    a rider.

COSMIC FIELDS (Layouts 04, 08, 09) — STARS AND LIGHT, NOT ROADS:
  - Constellation Path (04), Burst of Light (08), Orbit (09):
    These read as NIGHT-SKY, not landscape.
  - ALLOWED: a scattering of stars, a beam of light, a burst of light,
            concentric arcs, constellation lines connecting stars.
  - NOT ALLOWED: a physical road, a path with footprints, a runway,
                 a track, anything that looks like a surface to walk on,
                 anything that implies travel across solid ground.
  - TEST: if the imagery could be mistaken for a high-way, a walkway,
    a railway, or a runway — remove or soften it. The journey is
    THROUGH the heavens, not ACROSS a surface.
```

Why this matters:
- Literal depictions of the Mi'raj journey can drift into imagery
  that resembles religious illustration, which we avoid.
- Literal heavenly structures (stairs, gates) can read as fantastical
  or devotional art — outside the professional, restrained register
  of this brand.
- The Buraq is a sacred figure in Islamic tradition; depicting it (or
  anything resembling it) is strictly out of bounds for this brand.

Default rule for ALL cosmic concepts in this spec:
**If a motif could be drawn by a religious-illustration artist, redraw
it as a gradient or geometric symbol.**
```

### 2.5 Mood Discipline
```
Shab-e-Miraj is a night of heavenly ascent and divine gift.

ALLOWED MOODS:
  - Uplifted
  - Ascending
  - Hopeful
  - Celestial
  - Reverent
  - Awestruck

NOT ALLOWED MOODS (would betray the spirit of the night):
  - Celebratory
  - Festive
  - Somber
  - Heavy
  - Decorative-for-its-own-sake
  - Cartoonish (no bright primary colors, no flat vector look)

If a layout choice starts to read as "video game UI" or "Christmas
card", stop. Shab-e-Miraj is sacred, not decorative.
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

## 3. The 10 Shab-e-Miraj Layouts

Each layout is a complete design system: visual theme, color logic, type logic, composition grid, decorative element, and a worked full prompt. Pick the layout that matches this year's mood, then run the prompt.

### Layout 01 — Golden Stairway (Abstract / Atmospheric — Proceed with Care)
**Mood:** Ascending, hopeful, direct
**Type:** Centered, in the calm below
**Aspect:** 1:1

**Visual Theme:**
- An ABSTRACT ascending gradient of gold light, rising from lower-center
  toward upper-center. Think LIGHT LEAK, not stairs.
- The shape is built from soft gold gradients, soft glow, and 2-3
  horizontal gold bands that grow LUMINOSITY (not literal steps) as
  they ascend. No flat lines, no defined treads, no risers.
- A few small gold stars near the top of the gradient
- Type sits in the calm below, in the lower-left or lower-center
- Background: celestial indigo, calm
- The motif reads as ASCENDING LIGHT, never as a built staircase or ladder

**Color Logic:**
- Primary: celestial indigo (background)
- Secondary: luminous gold (stairs, text)
- Accent: midnight sky (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│           ✦       ✦                 │
│         ✦                           │
│                  ╱╱                 │
│               ╱╱                    │
│            ╱╱                       │
│         ╱╱                          │
│      ╱╱        ✦                     │
│   ╱╱                               │
│                                     │
│   "Shab-e-Miraj"                    │
│       "Mubarak"                     │
│   "Celestial journey blessed"       │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Golden Stairway
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — background)
- Secondary: #D4AF37 (luminous gold — stairs, text)
- Accent: #0D1B2A (midnight sky — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- An ABSTRACT ascending gradient of gold light (NOT a literal staircase)
- Soft gold light-leak rising from lower-center to upper-center
- 2-3 soft horizontal gold bands that grow LUMINOSITY (not treads)
  as they ascend. No flat lines, no defined treads, no risers.
- A few small gold stars near the top of the gradient (3-5 max)
- Background: deep celestial indigo
- ONE focal motif (the ascending light) + small supporting stars
- MUST NOT read as a physical staircase, ladder, or pearly gate

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered (slightly low), secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Stairway: lower-center to upper-center, narrowing as it climbs
- Type: anchored at the base, eye travels UP along the stairs
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people, no human figure imagery
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- PROCEED WITH CARE: This motif must read as ATMOSPHERIC LIGHT,
  not a physical staircase, ladder, or structure meant to be climbed.
  No defined treads, no risers, no architectural lines.
- ONE focal motif (the ascending light) + small supporting stars
- Maximum one decorative element + small supporting stars

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 02 — Beam of Heaven (Abstract / Atmospheric — Proceed with Care)
**Mood:** Awestruck, single, dramatic
**Type:** Centered, in the dark lower half
**Aspect:** 1:1

**Visual Theme:**
- A single dramatic gold light beam descends from the upper-center
- The beam widens as it descends, like a soft celestial spotlight
- The beam's center is the brightest point; edges fade to indigo
- Type sits in the lower half, in the calm dark
- Background: celestial indigo, almost black at the top
- No stars, no clouds, no opening in the sky — the beam is the
  celestial event, period
- MUST NOT read as light pouring through a hole in the clouds or
  through a heavenly gate. The beam comes from INDIGO, not from
  any depicted opening or structure.

**Color Logic:**
- Primary: celestial indigo (background)
- Secondary: luminous gold (beam, text)
- Accent: midnight sky (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│            ╲      ╱                  │
│             ╲    ╱                   │
│              ╲  ╱                    │
│               ╲╱                     │
│               ╱╲                     │
│              ╱  ╲                    │
│             ╱    ╲                   │
│            ╱      ╲                  │
│                                     │
│       "Shab-e-Miraj Mubarak"        │
│       "Celebrating the              │
│        heavenly journey"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Beam of Heaven
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — background)
- Secondary: #D4AF37 (luminous gold — beam, text)
- Accent: #0D1B2A (midnight sky — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A single dramatic gold light beam descending from upper-center
- The beam widens as it descends, like a soft celestial spotlight
- The beam's center is the brightest point; edges fade to indigo
- Type sits in the lower half, in the calm dark
- Background: celestial indigo, almost black at the top
- ONE focal motif (the beam) — no stars, no clouds, no other elements
- PROCEED WITH CARE: the beam must come from EMPTY indigo — not
  from a hole in clouds, not from a heavenly gate, not from any
  depicted opening or structure. The beam's source is the sky itself.

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Beam: upper-center, descending, ~25% of post width at the top,
  widening to ~40% at the lower half
- Type: lower half, centered, in the calm dark
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people, no human figure imagery
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- The beam must read as a SINGLE, calm descent — not chaotic rays
- PROCEED WITH CARE: no clouds, no opening in the sky, no heavenly
  gate — the beam's source is empty indigo, period
- ONE focal motif (the beam) — no competing elements

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 03 — Ascending Arches
**Mood:** Architectural, receding, infinite
**Type:** Centered, in the foreground
**Aspect:** [VERTICAL] 4:5 (1080 × 1350)

**Visual Theme:**
- A series of nested arches recede into the distance in one-point perspective
- The arches grow smaller and fainter as they recede
- Each arch is rendered as a thin gold line on celestial indigo
- The innermost (deepest) arch glows with gold light
- Type sits in the foreground, inside the largest arch

**Color Logic:**
- Primary: celestial indigo (background, space between arches)
- Secondary: luminous gold (arch lines, text)
- Accent: midnight sky (deepest void, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│     ┌───────────────────────┐       │
│     │  ┌─────────────────┐  │       │
│     │  │  ┌───────────┐  │  │       │
│     │  │  │  ┌─────┐  │  │  │       │
│     │  │  │  │ glow│  │  │  │       │
│     │  │  │  └─────┘  │  │  │       │
│     │  │  └───────────┘  │  │       │
│     │  └─────────────────┘  │       │
│     │ "Shab-e-Miraj"          │     │
│     │     "Mubarak"           │     │
│     └───────────────────────┘       │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 4:5 (1080x1350) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Ascending Arches [VERTICAL]
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — background)
- Secondary: #D4AF37 (luminous gold — arch lines, text)
- Accent: #0D1B2A (midnight sky — deepest void, CTA icons)

VISUAL ELEMENTS:
- A series of nested arches receding in one-point perspective
- The arches grow smaller and fainter as they recede (4-6 arches)
- Each arch is a thin gold line on celestial indigo
- The innermost (deepest) arch glows with soft gold light
- Type sits in the foreground, inside the largest arch
- ONE focal motif (the arch series) — a single receding idea

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Largest arch: ~90% of post width, in the foreground
- Each subsequent arch: ~15% smaller, recedes toward vanishing point
- Type: foreground, centered inside the largest arch
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people, no human figure imagery
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- The arches must read as INFINITE and REVERENT, not playful
- ONE focal motif (the arch series)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 04 — Constellation Path (Cosmic Field — Proceed with Care)
**Mood:** Journeying, connected, hopeful
**Type:** Centered, in the calm below
**Aspect:** 1:1

**Visual Theme:**
- A trail of gold stars arcs upward from lower-left to upper-right
- Thin gold lines connect the stars like a constellation trail
- The trail grows brighter and more luminous as it ascends
- A small crescent sits at the trail's apex
- Type sits in the lower-left or lower-center, in the calm below
- The 'path' is a SCATTERING OF STARS connected by thin lines,
  not a road, walkway, runway, or surface. It must read as NIGHT SKY,
  not as landscape.

**Color Logic:**
- Primary: celestial indigo (background)
- Secondary: luminous gold (stars, lines, text)
- Accent: midnight sky (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                          ☾           │
│                       ╱              │
│                    ✦                │
│                  ╱                  │
│               ✦                    │
│             ╱                       │
│          ✦                          │
│        ╱                            │
│     ✦                               │
│   ╱                                  │
│                                     │
│   "Shab-e-Miraj Mubarak"            │
│   "Celebrating the heavenly journey" │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Constellation Path
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — background)
- Secondary: #D4AF37 (luminous gold — stars, lines, text)
- Accent: #0D1B2A (midnight sky — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A trail of gold stars arcs upward from lower-left to upper-right
- Thin gold lines connect the stars like a constellation trail
- The trail grows brighter and more luminous as it ascends
- A small crescent sits at the trail's apex
- Type sits in the lower-left or lower-center, in the calm below
- ONE focal motif (the ascending star trail) + ONE micro (apex crescent)
- PROCEED WITH CARE: the 'path' must read as a scattering of stars
  with constellation lines — NOT a road, walkway, runway, or surface
  of any kind. No footprints, no tracks, no implied ground.

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered (slightly low), secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Trail: arcs from lower-left to upper-right, ~6-8 stars
- Apex crescent: upper-right
- Type: lower-left or lower-center
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people, no human figure imagery
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- The trail must read as ASCENDING, not horizontal
- PROCEED WITH CARE: this is a SCATTERING OF STARS, not a road or
  surface. No footprints, no tracks, no implied ground beneath.
- ONE focal motif (the trail) + ONE micro (crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 05 — Crescent & Star (Symbolic — Proceed with Care)
**Mood:** Symbolic, quiet, ascending
**Type:** Centered, below the crescent
**Aspect:** 1:1

**Visual Theme:**
- A large gold crescent sits in the upper half as a pure GEOMETRIC symbol
- A single small star rests INSIDE the crescent's curve
- The crescent is a SHAPE, not a vehicle. It carries meaning, not a rider.
- Type sits in the lower half, beneath the crescent
- Background: celestial indigo, calm
- No other elements
- CRITICAL: this layout alludes to the Buraq tradition. The Buraq
  is NOT drawn. There is no creature, no winged horse, no figure
  of any kind. The crescent is geometry, period.

**Color Logic:**
- Primary: celestial indigo (background)
- Secondary: luminous gold (crescent, star, text)
- Accent: midnight sky (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│        ╱⌒⌒⌒⌒⌒⌒⌒⌒⌒╲                 │
│      ╱      ✦        ╲               │
│    ╱                   ╲             │
│                                     │
│                                     │
│                                     │
│       "Shab-e-Miraj Mubarak"        │
│       "Celebrating the              │
│        heavenly journey"            │
│                                     │
│       "Blessings of the             │
│        sacred journey"              │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Crescent Carriage
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — background)
- Secondary: #D4AF37 (luminous gold — crescent, star, text)
- Accent: #0D1B2A (midnight sky — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A large gold crescent in the upper half, oriented horizontally
- A single small star rests INSIDE the crescent's curve
- The crescent is a pure geometric symbol — NOT a vehicle, NOT a
  boat, NOT a saddle, NOT a vessel carrying a rider
- Type sits in the lower half, beneath the crescent
- Background: solid celestial indigo
- ONE focal motif (the crescent + star) — a single geometric idea

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Crescent: upper half, ~50% of post width
- Star: inside the crescent's curve
- Type: lower half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people, no human figure imagery
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- PROCEED WITH CARE — THE BURAQ IS NOT DRAWN. The crescent is a
  pure geometric symbol, NOT a vehicle. NO winged horse, NO horse
  with a face, NO creature of any kind, NO figure sitting or
  standing on the crescent, NO saddle, NO reins, NO hooves, NO
  eyes, NO face on any element.
- The crescent carries MEANING, not a rider
- ONE focal motif (the crescent + star)
- The star must be CLEARLY inside the crescent's curve

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 06 — Calligraphy in Gold
**Mood:** Type-driven, intimate, luminous
**Type:** Massive, the design itself
**Aspect:** 1:1

**Visual Theme:**
- The event title is THE design — rendered in a luminous gold calligraphic
  or display serif at huge scale
- Title appears to glow softly against the deep indigo
- A single hairline gold rule separates title from message
- Background: celestial indigo, calm and even
- No other ornament

**Color Logic:**
- Primary: celestial indigo (background)
- Secondary: luminous gold (text)
- Accent: midnight sky (hairline rule, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│     S H A B - e - M I R A J         │
│         M U B A R A K               │
│         ──────────── (rule)         │
│         "Celebrating the            │
│          heavenly journey"          │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Calligraphy in Gold
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — background)
- Secondary: #D4AF37 (luminous gold — text)
- Accent: #0D1B2A (midnight sky — hairline rule, CTA icons)

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
- NO faces, no people, no human figure imagery
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

### Layout 07 — Layered Heavens (Abstract / Atmospheric — Proceed with Care)
**Mood:** Atmospheric, ordered, cosmic
**Type:** Centered, on the horizon line
**Aspect:** 1:1

**Visual Theme:**
- Horizontal ATMOSPHERIC BANDS of deepening indigo across the post
- Each band is a slightly different shade of the primary (allowed by
  the gradient rule between primary + secondary)
- Each band feels like a soft, hazy layer of sky — NOT a hard-edged
  stripe, NOT a tier of a building, NOT a defined platform or level
- A single gold star sits in one of the upper bands
- Type sits on a thin gold horizon line crossing the middle
- The bands must read as DEPTH IN THE SKY, never as floors of a
  structure, steps of a stairway, or levels of a building.

**Color Logic:**
- Primary: celestial indigo (bands, varying depth)
- Secondary: luminous gold (horizon line, text, star)
- Accent: midnight sky (deepest band, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│  ░░░░░░░ band 1 (lightest)          │
│  ░░░░░░░                             │
│  ▓▓▓▓▓▓▓ band 2      ✦              │
│  ▓▓▓▓▓▓▓                             │
│  ███████ band 3                      │
│  ███████                             │
│  ███████ band 4 (deepest)            │
│  ═══════════════ (gold horizon)      │
│       "Shab-e-Miraj Mubarak"        │
│       "Celebrating the              │
│        heavenly journey"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Layered Heavens
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — base band color)
- Secondary: #D4AF37 (luminous gold — horizon line, text, star)
- Accent: #0D1B2A (midnight sky — deepest band, CTA icons)

VISUAL ELEMENTS:
- 4-5 horizontal ATMOSPHERIC bands of indigo across the post
- Each band is a slightly different depth of primary (allowed by
  the gradient rule between primary + accent)
- Bands have SOFT, HAZY edges — not hard horizontal lines
- A single gold star sits in one of the upper bands
- Type sits on a thin gold horizon line crossing the middle
- ONE focal motif (the layered sky) + ONE micro (star)
- PROCEED WITH CARE: bands must read as ATMOSPHERIC DEPTH, not as
  floors, tiers, levels, or platforms of a built structure.

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Bands: 4-5 horizontal layers, each ~15-20% of post height
- Horizon line: at the mid-line, thin gold
- Type: below the horizon, centered
- Star: in one of the upper bands
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people, no human figure imagery
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- PROCEED WITH CARE: the bands must read as ATMOSPHERIC DEPTH
  in the sky, not as floors, tiers, levels, or platforms of a
  built structure. Soft hazy edges only, no hard horizontal lines.
- ONE focal motif (the layered sky) + ONE micro (star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 08 — Burst of Light (Cosmic Field — Proceed with Care)
**Mood:** Awestruck, radiant, single
**Type:** Centered, in the calm below the burst
**Aspect:** 1:1

**Visual Theme:**
- A radial gold light burst originates from the upper-center
- Soft gold rays extend outward in a sky-radiance pattern
- The center is the brightest point; rays fade to indigo
- Type sits in the lower half, in the calm dark
- Background: celestial indigo
- No stars, no sun, no horizon — the burst IS the celestial event
- PROCEED WITH CARE: the burst is a SKY-RADIANCE, not a sun rising
  over a horizon, not an explosion, not a flash on a surface. It is
  light emanating from the night sky itself.

**Color Logic:**
- Primary: celestial indigo (background)
- Secondary: luminous gold (burst, text)
- Accent: midnight sky (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│            \ │ /                    │
│          ─  ✦  ─                    │
│            / │ \                    │
│          /  │  \                    │
│        /    │    \                  │
│      /      │      \                │
│    /        │        \              │
│                                     │
│       "Shab-e-Miraj Mubarak"        │
│       "Celebrating the              │
│        heavenly journey"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Burst of Light
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — background)
- Secondary: #D4AF37 (luminous gold — burst, text)
- Accent: #0D1B2A (midnight sky — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A radial gold light burst from the upper-center
- Soft gold rays extend outward in a sky-radiance pattern (~12-16 rays)
- The center is the brightest point; rays fade to indigo
- Type sits in the lower half, in the calm dark
- Background: celestial indigo
- ONE focal motif (the burst) — no stars, no sun, no horizon
- PROCEED WITH CARE: this is a SKY-RADIANCE, not a sun rising over
  a horizon, not an explosion, not a flash on a surface. The light
  emanates from the night sky itself.

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Burst: upper-center, ~50% of post width
- Type: lower half, centered, in the calm dark
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people, no human figure imagery
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- The burst must read as RADIANT and SOFT, not spiky or aggressive
- PROCEED WITH CARE: the burst is a SKY-RADIANCE — not a sun on a
  horizon, not an explosion, not a flash on a surface. No sun disc,
  no horizon line, no implied ground beneath the rays.
- ONE focal motif (the burst) — no competing elements

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 09 — Orbit (Cosmic Field — Proceed with Care)
**Mood:** Cosmic, ordered, harmonious
**Type:** Centered, in the open negative space
**Aspect:** 1:1

**Visual Theme:**
- A central gold star sits at the post's center as a PURE GEOMETRIC point
- 3-4 concentric gold arcs orbit the star, each at a different radius
- The arcs are thin, elegant, and partial (not full circles)
- The arcs create a sense of cosmic motion in the SKY
- Type sits in a calm negative space pocket in the lower half
- Background: celestial indigo, calm
- PROCEED WITH CARE: this is cosmic geometry, not a planetary diagram,
  not an astronomical chart, not a depiction of literal celestial
  bodies. It is pure ornament, not a model of any real system.

**Color Logic:**
- Primary: celestial indigo (background)
- Secondary: luminous gold (star, arcs, text)
- Accent: midnight sky (deepest shadow, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│       ╱─────────╲                    │
│      │   ╱─────╲  │                  │
│      │  │  ╱─╲  │ │                  │
│      │  │ │✦│  │ │                  │
│      │  │  ╲─╱  │ │                  │
│      │   ╲─────╱  │                  │
│       ╲─────────╱                    │
│                                     │
│       "Shab-e-Miraj Mubarak"        │
│       "Celebrating the              │
│        heavenly journey"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 09:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Orbit
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — background)
- Secondary: #D4AF37 (luminous gold — star, arcs, text)
- Accent: #0D1B2A (midnight sky — deepest shadow, CTA icons)

VISUAL ELEMENTS:
- A central gold star at the post's center
- 3-4 concentric gold arcs orbiting the star at different radii
- Arcs are THIN, ELEGANT, and PARTIAL (not full circles)
- Arcs create a sense of cosmic motion without literal movement
- Type sits in a calm negative space pocket in the lower half
- Background: solid celestial indigo
- ONE focal motif (the orbiting system) — a single ordered idea
- PROCEED WITH CARE: this is cosmic geometry, not a planetary
  diagram or astronomical chart. It is ornament, not a model.

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
- Type: lower half, centered, in a calm pocket
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people, no human figure imagery
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- The arcs must read as COSMIC and HARMONIOUS, not chaotic
- PROCEED WITH CARE: this is cosmic geometry (ornament), not a
  planetary diagram or astronomical model. No labels, no orbits
  of named bodies, no implied science illustration.
- ONE focal motif (the orbiting system)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 10 — Gate of Light
**Mood:** Threshold, reverent, infinite
**Type:** Centered, inside the gate
**Aspect:** 1:1

**Visual Theme:**
- A single stylized arch (gate) frames the post's center
- Inside the arch: a luminous gold gradient fills the gate from top to bottom
- The arch's outline is a thin gold line
- Type sits in the gate, in the gradient
- Background outside the arch: celestial indigo
- The arch is the only ornament

**Color Logic:**
- Primary: celestial indigo (outside the gate)
- Secondary: luminous gold (arch line, gradient inside, text)
- Accent: midnight sky (deepest shadow outside the arch, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│            ╱    ╲                    │
│           │░░░░░│                   │
│           │░░░░░│                   │
│           │░░░░░│ "Shab-e-Miraj"    │
│           │░░░░░│   "Mubarak"       │
│           │░░░░░│                   │
│           │░░░░░│ "Celebrating the  │
│           │░░░░░│  heavenly journey"│
│           ╲░░░░╱                    │
│            ╲____╱                    │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Shab-e-Miraj Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Gate of Light
EVENT TITLE: "Shab-e-Miraj Mubarak"
GREETING SUBTITLE: "Celebrating the heavenly journey"
WISH MESSAGE: "Blessings of the sacred journey"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1A237E (celestial indigo — outside the gate)
- Secondary: #D4AF37 (luminous gold — arch line, gradient inside, text)
- Accent: #0D1B2A (midnight sky — deepest shadow outside, CTA icons)

VISUAL ELEMENTS:
- A single stylized arch (gate) framing the post's center
- Inside the arch: a luminous gold gradient fills the gate top to bottom
- The arch's outline is a thin gold line
- Type sits in the gate, in the gold gradient
- Background outside the arch: solid celestial indigo
- ONE focal motif (the gate of light) — a single threshold idea

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
- Gradient inside: brightest at top, fading slightly toward bottom
- Type: centered inside the gate
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people, no human figure imagery
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- The arch must read as a THRESHOLD, not a doorway to a building
- ONE focal motif (the gate of light)
- The gradient must feel LUMINOUS, not flat yellow

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given year's Shab-e-Miraj post.

| Year's Tone | Recommended Layouts |
|-------------|---------------------|
| Default / classic | 01 Golden Stairway, 04 Constellation Path |
| Awestruck, single dramatic moment | 02 Beam of Heaven, 08 Burst of Light |
| Architectural, threshold | 03 Ascending Arches, 10 Gate of Light |
| Type-driven, brand-led | 06 Calligraphy in Gold |
| Cosmic, ordered | 09 Orbit, 07 Layered Heavens |
| Symbolic, intimate | 05 Crescent Carriage |
| Default rotation | 01, 04, 06, 08 (one of these per cycle) |

**Recommended rotation pattern (4 years):**
- Year 1: Layout 01 — Golden Stairway
- Year 2: Layout 04 — Constellation Path
- Year 3: Layout 06 — Calligraphy in Gold
- Year 4: Layout 08 — Burst of Light

This guarantees 4 visually distinct posts over a 4-year cycle, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_islamic_shab_e_miraj_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_islamic_shab_e_miraj_01_20270114_v1.png   (Layout 01)
gull_real_estate_builders_islamic_shab_e_miraj_03_20270114_v1.png   (Layout 03, vertical)
gull_real_estate_builders_islamic_shab_e_miraj_08_20270114_v1.png   (Layout 08)
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

Use this for every Shab-e-Miraj post.

```
□ Layout number selected (01-10)
□ Color palette confirmed (3 colors, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-1 micro = max 2)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary ground, secondary icons
□ Aspect ratio: 1:1 default, 4:5 for Layout 03
□ Ascent rule: eye travels from lower type UP toward upper motif
□ Mood check: uplifted/ascending/hopeful/celestial/reverent
□ Prohibited elements reviewed (faces, figures, prayer scenes, religious text, etc.)
□ Filename follows convention
```

## 8. Post-Generation Checklist

```
□ No faces, no people, no human figure imagery
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
□ Mood is uplifted and ascending, never festive or somber
□ Gold elements feel LUMINOUS, not gaudy or flat-yellow
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Shab-e-Miraj-Specific)

Shab-e-Miraj (27th Rajab) is the night of the Prophet's ascension through the heavens — a sacred night in Islamic tradition. The visual treatment must respect that:

- **No human figure imagery.** This is the strictest of all our specs. The Prophet is never depicted. NO figures, NO silhouettes, NO implied people anywhere in the post.
- **The Buraq is not drawn.** Layout 05 (Crescent & Star) alludes to the Buraq tradition. The Buraq is a sacred figure and is NEVER depicted. The crescent is a pure geometric symbol, not a vehicle. No winged horse, no horse with a face, no creature of any kind, no figure sitting on the crescent, no saddle, no reins, no hooves, no eyes, no face on any element. (See Section 2.4.1 for the full rule.)
- **No worship scenes.** The journey is honored in the greeting, not depicted literally.
- **No religious text.** A greeting in English is fine. Verses and Arabic script are not used.
- **No mosque imagery with people.** A stylized arch or gate is fine. A mosque with worshippers is not.
- **Abstract, not literal.** Layouts 01, 02, and 07 touch concepts (the ladder, the heavens, the ascent) that can easily be misread if rendered too literally. The motif must read as ATMOSPHERIC LIGHT, not as a built structure. No literal stairs, no literal ladder, no pearly gates, no platforms, no floors, no tiers. (See Section 2.4.1.)
- **Cosmic, not earthly.** Layouts 04, 08, and 09 sit in the night-sky register. No roads, walkways, runways, footprints, tracks, or any surface that implies travel across ground. (See Section 2.4.1.)
- **Ascent, not gravity.** The eye should travel UP. Avoid heavy, earthbound compositions.
- **Gold is sacred, not gaudy.** Gold reads as divine light, not decoration. Use gradients and luminous quality, never flat yellow fills.
- **The heavens are the canvas.** Stars, moons, crescents, light beams, arches, layered skies — all evoke the celestial realm, not any specific religious symbol.

The single most important rule for this spec:
> **If a motif could be drawn by a religious-illustration artist, redraw it as a gradient or geometric symbol.**

When in doubt: **subtract, don't add.** A simpler post is more respectful than a busier one. If a layout choice starts to read as "video game UI", "Christmas card", or "fantasy art", stop.

---

**Document Version:** 1.0 - Shab-e-Miraj Post Specification
**Last Updated:** July 13, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Shab-e-Miraj annual posts
