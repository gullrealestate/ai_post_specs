# Gull Real Estate & Builders - Ramadan 1st Ashra (Rehmat) Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Ramadan 1st Ashra — Rehmat (Mercy)**, the first ten days of Ramadan. It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be published with visual variety year over year.

All posts are event-oriented, hopeful, gentle, and merciful. The first Ashra is the opening of Ramadan — a time of mercy, compassion, and a fresh spiritual beginning. The visual register is **soft, warm, dawn-like** — never festive in the Eid sense, never somber, never austere. The post should always feel like the first light breaking over a quiet morning.

This is the first of FOUR Ramadan specs (1st, 2nd, 3rd Ashra + general Ramadan). Each Ashra has a UNIQUE color palette and must not cross-contaminate with the others. The palette and rules here apply ONLY to the 1st Ashra (Rehmat/Mercy).

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
❌ NO emerald or violet tones (those belong to 2nd and 3rd Ashra)
❌ NO literal hearts, no Valentine's-style imagery
```

---

## 2. Strict Design Language (Applies to All 10 Layouts)

This is the spine of the spec. The 10 layouts all live inside these rules.

### 2.1 Color Discipline
```
- ONLY THREE COLORS are allowed in the entire post:
  * Primary: #E8B4B8 (soft dawn pink)
  * Secondary: #D4AF37 (warm gold)
  * Accent: #FFF8E7 (ivory)
- No fourth color. No exceptions.
- No emerald. No violet. Those palettes belong to other Ashras.
- Gradient stops are allowed ONLY between Primary and Accent
  (the dawn pink and ivory natural flow).
- The Accent (ivory) is reserved for: backgrounds in part of the
  composition, text contrast, the company wordmark, and small
  micro-elements. The Secondary (gold) is reserved for: type,
  decorative motif line work, and CTA icons.
- Backgrounds: solid ivory, solid dawn pink, or a dawn-pink-to-ivory
  gradient. NOTHING else.
- Text contrast: AAA where possible, AA at minimum
```

### 2.2 Typography Discipline
```
- Use EXACTLY TWO typefaces per post:
  * One display face (the EVENT TITLE)
  * One body face (subtitle, message, CTA)
- The display face must be either a refined serif (Didone, modern
  transitional) or a calligraphic Latin (flowing terminals). The
  calligraphic option suits this Ashra particularly well.
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
- The event title is always centered on the dominant axis.
- DAWN RULE: when possible, the eye should travel from the title
  block UP toward a soft, hopeful focal motif (crescent, light, or
  bloom) in the upper third. The composition should feel like the
  first light of day.
- No element may overlap the logo space or the CTA bar.
```

### 2.4 Decorative Discipline
```
- Decorative elements are SYMBOLIC, never literal.
- Allowed motifs: small crescent, single small star, soft rose
  petal, abstract dotted arc (counting days), stylized lantern
  (chiragh, no literal flame), geometric pattern at low opacity,
  arch/mihrab (line work), mist/fog bands.
- No more than TWO decorative motifs per post. Typically ONE hero
  motif and ONE supporting micro-element.
- Decorative opacity: hero motif 60-100%, micro-element 20-40%.
- Patterns are reserved for backgrounds only, at ≤15% opacity.
- No decorative element may be placed inside the logo space.
- Lanterns, when used, must NOT show a literal flame. Use a glow gradient.
- NO emerald, NO violet, NO deep blue, NO crimson, NO black.
  Those belong to other Ashras or events.
```

### 2.5 Mood Discipline
```
The 1st Ashra of Ramadan is the first ten days — Rehmat (Mercy).

ALLOWED MOODS:
  - Hopeful
  - Gentle
  - Merciful
  - Compassionate
  - Dawn-like
  - Beginning
  - Warm

NOT ALLOWED MOODS (would betray the spirit of this Ashra):
  - Celebratory (this is NOT Eid)
  - Festive with confetti/balloons
  - Solemn or austere (this is the MERCIFUL Ashra, not the
    reflective one or the salvation one)
  - Heavy, deep, or moody
  - Decorative-for-its-own-sake
  - Valentine's (this is mercy, not romance — no literal hearts,
    no roses-as-romance, no pink-as-love cliché)

If a layout choice starts to read as "Valentine's card", "Eid
card", or "funeral program", stop. The 1st Ashra is a SOFT
DAWN, the gentle beginning of a sacred month.
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

## 3. The 10 Ramadan 1st Ashra Layouts

Each layout is a complete design system. Pick the layout that matches this year's mood, then run the prompt.

### Layout 01 — First Dawn
**Mood:** Hopeful, soft, the very first light
**Type:** Centered, in the calm below
**Aspect:** 1:1

**Visual Theme:**
- A soft dawn gradient at the lower third (primary pink rising into
  accent ivory above)
- A small new crescent in the upper third
- A single small star beside the crescent as a micro-element
- Type sits in the calm mid-band, below the crescent

**Color Logic:**
- Primary: soft dawn pink (lower band)
- Secondary: warm gold (crescent, star, text)
- Accent: ivory (upper sky, light source)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│              ☾ ✦                     │
│                                     │
│                                     │
│   ░░░░ soft sky ░░░░ (ivory)        │
│                                     │
│       "Ramadan - Week of Mercy"     │
│       "First Ashra: Rehmat"         │
│                                     │
│   ▓▓▓ dawn pink ▓▓▓ (primary)       │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: First Dawn
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — lower band)
- Secondary: #D4AF37 (warm gold — crescent, star, text)
- Accent: #FFF8E7 (ivory — upper sky)

VISUAL ELEMENTS:
- Soft dawn gradient at the lower third (primary pink rising into
  accent ivory above)
- A small new crescent in the upper third
- A single small star beside the crescent as a micro-element
- ONE focal motif (the crescent) + ONE micro (star)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Horizon: at the lower third
- Crescent: upper third, slightly off-center
- Type: in the calm mid-band, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones (those belong to other Ashras)
- NO literal hearts, no Valentine's-style imagery
- Gentle, hopeful mood — dawn-like, not festive
- ONE focal motif (the crescent) + ONE micro (star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 02 — Petal Field
**Mood:** Soft, scattered, gentle
**Type:** Centered, amid the petals
**Aspect:** 1:1

**Visual Theme:**
- Scattered soft rose petals float across the ivory background
- A small crescent sits in the upper third as the anchor
- Type sits in the center, amid the petals
- Petals are NOT realistic — they are stylized, abstract shapes
- Background: ivory, with petals at varying opacity

**Color Logic:**
- Primary: soft dawn pink (petals)
- Secondary: warm gold (crescent, text)
- Accent: ivory (background)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾                │
│                                     │
│      ❀         ❀                    │
│                                     │
│   ❀    "Ramadan - Week of   ❀      │
│         Mercy"                      │
│  ❀      "First Ashra:        ❀     │
│  ❀       Rehmat (Mercy)"     ❀     │
│                                     │
│      ❀    "May this Ramadan         │
│             bring Allah's mercy"    │
│                                     │
│        ❀         ❀                  │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: Petal Field
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — petals)
- Secondary: #D4AF37 (warm gold — crescent, text)
- Accent: #FFF8E7 (ivory — background)

VISUAL ELEMENTS:
- Scattered soft rose petals float across the ivory background (~12-18 petals)
- Petals are STYLIZED and ABSTRACT, NOT photorealistic
- A small crescent sits in the upper third as the anchor
- Petals at varying opacity (some 100%, some 40-60%)
- ONE focal motif (the crescent) + scattered petals as supporting field

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, accent ivory ground, secondary icons + text
- Crescent: upper third, slightly off-center
- Type: center, amid the petals
- Petals: scattered across the post, NOT touching the logo or CTA
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones
- NO literal hearts, no Valentine's-style imagery
- Petals must read as STYLIZED flower shapes, NOT romantic roses
- ONE focal motif (the crescent) + petal field

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 03 — Crescent & Rosary
**Mood:** Counting the days, meditative
**Type:** Centered, paired with the rosary arc
**Aspect:** 1:1

**Visual Theme:**
- A small crescent sits in the upper-center
- Below it, an abstract dotted arc curves across the post like a
  rosary or counting beads (no literal prayer beads — just dots)
- The arc suggests "the days passing"
- Type sits in the lower half
- Background: ivory

**Color Logic:**
- Primary: soft dawn pink (background field or gradient)
- Secondary: warm gold (crescent, dotted arc, text)
- Accent: ivory (background)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│              ☾                      │
│                                     │
│       • • • • • • • • • •           │
│                                     │
│   "Ramadan - Week of Mercy"         │
│   "First Ashra: Rehmat (Mercy)"     │
│                                     │
│   "May this Ramadan bring           │
│    Allah's mercy"                   │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: Crescent & Rosary
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — gradient or accent)
- Secondary: #D4AF37 (warm gold — crescent, dotted arc, text)
- Accent: #FFF8E7 (ivory — background)

VISUAL ELEMENTS:
- A small crescent in the upper-center
- An abstract dotted arc curving across the post (8-12 small gold dots)
- The arc is NOT a literal prayer bead — it's a counting-line motif
- Type sits in the lower half
- Background: ivory
- ONE focal motif (the crescent + dotted arc) — a single idea

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, accent ivory ground, secondary icons + text
- Crescent: upper-center
- Dotted arc: across the middle, curving downward
- Type: lower half, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones
- The dotted arc must read as a COUNTING-LINE, NOT a literal
  prayer bead / tasbih / rosary. No string, no thread, no beads
  on a cord. Just abstract dots in an arc.
- ONE focal motif (the crescent + dotted arc)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 04 — Window of Dawn
**Mood:** Threshold, framed light
**Type:** Centered, inside the arch
**Aspect:** 1:1

**Visual Theme:**
- A stylized pointed arch (window/mihrab) frames the post's center
- Inside the arch: a soft dawn-pink-to-ivory gradient suggesting
  the first light
- Type sits inside the arch, in the gradient
- Background outside the arch: deep dawn pink
- A small crescent sits at the arch's apex as a micro-element

**Color Logic:**
- Primary: soft dawn pink (outside the arch)
- Secondary: warm gold (arch line, crescent, text)
- Accent: ivory (gradient inside the arch)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│            ╱    ╲                    │
│           │░░░░░│                   │
│           │░░░░░│ "Ramadan -       │
│           │░░░░░│  Week of Mercy"  │
│           │░░░░░│                   │
│           │░░░░░│ "First Ashra:    │
│           │░░░░░│  Rehmat (Mercy)" │
│           ╲░░░░╱                    │
│            ╲____╱ ☾                  │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: Window of Dawn
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — outside the arch)
- Secondary: #D4AF37 (warm gold — arch line, crescent, text)
- Accent: #FFF8E7 (ivory — gradient inside the arch)

VISUAL ELEMENTS:
- Stylized pointed arch (window) framing the post's center
- Inside the arch: soft dawn-pink-to-ivory gradient
- Background outside the arch: solid dawn pink
- A small crescent at the arch's apex as a micro-element
- ONE focal motif (the arch) + ONE micro (crescent)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Arch: optically centered, ~55% of post width, ~70% of post height
- Type: centered inside the arch
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones
- The arch must be STYLIZED — line work, not an architectural drawing
- The arch reads as a WINDOW framing dawn light, not a mosque
- ONE focal motif (the arch) + ONE micro (crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 05 — Lantern at Dawn
**Mood:** Warm, intimate, contemplative
**Type:** Off-center, paired with the lantern
**Aspect:** 1:1

**Visual Theme:**
- A single traditional lantern (chiragh) sits on the left two-thirds
- The lantern has a soft inner glow (no literal flame)
- Behind/around the lantern: a soft dawn gradient
- Type sits in the right third, paired with the lantern
- Background: ivory with a soft pink-to-ivory gradient

**Color Logic:**
- Primary: soft dawn pink (gradient, lantern body)
- Secondary: warm gold (lantern glow, text)
- Accent: ivory (background, lantern highlights)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│   ┌──────────┐     "Ramadan"        │
│   │          │     "Week of Mercy"  │
│   │ LANTERN  │                      │
│   │  (glow)  │     "First Ashra"    │
│   │          │     "Rehmat"         │
│   └──────────┘                      │
│                                     │
│                  "May this Ramadan  │
│                   bring mercy"      │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: Lantern at Dawn
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — gradient, lantern body)
- Secondary: #D4AF37 (warm gold — lantern glow, text)
- Accent: #FFF8E7 (ivory — background, lantern highlights)

VISUAL ELEMENTS:
- A single traditional lantern (chiragh) on the left two-thirds
- Lantern has a soft inner glow (NO literal flame)
- Behind the lantern: a soft pink-to-ivory gradient
- Type sits in the right third
- ONE focal motif (the lantern) — no second decorative element

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, right-aligned, secondary color
- Subtitle: 4% of post height, right-aligned, secondary at 85%
- Wish message: 3% of post height, right-aligned, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Lantern: left two-thirds, vertically centered
- Type: right third, centered vertically
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones
- Lantern must NOT show a literal flame — use a glow gradient only
- The lantern reads as DAWN-TIME warmth, not as night-time only
- ONE focal motif (the lantern)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 06 — Watercolor Petal
**Mood:** Soft, painterly, organic
**Type:** Centered, floating
**Aspect:** 1:1

**Visual Theme:**
- A soft watercolor wash in dawn pink sweeps from one corner
- A single stylized petal shape sits in the upper third as a hero
  motif (NOT a rose, NOT a heart — a single abstract petal form)
- Type sits in the lower half, floating in the calm
- Background: ivory
- The hand-painted feeling is the whole point

**Color Logic:**
- Primary: soft dawn pink (watercolor wash, petal)
- Secondary: warm gold (petal accent, text)
- Accent: ivory (background)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│  ░░░░░ wash sweeps                  │
│  ░░░░░░░░ from top-left             │
│ ░░░░░░░░░░                          │
│ ░░░░░░░░░░      ❀                   │
│ ░░░░░░░░░░                          │
│                                     │
│       "Ramadan - Week of Mercy"     │
│       "First Ashra: Rehmat (Mercy)" │
│                                     │
│       "May this Ramadan bring       │
│        Allah's mercy"               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: Watercolor Petal
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — watercolor wash, petal)
- Secondary: #D4AF37 (warm gold — petal accent, text)
- Accent: #FFF8E7 (ivory — background)

VISUAL ELEMENTS:
- A soft watercolor wash in dawn pink sweeps from one corner,
  fading out as it goes
- A single stylized petal shape in the upper third as the hero
  motif (NOT a rose, NOT a heart — a single abstract petal form)
- Type sits in the lower half, floating in the calm
- Background: ivory
- ONE focal motif (the wash + petal) — a single idea

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, accent ivory ground, secondary icons + text
- Wash: starts from top-left or top-right corner, fades diagonally
- Petal: upper third, off-center
- Type: lower half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones
- The petal must be a STYLIZED abstract form, NOT a heart shape,
  NOT a literal rose
- Watercolor look must feel HAND-PAINTED, not vector-flat
- ONE focal motif (the wash + petal)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 07 — Calligraphy of Mercy
**Mood:** Type-driven, intimate, hopeful
**Type:** Massive, the design itself
**Aspect:** 1:1

**Visual Theme:**
- The Ashra's name ("Rehmat / Mercy") is THE design — rendered in
  a luminous gold calligraphic or display serif at huge scale
- A soft dawn-pink background anchors the type
- A single hairline gold rule separates the type from the message
- No other ornament

**Color Logic:**
- Primary: soft dawn pink (background)
- Secondary: warm gold (text, hairline rule)
- Accent: ivory (NOT used in this layout)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│         R E H M A T                  │
│         (Mercy)                      │
│         ──────────── (rule)         │
│         "Ramadan - First Ashra"     │
│         "May this Ramadan bring     │
│          Allah's mercy"             │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: Calligraphy of Mercy
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — background)
- Secondary: #D4AF37 (warm gold — text, hairline rule)
- Accent: #FFF8E7 (ivory — NOT USED in this layout)

VISUAL ELEMENTS:
- The Ashra's name "Rehmat (Mercy)" is THE design
- Rendered in a calligraphic or display serif at massive scale
  (~14-16% of post height)
- A single hairline gold rule separates the type from the message
- Background: solid soft dawn pink
- NO second decorative motif. The type is the art.

TYPOGRAPHY:
- Display face: calligraphic Latin OR Didone serif
- Body face: clean sans-serif
- Hero word "Rehmat": 14-16% of post height, centered, secondary
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%
- Letter spacing on hero: +3%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Hero word: vertically and horizontally centered, dominates
- Subtitle + message: below the hero, centered
- Negative space: minimum 18% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones
- ONE focal point (the type) — type-driven
- Maximum one decorative element (the hairline rule)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 08 — Geometric Mandala (Soft)
**Mood:** Contemplative, balanced, gentle
**Type:** Centered inside the mandala
**Aspect:** 1:1

**Visual Theme:**
- A large circular geometric mandala (interlocking soft shapes) in
  soft dawn pink + gold frames the post
- The mandala stroke is in gold at 60-80% opacity
- Type sits in the clear circular negative space at the center
- Background: ivory
- The mandala is SOFTER than other Ashra specs would call for —
  rounded shapes, not sharp geometric lines

**Color Logic:**
- Primary: soft dawn pink (mandala fills, soft shapes)
- Secondary: warm gold (mandala stroke, text)
- Accent: ivory (background)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│         ╭───────────╮               │
│       ╱   mandala    ╲             │
│      │   ╭───────╮    │             │
│      │  │  "Ramadan │   │            │
│      │  │  Week of  │   │           │
│      │  │   Mercy"  │   │           │
│      │   ╰───────╯    │             │
│       ╲             ╱              │
│         ╰───────────╯               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: Geometric Mandala (Soft)
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — mandala fills)
- Secondary: #D4AF37 (warm gold — mandala stroke, text)
- Accent: #FFF8E7 (ivory — background)

VISUAL ELEMENTS:
- A large circular geometric mandala in soft dawn pink + gold
- The mandala stroke is in gold at 60-80% opacity
- The mandala is SOFTER than typical — rounded shapes, not sharp lines
- Type sits in the clear circular negative space at the center
- Background: solid ivory
- ONE focal motif (the mandala) — no second decorative element

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, accent ivory ground, secondary icons + text
- Mandala: optically centered, ~70% of post width
- Type: in the mandala's clear center
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones
- The mandala must be SOFT — rounded shapes, not sharp lines
- ONE focal motif (the mandala)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 09 — Mist & Crescent
**Mood:** Atmospheric, dreamlike, gentle
**Type:** Centered, floating
**Aspect:** 1:1

**Visual Theme:**
- 3-4 horizontal bands of soft dawn-pink mist layer across the post
- Each band is at low opacity, creating depth
- A small crescent breaks through the topmost band
- Type sits in a calm band of negative space
- Background: ivory
- The hand-painted feeling carries through

**Color Logic:**
- Primary: soft dawn pink (mist bands)
- Secondary: warm gold (crescent, text)
- Accent: ivory (background)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│ ░░░░░░░ mist ░░░░░░░ ☾              │
│ ░░░░░░░░░░░░░░░░░░░░░░              │
│                                     │
│       "Ramadan - Week of Mercy"     │
│                                     │
│ ░░░░░░░░░░░░░░░░░░░░░░              │
│       "First Ashra: Rehmat (Mercy)" │
│       "May this Ramadan bring       │
│        Allah's mercy"               │
│                                     │
│ ░░░░░░░░░░░░░░░░░░░░░░              │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 09:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: Mist & Crescent
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — mist bands)
- Secondary: #D4AF37 (warm gold — crescent, text)
- Accent: #FFF8E7 (ivory — background)

VISUAL ELEMENTS:
- 3-4 horizontal bands of soft dawn-pink mist across the post
- Each band at 20-40% opacity
- A small crescent breaking through the topmost band
- Type sits in calm negative space between the mists
- Background: ivory
- ONE focal motif (the mist field) + ONE micro (crescent)

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, accent ivory ground, secondary icons + text
- Mist bands: horizontal, asymmetric heights, varied opacities
- Type: in a calm band of negative space
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones
- Mist must feel SOFT and atmospheric, not hard-edged
- ONE focal motif (the mist field) + ONE micro (crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 10 — Heart of Mercy
**Mood:** Symbolic, gentle, abstract
**Type:** Centered, paired with the symbol
**Aspect:** 1:1

**Visual Theme:**
- An abstract soft symbol made of a crescent + a curved arc below it
  forms a "mercy" mark — NOT a literal heart, NOT a Valentine symbol
- The symbol sits in the upper-center as the hero
- Type sits in the lower half
- Background: ivory with a soft pink gradient
- The composition reads as gentleness, not romance

**Color Logic:**
- Primary: soft dawn pink (the abstract mercy mark, gradient)
- Secondary: warm gold (mark accent, text)
- Accent: ivory (background)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│            ☾                        │
│           ╱                          │
│          ╱                           │
│         ╱                            │
│                                     │
│                                     │
│       "Ramadan - Week of Mercy"     │
│       "First Ashra: Rehmat (Mercy)" │
│                                     │
│       "May this Ramadan bring       │
│        Allah's mercy"               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Ramadan 1st Ashra" for
Gull Real Estate & Builders.

LAYOUT: Heart of Mercy
EVENT TITLE: "Ramadan - Week of Mercy"
GREETING SUBTITLE: "First Ashra: Rehmat (Mercy)"
WISH MESSAGE: "May this Ramadan bring Allah's mercy"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #E8B4B8 (soft dawn pink — the abstract mercy mark, gradient)
- Secondary: #D4AF37 (warm gold — mark accent, text)
- Accent: #FFF8E7 (ivory — background)

VISUAL ELEMENTS:
- An abstract soft symbol: a small crescent + a single curved arc
  below it, forming a "mercy" mark
- The symbol is NOT a literal heart, NOT a Valentine symbol,
  NOT a romantic shape
- It is a crescent cradled by a single arc — symbolic, not narrative
- The symbol sits in the upper-center as the hero
- Type sits in the lower half
- Background: ivory with a soft pink gradient
- ONE focal motif (the mercy mark) — no second decorative element

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Mercy mark: upper-center, ~25% of post height
- Type: lower half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO celebration elements
- NO bird, nest, or emblem in the logo space
- NO emerald or violet tones
- The mark must be CRESCENT + ARC, NOT a heart shape, NOT a
  Valentine symbol, NOT a romantic motif. It is a mercy
  symbol, not a love symbol.
- The mark reads as GENTLENESS, not as romance
- ONE focal motif (the mercy mark)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given year's 1st Ashra post.

| Year's Tone | Recommended Layouts |
|-------------|---------------------|
| Default / classic dawn | 01 First Dawn, 09 Mist & Crescent |
| Soft, scattered | 02 Petal Field, 06 Watercolor Petal |
| Counting, meditative | 03 Crescent & Rosary |
| Threshold, framed | 04 Window of Dawn |
| Warm, intimate | 05 Lantern at Dawn |
| Type-driven, brand-led | 07 Calligraphy of Mercy |
| Contemplative, balanced | 08 Geometric Mandala (Soft) |
| Symbolic, gentle | 10 Heart of Mercy |
| Default rotation | 01, 04, 07, 09 (one of these per cycle) |

**Recommended rotation pattern (4 years):**
- Year 1: Layout 01 — First Dawn
- Year 2: Layout 04 — Window of Dawn
- Year 3: Layout 07 — Calligraphy of Mercy
- Year 4: Layout 09 — Mist & Crescent

This guarantees 4 visually distinct posts over a 4-year cycle, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_islamic_ramadan1_ashra_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_islamic_ramadan1_ashra_01_20270218_v1.png   (Layout 01)
gull_real_estate_builders_islamic_ramadan1_ashra_07_20270218_v1.png   (Layout 07)
gull_real_estate_builders_islamic_ramadan1_ashra_09_20270218_v1.png   (Layout 09)
```

---

## 6. CTA Bar Specification (Identical Across All 10 Layouts)

The CTA bar is the ONE element that never changes. It anchors brand recognition across all the visual variety above.

```
HEIGHT: bottom 12% of the post
GROUND COLOR: primary color of the selected layout (or ivory if the
              selected layout uses ivory as ground)
LEFT SIDE: SVG phone icon (stroke: secondary gold) + "0314 9393930" (body face)
RIGHT SIDE: SVG globe icon (stroke: secondary gold) + "gullrealestate.github.io" (body face)
DIVIDER: thin vertical line in secondary gold, 30% opacity, centered
PADDING: equal left/right padding (8% of post width)
ICON SIZE: 24x24 logical units, scalable
TEXT SIZE: 3% of post height
TEXT COLOR: secondary gold
```

### Phone Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[SECONDARY_GOLD]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
</svg>
```

### Globe Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[SECONDARY_GOLD]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <circle cx="12" cy="12" r="10"/>
  <line x1="2" y1="12" x2="22" y2="12"/>
  <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/>
</svg>
```

---

## 7. Pre-Generation Checklist

Use this for every 1st Ashra post.

```
□ Layout number selected (01-10)
□ Color palette confirmed (ONLY dawn pink + gold + ivory, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-1 micro = max 2)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary or ivory ground, gold icons
□ Aspect ratio: 1:1 default
□ Dawn rule: composition feels HOPEFUL and SOFT, not heavy or festive
□ Mood check: hopeful/gentle/merciful/compassionate/dawn-like
□ Prohibited elements reviewed (faces, prayer scenes, religious text,
  celebration elements, emerald, violet, hearts, Valentine's, etc.)
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
□ ONLY the 3 allowed colors appear in the post (no fourth crept in)
□ No emerald, no violet, no deep blue, no crimson, no black
□ Only two typefaces are used
□ Maximum two decorative motifs (one hero + optional micro)
□ CTA bar matches Section 6 spec exactly
□ Aspect ratio matches layout choice
□ Mood is hopeful and gentle, never festive (no Eid feel) or somber
□ No Valentine's imagery — mercy, not romance
□ Lanterns (if used) have glow gradients, no literal flames
□ The dotted arc (Layout 03) is NOT a literal prayer bead / tasbih
□ The mercy mark (Layout 10) is crescent+arc, NOT a heart
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Ramadan 1st Ashra-Specific)

The 1st Ashra of Ramadan (Days 1-10) is dedicated to **Rehmat (Mercy)** — the merciful opening of the holy month. The visual treatment must respect that:

- **No celebration imagery.** This is NOT Eid. The register is closer to "soft dawn" than "festival."
- **No Valentine's imagery.** The Ashra is about MERCY (divine compassion), not romance. No literal hearts, no roses-as-romance, no pink-as-love cliché. The "Heart of Mercy" mark (Layout 10) is a CRESCENT + ARC — explicitly not a heart shape.
- **No emerald, no violet.** Those palettes belong to the 2nd and 3rd Ashras. Cross-contamination is a documented failure mode of multi-Ashra posting.
- **No Eid-style festivity.** If a layout choice starts to read as "Eid card", "wedding invite", or "party poster", stop.
- **No religious text.** A greeting in English is fine. Verses and Arabic script are not used.
- **No worship scenes.** The Ashra is honored in the greeting, not depicted literally.
- **No mosque imagery with people.** A stylized arch or window is fine. A mosque with worshippers is not.
- **The dotted arc (Layout 03) is a counting line, NOT a tasbih / prayer bead / rosary.** It is abstract dots in an arc. No string, no thread, no beads on a cord.
- **The "Heart of Mercy" (Layout 10) is a CRESCENT cradled by an ARC.** It is a mercy symbol, not a love symbol. The crescent is the dominant element; the arc is subordinate.

The single most important rule for this spec:
> **Soft dawn, not romantic dawn. Mercy, not love. A beginning, not a celebration.**

When in doubt: **subtract, don't add.** A simpler post is more respectful than a busier one.

---

**Document Version:** 1.0 - Ramadan 1st Ashra (Rehmat) Post Specification
**Last Updated:** July 18, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Ramadan 1st Ashra annual posts
