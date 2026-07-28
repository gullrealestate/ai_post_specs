# Gull Real Estate & Builders - Jumma Mubarak Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Jumma Mubarak** (the weekly Friday blessing in the Islamic tradition). It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be refreshed weekly without visual repetition.

All posts are event-oriented, dignified, calm, and spiritual — never celebratory. The Friday context is treated as a moment of reflection, gratitude, and community, not as a marketing hook.

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
- Allowed motifs: crescent, star, geometric pattern, arch/mihrab,
  stylized lantern, floral (rose, jasmine), water/wave, constellation.
- No more than TWO decorative motifs per post. Typically ONE hero
  motif and ONE supporting micro-element.
- Decorative opacity: hero motif 60-100%, micro-element 20-40%.
- Patterns are reserved for backgrounds only, at ≤15% opacity.
- No decorative element may be placed inside the logo space.
- Lanterns, when used, must NOT show a literal flame. Use a glow gradient.
```

### 2.5 Mood Discipline
```
Jumma Mubarak is a calm, reflective, dignified moment.

ALLOWED MOODS:
  - Serene
  - Reflective
  - Grateful
  - Hopeful
  - Peaceful

NOT ALLOWED MOODS (would betray the spirit of the day):
  - Celebratory
  - Festive
  - Excited
  - Loud
  - Decorative-for-its-own-sake

If a layout choice starts to read as "Eid card" or "wedding invite",
stop. Jumma is a Friday blessing, not a celebration.
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

## 3. The 10 Jumma Mubarak Layouts

Each layout is a complete design system: visual theme, color logic, type logic, composition grid, decorative element, and a worked full prompt. Pick the layout that matches the week's tone, then run the prompt.

### Layout 01 — Dawn Horizon
**Mood:** Reflective, hopeful, the start of something
**Type:** Centered, vertical
**Aspect:** 1:1

**Visual Theme:**
- A horizontal soft-sunrise gradient bisects the post at the lower third
- Above the horizon: a single minaret silhouette in primary color, off-center right
- Below the horizon: a calm secondary-color ground, with one or two gentle wave lines
- A small crescent sits in the upper third as a micro-element

**Color Logic:**
- Primary: deep teal or deep forest green (the dawn sky)
- Secondary: warm cream or pale rose (the horizon glow)
- Accent: soft gold (crescent, CTA icons only)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                  ☾  (crescent)      │
│                                     │
│       "Jumma Mubarak"               │
│       (display, centered)           │
│                                     │
│       "May your Friday be blessed"  │
│       (body, centered)              │
│                                     │
│  ░░░ horizon line ░░░               │
│  ▓▓▓ ground ▓▓▓                     │
│                       |             │
│                       | minaret     │
│                       |             │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Dawn Horizon
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #2E5D4F (deep forest green — the dawn sky)
- Secondary: #F4E4D2 (warm cream — the horizon glow)
- Accent: #C9A961 (soft gold — crescent, CTA icons)

VISUAL ELEMENTS:
- Soft horizontal gradient bisecting the post at the lower third
- One single minaret silhouette in primary color, off-center right
- Small crescent in the upper third, in accent gold
- One or two subtle wave lines below the horizon
- Background pattern (if any) at ≤10% opacity

TYPOGRAPHY:
- Display face: modern transitional serif
- Body face: clean sans-serif
- Title: 10% of post height, centered, primary color on cream
- Subtitle: 4% of post height, centered, primary color
- Message: 3% of post height, centered, primary color at 80% opacity

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, secondary-color ground, primary-color icons + text
- Minaret: off-center right, reaching into the upper sky band
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements (no confetti, balloons, fireworks)
- NO bird, nest, or emblem in the logo space
- Calm, reflective mood — not festive
- ONE focal point (the title), ONE supporting motif (minaret)
- Maximum two decorative motifs total

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 02 — Lantern Centerpiece
**Mood:** Warm, intimate, contemplative
**Type:** Off-center, asymmetric
**Aspect:** 1:1

**Visual Theme:**
- A single oversized traditional lantern (chiragh) occupies the left two-thirds
- Type wraps around the lantern's right edge
- Lantern body has a soft inner glow (no flame shown)
- Background: deep, calm primary with a faint geometric pattern at ≤10%

**Color Logic:**
- Primary: deep midnight blue or deep teal
- Secondary: warm amber (the lantern's glow, NOT a fill)
- Accent: ivory or pale gold (text and CTA)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│   ╔══════════╗     "Jumma            │
│   ║          ║      Mubarak"        │
│   ║  LANTN   ║                      │
│   ║          ║     "May your         │
│   ║   (glow) ║      Friday be        │
│   ╚══════════╝      blessed"        │
│                                     │
│                  "From Gull Real    │
│                   Estate & Builders"│
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Lantern Centerpiece
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #142A3A (midnight blue — background)
- Secondary: #E8A75A (warm amber — lantern glow gradient)
- Accent: #F4ECDA (ivory — text, CTA icons)

VISUAL ELEMENTS:
- Single oversized traditional lantern (chiragh) on the left two-thirds
- Lantern body has a soft inner glow (no literal flame)
- Background: deep primary, with a faint geometric pattern at ≤10%
- Type wraps the lantern's right edge
- ONE focal motif only (the lantern) — no second decorative element

TYPOGRAPHY:
- Display face: elegant calligraphic Latin (flowing terminals)
- Body face: clean sans-serif
- Title: 10% of post height, right-aligned, ivory
- Subtitle: 4% of post height, right-aligned, ivory at 85%
- Company attribution: 3% of post height, right-aligned, ivory at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary-color ground, ivory icons + text
- Lantern: left two-thirds, vertically centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal point (the lantern) — no competing visuals
- Maximum one decorative motif (the lantern) plus background pattern

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + accent palette naturally.
```

---

### Layout 03 — Geometric Mandala
**Mood:** Contemplative, balanced, eternal
**Type:** Centered inside the mandala
**Aspect:** 1:1

**Visual Theme:**
- A large circular geometric mandala (interlocking stars/polygons) frames the post
- Type sits in the clear circular negative space at the center
- Mandala stroke is in the accent color at 80% opacity
- Background: secondary color, calm and clean

**Color Logic:**
- Primary: deep navy or deep teal
- Secondary: ivory or warm cream
- Accent: muted gold (mandala stroke, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│         ╭───────────╮               │
│       ╱   mandala    ╲             │
│      │   ╭───────╮    │             │
│      │  │  "Jumma  │   │            │
│      │  │  Mubarak" │   │           │
│      │   ╰───────╯    │             │
│       ╲             ╱              │
│         ╰───────────╯               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 1:1 (1080x1080) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Geometric Mandala
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1B2A41 (deep navy — mandala stroke)
- Secondary: #F5F1E6 (ivory — background, text)
- Accent: #B8965A (muted gold — micro-highlights, CTA icons)

VISUAL ELEMENTS:
- Large circular geometric mandala (interlocking stars, polygons)
- Mandala stroke: accent color at 80% opacity
- Background: solid secondary color
- Type sits in the clear circular negative space at the center
- NO second decorative motif — the mandala IS the focal point

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary color at 80%
- Wish message: 3% of post height, centered, primary color at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary-color ground, ivory icons + text
- Mandala: optically centered, occupying ~70% of the post width
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal point (the mandala + centered title)
- Maximum one decorative motif (the mandala)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + accent palette naturally.
```

---

### Layout 04 — Calligraphy Hero
**Mood:** Quiet, type-driven, dignified
**Type:** Large, dominant, almost fills the frame
**Aspect:** 1:1

**Visual Theme:**
- The event title is THE design — rendered in a calligraphic or display serif at massive scale
- Subtitle and message are tiny by comparison, set in reserved negative space
- A single hairline ornamental rule (gold) separates the title from the message
- Background: clean primary, no pattern, no other ornament

**Color Logic:**
- Primary: deep emerald or deep teal
- Secondary: ivory (text)
- Accent: muted gold (hairline rule, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│       J U M M A                     │
│       M U B A R A K                 │
│       ─────────── (gold rule)       │
│       "May your Friday be blessed"  │
│                                     │
│       "From Gull Real Estate        │
│        & Builders"                  │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Calligraphy Hero
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1F4A3F (deep emerald — background)
- Secondary: #F4ECDA (ivory — text)
- Accent: #C9A961 (muted gold — hairline rule, CTA icons)

VISUAL ELEMENTS:
- The event title IS the design — calligraphic or display serif at
  massive scale (~12-14% of post height per line)
- ONE single hairline ornamental rule in accent gold between title
  and message (length: ~30% of post width, centered)
- Background: solid primary, no pattern, no other ornament
- NO second decorative motif. NO pattern. The title is the art.

TYPOGRAPHY:
- Display face: calligraphic Latin OR modern Didone serif
- Body face: clean sans-serif
- Title: 12-14% of post height, multi-line if needed, secondary color
- Subtitle: 4% of post height, centered, secondary color at 85%
- Company attribution: 3% of post height, centered, secondary at 65%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary-color ground, ivory icons + text
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

### Layout 05 — Floral Wreath
**Mood:** Soft, gentle, grateful
**Type:** Centered, framed by the wreath
**Aspect:** 1:1

**Visual Theme:**
- A circular floral wreath of stylized rose and jasmine motifs encircles the center
- Type sits in the clear center, never overlapping the wreath
- Wreath is rendered in a single accent color (line work, not filled)
- Background: secondary color, no pattern

**Color Logic:**
- Primary: soft sage green or muted teal
- Secondary: warm cream
- Accent: dusty rose or muted gold (wreath line work, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│        ❀─────❀─────❀               │
│      ❀               ❀              │
│    ❀   "Jumma          ❀            │
│    ❀    Mubarak"        ❀           │
│      ❀               ❀              │
│        ❀─────❀─────❀               │
│                                     │
│   "May your Friday be blessed"      │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Floral Wreath
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #6E8B6F (soft sage green — text)
- Secondary: #FAF3E7 (warm cream — background)
- Accent: #B07A6A (dusty rose — wreath line work, CTA icons)

VISUAL ELEMENTS:
- Circular floral wreath of stylized rose and jasmine
- Wreath rendered as line work in accent color (NOT filled)
- Type sits in the clear center, NEVER overlapping the wreath
- Background: solid secondary, no pattern
- ONE focal motif (the wreath) — no second decorative element

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 80%
- Wish message: 3% of post height, centered, primary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary-color ground, ivory icons + text
- Wreath: optically centered, ~60% of post width
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal point (the wreath + centered title)
- Maximum one decorative motif (the wreath)
- Floral elements must be STYLIZED, not photorealistic

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + accent palette naturally.
```

---

### Layout 06 — Mihrab Arch
**Mood:** Reverent, architectural, still
**Type:** Centered inside the arch
**Aspect:** 1:1

**Visual Theme:**
- A stylized pointed arch (mihrab) frames the centered text
- The arch is rendered as a thin line in the accent color
- Inside the arch: just the title, subtitle, and message
- Background: primary color, calm and even
- A tiny crescent sits at the arch's apex as a micro-element

**Color Logic:**
- Primary: deep sapphire or deep teal
- Secondary: ivory (text and arch interior)
- Accent: muted gold (arch line, crescent, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│              ☾                      │
│            ╱    ╲                    │
│           │      │                   │
│           │      │   "Jumma         │
│           │      │    Mubarak"      │
│           │      │                   │
│           │      │   "May your      │
│           │      │    Friday be     │
│           │      │    blessed"      │
│           │      │                   │
│           ╲      ╱                   │
│            ╲____╱                    │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Mihrab Arch
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #1B3A5B (deep sapphire — background)
- Secondary: #F4ECDA (ivory — text, arch interior)
- Accent: #C9A961 (muted gold — arch line, crescent, CTA icons)

VISUAL ELEMENTS:
- Stylized pointed arch (mihrab) as a thin line in accent gold
- Tiny crescent at the arch's apex
- Inside the arch: only the title, subtitle, and message
- Background: solid primary, no pattern
- ONE focal motif (the arch) — no second decorative element

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary-color ground, ivory icons + text
- Arch: optically centered, ~50% of post width, ~70% of post height
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal point (the arch + centered title)
- Maximum one decorative motif (the arch + its crescent)
- Arch must be STYLIZED, not an architectural drawing

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + accent palette naturally.
```

---

### Layout 07 — Stained Glass
**Mood:** Meditative, structured, jewel-like
**Type:** Centered, with type acting as the "leading" of the glass
**Aspect:** 1:1

**Visual Theme:**
- A geometric stained-glass pattern fills the entire background
- The pattern is divided into clear color blocks (primary + secondary)
- Type sits in a clear, unpatterned rectangular or arched panel in the center
- The contrast between the busy pattern and the clean text panel IS the design

**Color Logic:**
- Primary: deep sapphire or deep amethyst
- Secondary: warm cream or pale gold (used in the glass AND the text panel)
- Accent: muted teal or muted rose (a third color appearing in 1-2 glass cells)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓┌─────────────┐▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "Jumma      │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  Mubarak"   │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "May your   │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  Friday be  │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  blessed"   │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓└─────────────┘▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 1:1 (1080x1080) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Stained Glass
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only — applied to glass cells + text panel):
- Primary: #1E3A6B (deep sapphire — main glass cells)
- Secondary: #F2E4C5 (warm cream — text panel, secondary glass cells)
- Accent: #6B8E9E (muted teal — 1-2 glass cells only, NOT a fill)

VISUAL ELEMENTS:
- Geometric stained-glass pattern fills the entire background
- Pattern is divided into clean color blocks (no gradients within cells)
- A clear, unpatterned rectangular panel in the center holds the type
- The contrast between busy pattern and clean panel IS the design
- ONE focal motif (the stained-glass field + central text panel)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 10% of post height, centered inside the panel, primary color
- Subtitle: 4% of post height, centered, primary at 80%
- Wish message: 3% of post height, centered, primary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary-color ground, ivory icons + text
- Text panel: ~50% of post width, ~40% of post height, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal point (the text panel within the glass field)
- Maximum one decorative motif (the stained-glass pattern)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 08 — Watercolor Wash
**Mood:** Gentle, painterly, organic
**Type:** Centered, soft, hand-set feeling
**Aspect:** 1:1

**Visual Theme:**
- A soft watercolor wash in primary color sweeps from one corner, fading out
- A single small decorative element (crescent, star, or floral sprig) sits
  in the negative space opposite the wash
- Background: ivory or warm cream, paper-like
- The hand-painted feeling is the whole point — sharp vector edges NOT used

**Color Logic:**
- Primary: soft teal or sage (the wash, and the title)
- Secondary: warm cream or ivory (background, subtitle, message)
- Accent: dusty rose or muted gold (the small decorative element, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│    ░░░░░ wash                       │
│   ░░░░░░░ sweeps                    │
│  ░░░░░░░░ from                      │
│ ░░░░░░░░ top-left    ☾              │
│ ░░░░░░░░                            │
│                                     │
│         "Jumma Mubarak"             │
│         "May your Friday            │
│          be blessed"                │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 1:1 (1080x1080) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Watercolor Wash
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #5C8A8A (soft teal — watercolor wash, title)
- Secondary: #FAF3E7 (warm cream — background, subtitle, message)
- Accent: #B07A6A (dusty rose — crescent, CTA icons)

VISUAL ELEMENTS:
- A soft watercolor wash in primary color sweeping from one corner,
  fading out as it goes
- A small crescent in the negative space opposite the wash
- Background: warm cream, paper-like texture
- ONE focal motif (the wash) + ONE micro-element (the crescent)
- Hand-painted feeling — NO sharp vector edges on the wash

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 10% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 80%
- Wish message: 3% of post height, centered, primary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary-color ground, ivory icons + text
- Wash: starts from top-left or top-right corner, fades diagonally
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the wash) + ONE micro-element (the crescent)
- Watercolor look must feel HAND-PAINTED, not vector-flat

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + accent palette naturally.
```

---

### Layout 09 — Starlit Sky
**Mood:** Quiet, vast, spiritual
**Type:** Centered, against the night
**Aspect:** [VERTICAL] 4:5 (1080 × 1350) — recommended for this layout

**Visual Theme:**
- Deep night-sky gradient as background (top: deep primary, bottom: deeper primary)
- A scattering of small stars in accent gold
- A single crescent in the upper third
- Title in soft ivory, message in soft ivory at lower opacity
- The vastness of the sky IS the design — minimal ornamentation

**Color Logic:**
- Primary: deep midnight blue (background)
- Secondary: soft ivory (text, crescent)
- Accent: muted gold (stars, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ✦   ✦           │
│        ☾         ✦       ✦          │
│                       ✦             │
│  ✦           "Jumma"                │
│                  Mubarak"           │
│                                     │
│      "May your Friday be blessed"   │
│                                     │
│   ✦         ✦              ✦        │
│            ✦                         │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 09:**
```
Generate a 4:5 (1080x1350) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Starlit Sky [VERTICAL]
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #0F1A2E (deep midnight blue — background gradient)
- Secondary: #F4ECDA (soft ivory — text, crescent)
- Accent: #C9A961 (muted gold — stars, CTA icons)

VISUAL ELEMENTS:
- Vertical gradient: top slightly lighter primary, bottom deeper primary
- A scattering of small accent-gold stars (~12-18 stars, varied sizes)
- A single crescent in the upper third
- Background is otherwise EMPTY — vastness is the design
- ONE focal motif (the sky field with stars) — no second decorative element

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary-color ground, ivory icons + text
- Title: vertically and horizontally centered
- Negative space: minimum 25% of post is empty (the sky breathes)
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the sky field) — vastness is the design
- Maximum one decorative motif (stars + crescent as a single field)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + accent palette naturally.
```

---

### Layout 10 — Marble & Gold
**Mood:** Refined, elevated, timeless
**Type:** Centered, against the marble
**Aspect:** 1:1

**Visual Theme:**
- A subtle marble or stone texture fills the background in a single soft primary tone
- Thin gold lines form a minimal ornamental frame (a single inner border rectangle,
  OR a top-and-bottom horizontal rule, NOT a full mandala)
- A small crescent sits as a micro-element at the top of the frame
- Type is set in a refined serif with generous letter spacing
- The luxurious restraint is the whole point — it whispers, it does not shout

**Color Logic:**
- Primary: soft warm gray or warm taupe (marble base, title)
- Secondary: ivory (background tone of the marble, subtitle, message)
- Accent: muted gold (lines, crescent, CTA icons)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│    ┌──────────────────────────┐     │
│    │            ☾             │     │
│    │                          │     │
│    │     "Jumma Mubarak"      │     │
│    │                          │     │
│    │  "May your Friday        │     │
│    │   be blessed"            │     │
│    │                          │     │
│    │  "From Gull Real Estate  │     │
│    │   & Builders"            │     │
│    └──────────────────────────┘     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Jumma Mubarak" for
Gull Real Estate & Builders.

LAYOUT: Marble & Gold
EVENT TITLE: "Jumma Mubarak"
GREETING SUBTITLE: "May your Friday be blessed"
WISH MESSAGE: "Prayers for peace and prosperity"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (3 colors only):
- Primary: #6E6259 (warm taupe — marble tone, title)
- Secondary: #F2EBDD (ivory — marble highlight, subtitle, message)
- Accent: #B8965A (muted gold — frame line, crescent, CTA icons)

VISUAL ELEMENTS:
- Subtle marble or stone texture filling the background in the primary tone
- Thin gold line forming a single inner border rectangle (NOT a mandala)
- Small crescent at the top of the frame as a micro-element
- Background marble must be SUBTLE — texture, not pattern
- ONE focal motif (the frame + the type inside it)

TYPOGRAPHY:
- Display face: Didone or modern transitional serif, with generous
  letter spacing (+2% to +4%)
- Body face: clean sans-serif
- Title: 10% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary-color ground, ivory icons + text
- Frame: inner rectangle, ~75% of post width × ~65% of post height
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the frame + the type inside it)
- Maximum one decorative element (the frame + its crescent)
- Marble look must feel LUXURIOUS-RESTRAINED, not gaudy or busy

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + accent palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given Friday. The same event is published weekly, so rotation matters.

| Friday's Tone | Recommended Layouts |
|---------------|---------------------|
| First Friday of the month (fresh start) | 01 Dawn Horizon, 08 Watercolor Wash |
| Reflective / mid-month | 06 Mihrab Arch, 09 Starlit Sky |
| Gratitude / thankfulness | 04 Calligraphy Hero, 05 Floral Wreath |
| Architectural / structured | 03 Geometric Mandala, 07 Stained Glass |
| Warm / communal | 02 Lantern Centerpiece, 05 Floral Wreath |
| Elevated / special occasion | 10 Marble & Gold |
| Default rotation | 01, 04, 06, 09 (one of these per week) |

**Recommended rotation pattern (4 weeks):**
- Week 1: Layout 01 — Dawn Horizon
- Week 2: Layout 04 — Calligraphy Hero
- Week 3: Layout 06 — Mihrab Arch
- Week 4: Layout 09 — Starlit Sky

This guarantees 4 visually distinct Fridays per month, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_islamic_jumma_mubarak_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_islamic_jumma_mubarak_01_20260717_v1.png   (Layout 01)
gull_real_estate_builders_islamic_jumma_mubarak_04_20260724_v1.png   (Layout 04)
gull_real_estate_builders_islamic_jumma_mubarak_09_20260731_v1.png   (Layout 09, vertical)
```

---

## 6. CTA Bar Specification (Identical Across All 10 Layouts)

The CTA bar is the ONE element that never changes. It anchors brand recognition across all the visual variety above.

```
HEIGHT: bottom 12% of the post
GROUND COLOR: primary color of the selected layout
LEFT SIDE: SVG phone icon (stroke: accent color) + "0314 9393930" (body face)
RIGHT SIDE: SVG globe icon (stroke: accent color) + "gullrealestate.github.io" (body face)
DIVIDER: thin vertical line in accent color, 30% opacity, centered
PADDING: equal left/right padding (8% of post width)
ICON SIZE: 24x24 logical units, scalable
TEXT SIZE: 3% of post height
TEXT COLOR: secondary color, OR accent color for high contrast on dark ground
```

### Phone Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[ACCENT_COLOR]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
</svg>
```

### Globe Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[ACCENT_COLOR]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <circle cx="12" cy="12" r="10"/>
  <line x1="2" y1="12" x2="22" y2="12"/>
  <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/>
</svg>
```

---

## 7. Pre-Generation Checklist

Use this for every Jumma post, every Friday.

```
□ Layout number selected (01-10)
□ Color palette confirmed (3 colors, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-1 micro = max 2)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary ground, accent icons
□ Aspect ratio: 1:1 default, 4:5 for Layout 09, 9:16 if needed
□ Mood check: serene/reflective/grateful/hopeful/peaceful — NOT celebratory
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
□ Mood is calm and reflective, never festive
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Jumma-Specific)

Jumma (Friday) is a sacred day in Islamic tradition — a day of communal prayer, reflection, and blessing. The visual treatment must respect that:

- **No worship scenes.** Jumma posts are greetings, not depictions of the prayer itself.
- **No religious text.** A greeting in English is fine. Verses and Arabic script are not used.
- **No mosque imagery with people.** A stylized minaret silhouette or arch is fine. A mosque with worshippers is not.
- **Calm, not celebratory.** Jumma is not Eid. The visual register is closer to "good morning" than "happy holidays".
- **Dignified, not ostentatious.** Gold is used as accent only, in restrained amounts. It whispers.

When in doubt: **subtract, don't add.** A simpler post is more respectful than a busier one.

---

**Document Version:** 1.0 - Jumma Mubarak Post Specification
**Last Updated:** July 13, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Jumma Mubarak weekly posts
