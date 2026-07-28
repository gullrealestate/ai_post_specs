# Gull Real Estate & Builders - Eid-ul-Adha Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Eid-ul-Adha** (10th Dhul Hijjah — the Festival of Sacrifice, also called Eid Qurbani). It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be published with visual variety year over year.

Eid-ul-Adha is the **second Eid** in the Islamic calendar — and it has a different character from Eid-ul-Fitr. Where Eid-ul-Fitr is bright celebration of the spirit of togetherness, **Eid-ul-Adha is a more grounded, earnest celebration** — it commemorates the willingness of Ibrahim (AS) to sacrifice in obedience to Allah, and the Muslim practice of Qurbani (sacrifice). The visual register is **festive but EARNEST, earthy, and dignified**. It is celebration grounded in devotion, not material celebration.

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
❌ NO Western-style party imagery (balloons, confetti, party hats,
   fireworks, "happy birthday" aesthetic, neon colors)
❌ NO excessive gold that reads as gaudy
❌ NO low-quality, pixelated, or busy backgrounds
❌ NO content that could be read as inflammatory or disrespectful
❌ NO realistic animal imagery, NO butchered animal imagery,
   NO blood, NO sacrifice scenes depicted literally
❌ NO commercialization of the sacrifice (no shopping/gift-giving aesthetic)
```

---

## 2. Strict Design Language (Applies to All 10 Layouts)

This is the spine of the spec. The 10 layouts all live inside these rules.

### 2.1 Color Discipline
```
- ONLY THREE COLORS are allowed in the entire post:
  * Primary: #D2691E (earthy amber)
  * Secondary: #2E5A3A (deep forest green)
  * Accent: #FFF8E7 (warm white)
- No fourth color. No exceptions.
- Gradient stops are allowed ONLY between Primary and Secondary
  (the amber and forest green natural flow), or between Primary
  and Accent (amber and warm white).
- The Primary (earthy amber) is the festive-but-grounded element —
  used for type, decorative motifs, lantern glows, and the
  abstract sacrifice motif.
- The Secondary (deep forest green) is the grounding element —
  used for backgrounds and as a deep companion to the amber.
- The Accent (warm white) is the breathing room — used as
  background in part of the composition, for text contrast, and
  as a clean grounding color.
- Backgrounds: solid warm white, solid forest green, or an
  amber-to-forest-green gradient. NOTHING else.
- Text contrast: AAA where possible, AA at minimum
```

### 2.2 Typography Discipline
```
- Use EXACTLY TWO typefaces per post:
  * One display face (the EVENT TITLE)
  * One body face (subtitle, message, CTA)
- The display face can be a refined serif (Didone or modern
  transitional), an elegant calligraphic Latin (the calligraphic
  option suits Eid-ul-Adha's earnest tone), or a clean modern
  sans.
- The body face is always a clean, highly legible sans-serif.
- Type sizes (as % of post height):
  * Event Title: 9-11%
  * Subtitle / Greeting: 4-5%
  * Wish Message: 3-4%
  * CTA: 3%
- Letter spacing on the title: +1% to +3%
- Title and message must remain readable at 200×200 thumbnail size
```

### 2.3 Composition Discipline
```
- One focal point only. The eye should land on it within 0.5 seconds.
- Grid: 12-column virtual grid; elements snap to thirds or halves.
- Negative space: minimum 15% of the post must be empty. Slightly
  more breathing room than Eid-ul-Fitr — the composition should
  feel EARNEST, not crowded.
- The CTA bar always sits in the bottom 12% of the post.
- The logo space always sits in the top-left 18% × 18% box.
- The event title is always centered on the dominant axis.
- GROUNDED RULE: the composition should feel GROUNDED, EARTHY,
  and EARNEST. Decoration is allowed but with more restraint
  than Eid-ul-Fitr.
- No element may overlap the logo space or the CTA bar.
```

### 2.4 Decorative Discipline
```
- Decorative elements are SYMBOLIC and RESTRAINED.
- Allowed motifs: crescent, star, traditional lantern (chiragh,
  no literal flame), geometric Islamic patterns (arabesque,
  tessellation), mosque silhouettes (stylized, non-identifiable,
  NO people inside), stylized floral motifs (subtle), arch/mihrab
  (line work), abstract animal silhouette (Qurbani reference,
  ONLY in Layout 01, with extreme care), abstract curves (NOT
  literal hands), small abstract stone-like forms (the stones
  at Mina, ONLY in Layout 08).
- Maximum TWO decorative motifs per post. (Eid-ul-Adha is
  MORE RESTRAINED than Eid-ul-Fitr, which allowed 3.)
- Decorative opacity: hero motif 60-100%, micro-element 20-40%.
- Patterns are reserved for backgrounds only, at ≤15% opacity.
- No decorative element may be placed inside the logo space.
- Lanterns, when used, must NOT show a literal flame. Use a glow gradient.
- Mosque silhouettes (when used) must be STYLIZED, non-identifiable,
  and contain NO people inside. They are pure geometric shape.
- CRITICAL — STYLIZED ANIMAL (Layout 01): If the abstract Qurbani
  animal silhouette is used, it MUST be:
  - A SINGLE, abstract, artistic form
  - Stylized to the point of being almost a shape, not a creature
  - NOT a literal sheep/goat with anatomical detail
  - NOT depicting any specific real animal breed
  - NOT showing the act of sacrifice (no knife, no blood, no altar)
  - Standing still, in a calm dignified pose
  - See Layout 01 for the full rule.
```

### 2.5 Mood Discipline
```
Eid-ul-Adha is a celebration grounded in sacrifice and obedience.

ALLOWED MOODS:
  - Joyful
  - Grateful
  - Earnest
  - Generous
  - Festive (in a grounded, dignified Islamic way)
  - Devoted
  - Warm
  - Together

NOT ALLOWED MOODS (would betray the spirit of this Eid):
  - Western-party (balloons, confetti, neon, "happy birthday" feel)
  - Loud or chaotic
  - Materialistic (no shopping, no gift-giving aesthetic)
  - Gaudy or excessive gold
  - Solemn (this is STILL CELEBRATION, just more grounded than Fitr)
  - Sober or mournful (the sacrifice is honored, not mourned)
  - Decorative-for-its-own-sake
  - Gratuitous (Eid-ul-Adha is EARNEST, not excessive)

If a layout choice starts to read as "birthday card", "Western
party invite", "shopping mall poster", or "butcher's advertisement",
stop. Eid-ul-Adha is dignified Islamic celebration — festive, but
grounded in sacrifice, obedience, and generosity.
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

## 3. The 10 Eid-ul-Adha Layouts

Each layout is a complete design system. Pick the layout that matches this year's mood, then run the prompt.

### Layout 01 — Stylized Sacrifice
**Mood:** Earnest, dignified, the Qurbani reference
**Type:** Centered, paired with the silhouette
**Aspect:** 1:1

**Visual Theme:**
- A single abstract artistic animal silhouette in the lower half
- The animal is the Qurbani reference (sheep/goat), but rendered
  as a CALM, DIGNIFIED artistic shape — almost a symbol
- The silhouette is in deep forest green on a warm white background
- A small crescent + star in the upper third as a micro-element
- Type sits above the animal, in the upper half

**Color Logic:**
- Primary: earthy amber (text, decorative line)
- Secondary: deep forest green (animal silhouette, gradient)
- Accent: warm white (background)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│   "Eid-ul-Adha Mubarak"             │
│   "Wishing you peace                │
│    and blessings"                   │
│                                     │
│                                     │
│                                     │
│      ╱─────╲                        │
│     │ abstract │                     │
│     │   (Q)    │   (Q = Qurbani)    │
│     │          │                     │
│      ╲──────╱                        │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Stylized Sacrifice
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — text, decorative line)
- Secondary: #2E5A3A (deep forest green — animal silhouette, gradient)
- Accent: #FFF8E7 (warm white — background)

VISUAL ELEMENTS:
- A single abstract artistic animal silhouette in the lower half
- The animal is the Qurbani reference (sheep/goat), but rendered
  as a CALM, DIGNIFIED artistic shape — almost a symbol
- A small crescent + star in the upper third as a micro-element
- Type sits above the animal, in the upper half
- Background: warm white
- ONE focal motif (the abstract animal) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, secondary forest green ground, accent icons + text
- Animal silhouette: lower half, ~30% of post width
- Crescent + star: upper third
- Type: upper half, centered
- Negative space: minimum 18% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES (CRITICAL for this layout):
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- CRITICAL — THE ANIMAL SILHOUETTE MUST BE:
  * A SINGLE, ABSTRACT, ARTISTIC shape — almost a symbol
  * STYLIZED to the point of being more a shape than a creature
  * NOT a literal sheep/goat with anatomical detail (no visible
    eyes, no mouth, no detailed legs, no detailed wool, no
    detailed horns)
  * NOT depicting any specific real animal breed
  * NOT showing the act of sacrifice (no knife, no blood, no
    altar, no ropes, no restraint)
  * Standing still, in a calm dignified pose
  * Drawn as a SINGLE SIMPLE SILHOUETTE, not a detailed
    illustration
  * The animal reads as SYMBOL, not as creature
- The silhouette must be PROCEED WITH CARE level — it is the
  most sensitive visual element in this spec

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 02 — Lantern of Sacrifice
**Mood:** Warm, deep, contemplative Eid
**Type:** Off-center, paired with the lantern
**Aspect:** 1:1

**Visual Theme:**
- A single traditional lantern (chiragh) sits on the left two-thirds
- The lantern has a soft inner amber glow (no literal flame)
- The lantern is deeper and more grounded than Eid-ul-Fitr's
- Type sits in the right third
- Background: deep forest green

**Color Logic:**
- Primary: earthy amber (lantern glow, text)
- Secondary: deep forest green (background)
- Accent: warm white (lantern highlights, text contrast)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│   ┌──────────┐     "Eid-ul-Adha"   │
│   │          │     "Mubarak"       │
│   │ LANTERN  │                      │
│   │  (glow)  │     "Wishing you    │
│   │          │      peace and      │
│   └──────────┘      blessings"     │
│                                     │
│                                     │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Lantern of Sacrifice
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — lantern glow, text)
- Secondary: #2E5A3A (deep forest green — background)
- Accent: #FFF8E7 (warm white — lantern highlights, text contrast)

VISUAL ELEMENTS:
- A single traditional lantern (chiragh) on the left two-thirds
- The lantern has a soft inner amber glow (NO literal flame)
- The lantern is DEEPER and more GROUNDED than Eid-ul-Fitr's
- Type sits in the right third
- ONE focal motif (the lantern) — no second decorative element

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, right-aligned, accent color
- Subtitle: 4% of post height, right-aligned, accent at 85%
- Wish message: 3% of post height, right-aligned, accent at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, secondary ground, accent icons + text
- Lantern: left two-thirds, vertically centered
- Type: right third, centered vertically
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- Lantern must NOT show a literal flame — use a glow gradient only
- The lantern reads as DEEPER and more GROUNDED than Eid-ul-Fitr's
- ONE focal motif (the lantern)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 03 — Earth's Gift
**Mood:** Earthy, grounded, generous harvest
**Type:** Centered, in the calm above
**Aspect:** 1:1

**Visual Theme:**
- A soft horizon line bisects the post at the lower third
- Below the horizon: a warm amber ground (the earth)
- Above the horizon: a warm white-to-amber gradient (the sky)
- A small crescent + star in the upper third
- Type sits in the calm sky above
- A few abstract small forms (subtle harvest/earth elements) on the ground

**Color Logic:**
- Primary: earthy amber (ground, text)
- Secondary: deep forest green (gradient, decorative)
- Accent: warm white (sky, text contrast)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│                                     │
│   "Eid-ul-Adha Mubarak"             │
│   "May your Eid be filled            │
│    with joy and sacrifice"           │
│                                     │
│   ░░░░ horizon line ░░░             │
│   ▓▓▓▓▓ earth ▓▓▓▓▓                  │
│   ▓ ▓ ▓ (subtle forms) ▓ ▓ ▓         │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Earth's Gift
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — ground, text)
- Secondary: #2E5A3A (deep forest green — gradient, decorative)
- Accent: #FFF8E7 (warm white — sky, text contrast)

VISUAL ELEMENTS:
- A soft horizon line bisects the post at the lower third
- Below the horizon: a warm amber ground (the earth)
- Above the horizon: a warm white-to-amber gradient (the sky)
- A small crescent + star in the upper third
- A few abstract small forms on the ground (subtle harvest elements,
  NOT literal plants, NOT literal produce — just abstract dots or
  soft shapes)
- Type sits in the calm sky above
- ONE focal motif (the horizon) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Horizon: at the lower third
- Crescent + star: upper third
- Type: in the calm sky above
- Negative space: minimum 18% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The ground is ABSTRACT — not a literal field, not literal
  produce, not a literal harvest scene. Just amber ground with
  subtle abstract forms.
- The composition reads as GROUNDED, not as agricultural
- ONE focal motif (the horizon) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 04 — Crescent & Star
**Mood:** Heroic-celestial, the Eid signature in earthy palette
**Type:** Centered, beneath the crescent
**Aspect:** 1:1

**Visual Theme:**
- A large amber crescent sits in the upper half
- A star sits inside or beside the crescent
- A few small stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep forest green

**Color Logic:**
- Primary: earthy amber (crescent, stars, text)
- Secondary: deep forest green (background)
- Accent: warm white (text contrast)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│     ✦       ✦                      │
│   ╱⌒⌒⌒⌒⌒⌒⌒⌒⌒⌒╲                 │
│ ╱   crescent + stars   ╲             │
│ │       ✦             │             │
│  ╲                   ╱              │
│   ╲_______________╱                │
│       ✦       ✦                    │
│                                     │
│   "Eid-ul-Adha Mubarak"             │
│   "May your Eid be filled            │
│    with joy and sacrifice"           │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Crescent & Star
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — crescent, stars, text)
- Secondary: #2E5A3A (deep forest green — background)
- Accent: #FFF8E7 (warm white — text contrast)

VISUAL ELEMENTS:
- A large amber crescent in the upper half
- A star sits inside or beside the crescent
- A few small stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep forest green
- ONE focal motif (the crescent + stars)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, secondary ground, accent icons + text
- Crescent: upper half, ~50% of post width
- Star trail: along the crescent's curve
- Type: lower half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The crescent reads as EARNEST EID, not as Halloween
- The amber must feel GROUNDED, not as bright as Eid-ul-Fitr's gold
- ONE focal motif (the crescent + stars)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 05 — Mihrab of Devotion
**Mood:** Threshold, devotional, framed
**Type:** Centered, inside the arch
**Aspect:** 1:1

**Visual Theme:**
- A stylized pointed arch (mihrab) frames the post's center
- Inside the arch: a warm amber-to-cream gradient
- The arch line is in earthy amber
- Type sits inside the arch, in the gradient
- Background outside the arch: deep forest green
- A small crescent + star at the arch's apex as a micro-element

**Color Logic:**
- Primary: earthy amber (arch line, crescent, text)
- Secondary: deep forest green (outside the arch)
- Accent: warm white (gradient inside, text)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│            ╱    ╲                    │
│           │░░░░░│                   │
│           │░░░░░│ "Eid-ul-Adha"   │
│           │░░░░░│  "Mubarak"       │
│           │░░░░░│                   │
│           │░░░░░│ "Wishing you     │
│           │░░░░░│  peace and        │
│           │░░░░░│  blessings"      │
│           ╲░░░░╱                    │
│            ╲____╱ ☾ ✦                │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Mihrab of Devotion
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — arch line, crescent, text)
- Secondary: #2E5A3A (deep forest green — outside the arch)
- Accent: #FFF8E7 (warm white — gradient inside, text)

VISUAL ELEMENTS:
- Stylized pointed arch (mihrab) framing the post's center
- Inside the arch: warm amber-to-cream gradient
- The arch line is in earthy amber
- Type sits inside the arch, in the gradient
- Background outside the arch: deep forest green
- A small crescent + star at the arch's apex as a micro-element
- ONE focal motif (the arch) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, accent color
- Subtitle: 4% of post height, centered, accent at 85%
- Wish message: 3% of post height, centered, accent at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, secondary ground, accent icons + text
- Arch: optically centered, ~55% of post width, ~70% of post height
- Type: centered inside the arch
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The arch is STYLIZED — line work, not an architectural drawing
- The arch reads as a WINDOW of devotion, not a mosque
- ONE focal motif (the arch) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 06 — Geometric Abundance
**Mood:** Earthy, festive-but-grounded
**Type:** Centered, above the pattern
**Aspect:** 1:1

**Visual Theme:**
- A radial geometric pattern in the lower half
- The pattern is a modern Islamic geometric star (8 or 12 points)
- The pattern is in earthy amber with forest green inner fills
- Type sits in the upper half, in the cream space
- Background: warm white with a subtle forest green gradient

**Color Logic:**
- Primary: earthy amber (pattern stroke, text)
- Secondary: deep forest green (pattern fills, gradient)
- Accent: warm white (background, text contrast)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│   "Eid-ul-Adha Mubarak"             │
│   "May your Eid be filled            │
│    with joy and sacrifice"           │
│                                     │
│            ✦                        │
│          ╱  ╲                       │
│        ╱  ✦✦  ╲                     │
│       │  ✦  ✦  │                    │
│        ╲  ✦✦  ╱                     │
│          ╲  ╱                       │
│            ✦                        │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Geometric Abundance
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — pattern stroke, text)
- Secondary: #2E5A3A (deep forest green — pattern fills, gradient)
- Accent: #FFF8E7 (warm white — background, text contrast)

VISUAL ELEMENTS:
- A radial geometric pattern in the lower half
- The pattern is a modern Islamic geometric star (8 or 12 points)
- The pattern is in earthy amber with forest green inner fills
- Type sits in the upper half, in the cream space
- Background: warm white with a subtle forest green gradient
- ONE focal motif (the geometric pattern)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, secondary ground, accent icons + text
- Pattern: lower half, ~50% of post width
- Type: upper half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The pattern is a MODERN ISLAMIC GEOMETRIC STAR, not a firework,
  not an explosion, not a Western celebration burst
- The earthy palette keeps it GROUNDED, not as bright as Eid-ul-Fitr
- ONE focal motif (the geometric pattern)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 07 — Calligraphy of Sacrifice
**Mood:** Type-driven, the day's word
**Type:** Massive, the design itself
**Aspect:** 1:1

**Visual Theme:**
- "Eid-ul-Adha Mubarak" is THE design — rendered in a luminous
  calligraphic or display serif at huge scale
- The type appears to glow against the deep forest green
- A single hairline amber rule separates title from message
- Background: deep forest green
- A small crescent + star as a micro-element

**Color Logic:**
- Primary: earthy amber (text, hairline rule, crescent, star)
- Secondary: deep forest green (background)
- Accent: warm white (NOT used in this layout)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│                                     │
│   E I D - U L - A D H A             │
│         M U B A R A K               │
│         ──────────── (rule)         │
│         "May your Eid be filled     │
│          with joy and sacrifice"    │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Calligraphy of Sacrifice
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — text, hairline rule, crescent, star)
- Secondary: #2E5A3A (deep forest green — background)
- Accent: #FFF8E7 (warm white — NOT USED in this layout)

VISUAL ELEMENTS:
- "Eid-ul-Adha Mubarak" is THE design — rendered in a calligraphic
  or display serif at massive scale (~13-15% of post height)
- The type appears to glow against the deep forest green
- A single hairline amber rule separates title from message
- A small crescent + star as a micro-element
- Background: solid deep forest green
- NO second decorative motif. The type is the art.

TYPOGRAPHY:
- Display face: calligraphic Latin OR Didone serif
- Body face: clean sans-serif
- Hero phrase "Eid-ul-Adha Mubarak": 13-15% of post height, centered, primary
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%
- Letter spacing on hero: +3%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, secondary ground, accent icons + text
- Hero phrase: vertically and horizontally centered, dominates
- Subtitle + message: below the hero, centered
- Negative space: minimum 18% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- ONE focal point (the type) — type-driven
- Maximum one decorative element (the hairline rule) + one micro

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 08 — Stones of Ibrahim
**Mood:** Symbolic, devotional, the Mina reference
**Type:** Centered, paired with the stones
**Aspect:** 1:1

**Visual Theme:**
- Three small abstract stone-like forms sit in the lower half
- The stones are the Mina reference (the stoning of the devil ritual
  performed during Hajj)
- The stones are STYLIZED, NOT realistic pebbles
- A small crescent + star sits above the stones as a micro-element
- Type sits in the upper half, in the calm
- Background: warm white

**Color Logic:**
- Primary: earthy amber (stones, text, decorative)
- Secondary: deep forest green (gradient, micro-element)
- Accent: warm white (background)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│   "Eid-ul-Adha Mubarak"             │
│   "Wishing you peace                │
│    and blessings"                   │
│                                     │
│                                     │
│       ◯   ◯   ◯                     │
│      (3 abstract stones)            │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Stones of Ibrahim
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — stones, text, decorative)
- Secondary: #2E5A3A (deep forest green — gradient, micro-element)
- Accent: #FFF8E7 (warm white — background)

VISUAL ELEMENTS:
- Three small abstract stone-like forms sit in the lower half
- The stones are the Mina reference (the stoning of the devil
  ritual performed during Hajj)
- The stones are STYLIZED geometric forms, NOT realistic pebbles
- A small crescent + star sits above the stones as a micro-element
- Type sits in the upper half, in the calm
- Background: warm white
- ONE focal motif (the three stones) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Stones: lower half, three small abstract forms in a row
- Crescent + star: above the stones
- Type: upper half, centered
- Negative space: minimum 18% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- CRITICAL — THE STONES MUST BE:
  * STYLIZED abstract geometric forms (smooth ovals, soft circles)
  * NOT realistic pebbles with detailed texture
  * NOT shown being thrown (no motion, no hand, no trajectory)
  * Just three calm, still, symbolic forms in a row
  * The stones read as SYMBOL, not as action
- ONE focal motif (the three stones) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 09 — Arabesque Frame
**Mood:** Contemplative, balanced, earthy Eid
**Type:** Centered inside the frame
**Aspect:** 1:1

**Visual Theme:**
- A large circular geometric arabesque frame surrounds the post's center
- The frame is rendered in earthy amber with green inner shapes
- Type sits in the clear circular negative space at the center
- Background: warm white
- A small crescent + star at the top of the frame

**Color Logic:**
- Primary: earthy amber (frame stroke, crescent, text)
- Secondary: deep forest green (frame shapes, gradient)
- Accent: warm white (background, text)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│         ╭───────────╮               │
│       ╱   arabesque  ╲             │
│      │   ╭───────╮    │             │
│      │  │ "Eid-ul-  │   │            │
│      │  │  Adha     │   │           │
│      │  │ Mubarak"  │   │           │
│      │   ╰───────╯    │             │
│       ╲             ╱              │
│         ╰───────────╯               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 09:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Arabesque Frame
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — frame stroke, crescent, text)
- Secondary: #2E5A3A (deep forest green — frame shapes, gradient)
- Accent: #FFF8E7 (warm white — background, text)

VISUAL ELEMENTS:
- A large circular geometric arabesque frame surrounds the post's center
- The frame is rendered in earthy amber with green inner shapes
- A small crescent + star at the top of the frame
- Type sits in the clear circular negative space at the center
- Background: warm white
- ONE focal motif (the arabesque frame) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Frame: optically centered, ~70% of post width
- Type: in the frame's clear center
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The arabesque must be SYMMETRIC and CLEAN, not chaotic
- The earthy palette keeps it GROUNDED, not as bright as Eid-ul-Fitr
- ONE focal motif (the arabesque frame) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 10 — Open Hands of Generosity
**Mood:** Generous, sincere, abstract
**Type:** Centered, between the abstract curves
**Aspect:** 1:1

**Visual Theme:**
- An abstract pair of curved lines, gently cupped, suggesting
  "giving generously" — NOT a literal hand, NOT a hand-drawing
- The curves are simple amber line work on a deep forest green
  background
- A small crescent + star sits above the curves as a micro-element
- Type sits below the curves, in the calm
- The composition reads as GIVING, not receiving

**Color Logic:**
- Primary: earthy amber (the abstract curves, crescent, text)
- Secondary: deep forest green (background)
- Accent: warm white (text contrast)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│        ╭─────────╮                  │
│       ╱  curves   ╲                 │
│      │   ABSTRACT  │                │
│       ╲           ╱                 │
│        ╰─────────╯                  │
│                                     │
│   "Eid-ul-Adha Mubarak"             │
│   "Wishing you peace                │
│    and blessings"                   │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Adha Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Open Hands of Generosity
EVENT TITLE: "Eid-ul-Adha Mubarak"
GREETING SUBTITLE: "Wishing you peace and blessings"
WISH MESSAGE: "May your Eid be filled with joy and sacrifice"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders Family"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #D2691E (earthy amber — abstract curves, crescent, text)
- Secondary: #2E5A3A (deep forest green — background)
- Accent: #FFF8E7 (warm white — text contrast)

VISUAL ELEMENTS:
- An abstract pair of curved lines, gently cupped, suggesting
  "giving generously" — NOT a literal hand, NOT a hand-drawing
- The curves are simple amber line work
- A small crescent + star sits above the curves as a micro-element
- Type sits below the curves, in the calm
- ONE focal motif (the abstract curves) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, accent color
- Subtitle: 4% of post height, centered, accent at 85%
- Wish message: 3% of post height, centered, accent at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, secondary ground, accent icons + text
- Abstract curves: upper-center, ~30% of post width
- Crescent + star: above the curves
- Type: lower half, centered
- Negative space: minimum 18% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- CRITICAL: the curves are ABSTRACT, NOT a literal hand. NO fingers,
  NO palm lines, NO wrist, NO skin tone, NO body. Two simple
  curves like cupped parentheses — nothing more.
- The composition reads as GIVING, not as receiving
- ONE focal motif (the abstract curves) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given year's Eid-ul-Adha post.

| Year's Tone | Recommended Layouts |
|-------------|---------------------|
| Default / earnest Qurbani | 01 Stylized Sacrifice, 08 Stones of Ibrahim |
| Earthy, grounded | 03 Earth's Gift, 02 Lantern of Sacrifice |
| Heroic-celestial | 04 Crescent & Star |
| Threshold, devotional | 05 Mihrab of Devotion |
| Earthy festive | 06 Geometric Abundance |
| Type-driven, brand-led | 07 Calligraphy of Sacrifice |
| Contemplative, balanced | 09 Arabesque Frame |
| Generous, sincere | 10 Open Hands of Generosity |
| Default rotation | 01, 04, 07, 09 (one of these per cycle) |

**Recommended rotation pattern (4 years):**
- Year 1: Layout 01 — Stylized Sacrifice
- Year 2: Layout 04 — Crescent & Star
- Year 3: Layout 07 — Calligraphy of Sacrifice
- Year 4: Layout 09 — Arabesque Frame

This guarantees 4 visually distinct posts over a 4-year cycle, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_islamic_eid_ul_adha_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_islamic_eid_ul_adha_01_20270527_v1.png   (Layout 01)
gull_real_estate_builders_islamic_eid_ul_adha_07_20270527_v1.png   (Layout 07)
gull_real_estate_builders_islamic_eid_ul_adha_09_20270527_v1.png   (Layout 09)
```

---

## 6. CTA Bar Specification (Identical Across All 10 Layouts)

The CTA bar is the ONE element that never changes. It anchors brand recognition across all the visual variety above.

```
HEIGHT: bottom 12% of the post
GROUND COLOR: primary or secondary color of the selected layout
LEFT SIDE: SVG phone icon (stroke: accent warm white) + "0314 9393930"
RIGHT SIDE: SVG globe icon (stroke: accent warm white) + "gullrealestate.github.io"
DIVIDER: thin vertical line in accent warm white, 30% opacity, centered
PADDING: equal left/right padding (8% of post width)
ICON SIZE: 24x24 logical units, scalable
TEXT SIZE: 3% of post height
TEXT COLOR: accent warm white
```

### Phone Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[ACCENT_WHITE]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
</svg>
```

### Globe Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[ACCENT_WHITE]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <circle cx="12" cy="12" r="10"/>
  <line x1="2" y1="12" x2="22" y2="12"/>
  <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/>
</svg>
```

---

## 7. Pre-Generation Checklist

Use this for every Eid-ul-Adha post.

```
□ Layout number selected (01-10)
□ Color palette confirmed (ONLY amber + forest green + warm white, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-1 micro = max 2)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary or secondary ground, accent icons
□ Aspect ratio: 1:1 default
□ Grounded rule: composition feels EARNEST, GROUNDED, not as bright as Fitr
□ Mood check: joyful/grateful/earnest/generous/dedicated/warm
□ Prohibited elements reviewed (faces, prayer scenes, religious text,
  Western party imagery, realistic animals, sacrifice scenes, blood,
  shopping aesthetic, etc.)
□ Filename follows convention
```

## 8. Post-Generation Checklist

```
□ No faces or identifiable people
□ No mosque with worshippers or prayer scenes
□ No religious text, verses, or Arabic script
□ No political party logos or symbols
□ No Western party imagery (balloons, confetti, party hats, fireworks)
□ No bird, nest, or emblem in or near the logo space
□ Logo space is clean and properly reserved
□ User-uploaded logo colors harmonize with the post's palette
□ Text is readable at 200×200 thumbnail size
□ ONLY the 3 allowed colors appear in the post (no fourth crept in)
□ Only two typefaces are used
□ Maximum two decorative motifs (one hero + optional micro)
□ CTA bar matches Section 6 spec exactly
□ Aspect ratio matches layout choice
□ Mood is festive but grounded, never Western-party or materialistic
□ Lanterns (if used) have glow gradients, no literal flames
□ IF Layout 01 used: animal silhouette is abstract symbol, NOT realistic
□ IF Layout 08 used: stones are stylized forms, NOT being thrown
□ IF Layout 10 used: curves are abstract, NOT literal hands
□ Mosque silhouettes (if used) are STYLIZED, contain NO people
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Eid-ul-Adha-Specific)

Eid-ul-Adha (10th Dhul Hijjah) is the second Eid — the Festival of Sacrifice. It commemorates Ibrahim's (AS) willingness to sacrifice his son in obedience to Allah, and the practice of Qurbani (sacrifice) performed by Muslims worldwide. The visual treatment must respect that:

- **The sacrifice is honored, not depicted literally.** Qurbani is a sacred act. The post honors the devotion behind it; it does NOT show the act itself. NO knife, NO blood, NO altar, NO butchered animal imagery.
- **The stylized animal (Layout 01) is PROCEED WITH CARE.** It must be a SINGLE, abstract, artistic shape — almost a symbol, not a creature. NO anatomical detail, NO realistic breed, NO sacrifice act. The animal reads as SYMBOL, not as creature.
- **The stones (Layout 08) are symbols, not actions.** They are three calm, still, stylized forms in a row. NOT being thrown, NOT shown in motion, NO hand, NO trajectory. The stones read as SYMBOL, not as action.
- **The "Open Hands" (Layout 10) are ABSTRACT CURVES, not literal hands.** Two simple curves like cupped parentheses. NO fingers, NO palm lines, NO wrist, NO skin tone, NO body. The composition reads as GIVING, not as receiving.
- **No Western party imagery.** No balloons, no confetti, no party hats, no fireworks, no neon, no shopping aesthetic, no gift-giving imagery. Eid-ul-Adha is devotion, not consumption.
- **Gold is more restrained than Eid-ul-Fitr.** Earthy amber is the festive element, not bright gold. The palette is GROUNDED, not bright. The composition should feel earnest, not lavish.
- **No religious text.** A greeting in English is fine. Verses and Arabic script are not used.
- **No worship scenes.** The day is honored in the greeting, not depicted literally.
- **Decorative restraint.** Eid-ul-Adha is EARNEST, not abundant. Maximum 2 motifs per post (vs 3 for Eid-ul-Fitr). Pattern opacity stays at ≤15% (vs 20% for Eid-ul-Fitr). The composition should feel more sober.

The single most important rule for this spec:
> **Festive, but grounded in devotion. Earnest, not lavish. Sacrifice honored, not depicted.**

When in doubt: **subtract, don't add.** A simpler post is more respectful than a busier one. If a layout choice starts to read as "butcher's advertisement", "shopping mall poster", or "Western party invite", stop.

---

**Document Version:** 1.0 - Eid-ul-Adha Post Specification
**Last Updated:** July 28, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Eid-ul-Adha annual posts
