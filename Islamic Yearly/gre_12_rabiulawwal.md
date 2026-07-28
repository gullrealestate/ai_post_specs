# Gull Real Estate & Builders - Milad-un-Nabi Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Milad-un-Nabi / Eid-e-Milad** (12th Rabi-ul-Awal — the celebration of the birth of the Holy Prophet ﷺ). It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be published with visual variety year over year.

Milad-un-Nabi is the final Islamic event in the natural sequence — and it is **tonally distinct from both the Eids and the Ashras**. The day is observed with deep love, respect, and reverence. It is NOT a Western-style party. It is NOT festive in the Eid-ul-Fitr sense. The visual register is **dignified, reverent, soft, and reflective** — closer to the Ramadan Ashra specs in tone, but with its own character of love and respect. The post should always feel like honoring something sacred.

**This is the final Islamic event spec. After this, the sequence moves to the Pakistani national events and the cultural events.**

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
❌ NO faces or identifiable people (CRITICAL — the Prophet ﷺ
   is NEVER depicted, and no figures, silhouettes, or implied
   people anywhere in the post)
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
❌ NO celebrity likenesses, NO religious/political leader images
```

---

## 2. Strict Design Language (Applies to All 10 Layouts)

This is the spine of the spec. The 10 layouts all live inside these rules.

### 2.1 Color Discipline
```
- ONLY THREE COLORS are allowed in the entire post:
  * Primary: #2C5530 (deep heritage green)
  * Secondary: #D4AF37 (royal gold)
  * Accent: #1A1A1A (deep black)
- No fourth color. No exceptions.
- Gradient stops are allowed ONLY between Primary and Secondary
  (the green and gold natural flow), or between Primary and
  Accent (green and black).
- The Primary (heritage green) is the dominant element — used
  for backgrounds and as the foundation of the composition.
  This is HERITAGE green, the green of South Asian Islamic
  tradition.
- The Secondary (royal gold) is the LUMINOUS element — used
  for type, decorative motifs, lantern glows, and CTA icons.
  Gold is allowed but should feel REVERENT, not lavish.
- The Accent (deep black) is the GROUNDING element — used as
  a deep companion and for the deepest shadows. Black is what
  keeps the gold from becoming gaudy.
- Backgrounds: solid heritage green, solid black, or a
  green-to-black gradient. NOTHING else.
- Text contrast: AAA where possible, AA at minimum
```

### 2.2 Typography Discipline
```
- Use EXACTLY TWO typefaces per post:
  * One display face (the EVENT TITLE)
  * One body face (subtitle, message, CTA)
- The display face can be a refined serif (Didone or modern
  transitional) or an elegant calligraphic Latin (the
  calligraphic option suits Milad's reverent tone particularly
  well — flowing terminals echo the love and respect of the day).
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
- Negative space: minimum 15% of the post must be empty. The
  composition should feel REVERENT, not crowded.
- The CTA bar always sits in the bottom 12% of the post.
- The logo space always sits in the top-left 18% × 18% box.
- The event title is always centered on the dominant axis.
- REVERENT RULE: the composition should feel SOFT, DIGNIFIED,
  and HONORING. Decoration is allowed (more than the Ashra
  specs, less than Eid-ul-Fitr), but always with restraint.
- No element may overlap the logo space or the CTA bar.
```

### 2.4 Decorative Discipline
```
- Decorative elements are SYMBOLIC and REVERENT.
- Allowed motifs: crescent, star, traditional lantern (chiragh,
  no literal flame), ornate geometric Islamic patterns (arabesque,
  tessellation), mosque silhouettes (stylized, non-identifiable,
  NO people inside), stylized floral motifs (rose, jasmine —
  common in South Asian Islamic heritage), arch/mihrab (line
  work), abstract ornamental rules and frames.
- Maximum TWO decorative motifs per post. (Same cap as Eid-ul-Adha —
  Milad is REVERENT, not abundant.)
- Decorative opacity: hero motif 60-100%, micro-element 20-40%.
- Patterns are reserved for backgrounds or as decorative frames,
  at ≤15% opacity.
- No decorative element may be placed inside the logo space.
- Lanterns, when used, must NOT show a literal flame. Use a glow gradient.
- Mosque silhouettes (when used) must be STYLIZED, non-identifiable,
  and contain NO people inside. They are pure geometric shape.
```

### 2.5 Mood Discipline
```
Milad-un-Nabi is the celebration of the birth of the Prophet ﷺ,
observed with deep love, respect, and reverence.

ALLOWED MOODS:
  - Reverent
  - Dignified
  - Loving
  - Respectful
  - Soft
  - Reflective
  - Warm (in a reverent way, not in a party way)
  - Honoring

NOT ALLOWED MOODS (would betray the spirit of Milad):
  - Western-party (balloons, confetti, neon, "happy birthday" feel)
  - Loud or chaotic
  - Gaudy or excessive gold
  - Celebratory in a Western party sense
  - Materialistic
  - Solemn or mournful (this is LOVE, not grief)
  - Decorative-for-its-own-sake

If a layout choice starts to read as "birthday card", "Western
party invite", "wedding invitation", or "Christmas card", stop.
Milad-un-Nabi is dignified Islamic observance — loving, reverent,
honoring, but never Western party.
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

## 3. The 10 Milad-un-Nabi Layouts

Each layout is a complete design system. Pick the layout that matches this year's mood, then run the prompt.

### Layout 01 — Crescent of Birth
**Mood:** Reverent, the central symbol
**Type:** Centered, beneath the crescent
**Aspect:** 1:1

**Visual Theme:**
- A large gold crescent sits in the upper half
- A star sits inside or beside the crescent
- A few small stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep heritage green
- The composition is REVERENT, not as bright as Eid-ul-Fitr's

**Color Logic:**
- Primary: deep heritage green (background)
- Secondary: royal gold (crescent, stars, text)
- Accent: deep black (deepest shadow)

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
│   "Milad-un-Nabi Mubarak"           │
│   "Celebrating the birth            │
│    of the Holy Prophet ﷺ"          │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Crescent of Birth
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — background)
- Secondary: #D4AF37 (royal gold — crescent, stars, text)
- Accent: #1A1A1A (deep black — deepest shadow)

VISUAL ELEMENTS:
- A large gold crescent in the upper half
- A star sits inside or beside the crescent
- A few small stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep heritage green
- ONE focal motif (the crescent + stars)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Crescent: upper half, ~50% of post width
- Star trail: along the crescent's curve
- Type: lower half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people (CRITICAL — the Prophet ﷺ is never depicted)
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The crescent reads as REVERENT, not as Halloween
- The gold must feel HONORING, not gaudy
- ONE focal motif (the crescent + stars)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 02 — Ornate Mihrab
**Mood:** Threshold, ornate, devotional
**Type:** Centered, inside the arch
**Aspect:** 1:1

**Visual Theme:**
- A stylized pointed arch (mihrab) frames the post's center
- Inside the arch: an ornate gold-to-green gradient
- The arch is more ornate than other specs — with subtle gold
  pattern work at the arch's edges
- Type sits inside the arch, in the gradient
- Background outside the arch: deep heritage green
- A small crescent + star at the arch's apex as a micro-element

**Color Logic:**
- Primary: deep heritage green (outside the arch, gradient)
- Secondary: royal gold (arch line, gradient inside, text)
- Accent: deep black (gradient deepest)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│            ╱    ╲                    │
│           │░░░░░│                   │
│           │░░░░░│ "Milad-un-Nabi" │
│           │░░░░░│  "Mubarak"       │
│           │░░░░░│                   │
│           │░░░░░│ "Celebrating     │
│           │░░░░░│  the birth"      │
│           ╲░░░░╱                    │
│            ╲____╱ ☾ ✦                │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Ornate Mihrab
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — outside the arch, gradient)
- Secondary: #D4AF37 (royal gold — arch line, gradient inside, text)
- Accent: #1A1A1A (deep black — gradient deepest)

VISUAL ELEMENTS:
- Stylized pointed arch (mihrab) framing the post's center
- Inside the arch: ornate gold-to-green gradient
- The arch has subtle gold pattern work at its edges
- Type sits inside the arch, in the gradient
- Background outside the arch: deep heritage green
- A small crescent + star at the arch's apex as a micro-element
- ONE focal motif (the arch) + ONE micro (crescent + star)

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
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The arch is STYLIZED — line work, not an architectural drawing
- The arch reads as a WINDOW of devotion, not a mosque
- The ornamentation is SUBTLE, not overwhelming
- ONE focal motif (the arch) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 03 — Floral Heritage
**Mood:** Soft, warm, South Asian Islamic heritage
**Type:** Centered, framed by florals
**Aspect:** 1:1

**Visual Theme:**
- A circular floral wreath of stylized rose and jasmine surrounds
  the post's center
- The wreath is rendered in gold line work (NOT filled) on green
- Type sits in the clear center, never overlapping the wreath
- A small crescent + star at the top of the wreath
- Background: deep heritage green
- This layout evokes the floral heritage of South Asian Islamic art

**Color Logic:**
- Primary: deep heritage green (background)
- Secondary: royal gold (wreath line work, crescent, star, text)
- Accent: deep black (NOT used in this layout)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│        ❀─────❀─────❀               │
│      ❀               ❀              │
│    ❀   "Milad-un-    ❀            │
│    ❀    Nabi           ❀           │
│    ❀    Mubarak"      ❀           │
│      ❀               ❀              │
│        ❀─────❀─────❀               │
│                                     │
│   "Celebrating the birth            │
│    of the Holy Prophet ﷺ"          │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 1:1 (1080x1080) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Floral Heritage
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — background)
- Secondary: #D4AF37 (royal gold — wreath line work, crescent, star, text)
- Accent: #1A1A1A (deep black — NOT USED in this layout)

VISUAL ELEMENTS:
- A circular floral wreath of stylized rose and jasmine surrounds
  the post's center
- The wreath is rendered in gold LINE WORK (NOT filled) on green
- A small crescent + star at the top of the wreath
- Type sits in the clear center, never overlapping the wreath
- Background: deep heritage green
- ONE focal motif (the wreath) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Wreath: optically centered, ~65% of post width
- Type: in the wreath's clear center
- Crescent + star: at the top of the wreath
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The florals must be STYLIZED line work, NOT photorealistic
- The wreath reads as REVERENT Islamic heritage, not as
  Valentine's romance
- ONE focal motif (the wreath) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 04 — Lantern of Devotion
**Mood:** Warm, deep, devotional
**Type:** Off-center, paired with the lantern
**Aspect:** 1:1

**Visual Theme:**
- A single traditional lantern (chiragh) sits on the left two-thirds
- The lantern is more ornate than other specs — with subtle gold
  pattern work on its body
- The lantern has a soft inner gold glow (no literal flame)
- Type sits in the right third
- Background: deep heritage green

**Color Logic:**
- Primary: deep heritage green (background)
- Secondary: royal gold (lantern glow, lantern body, text)
- Accent: deep black (deepest shadow)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│   ┌──────────┐     "Milad-un-      │
│   │          │     Nabi"           │
│   │ LANTERN  │                      │
│   │  (glow)  │     "Mubarak"       │
│   │          │                      │
│   └──────────┘     "Celebrating     │
│                    the birth"      │
│                                     │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Lantern of Devotion
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — background)
- Secondary: #D4AF37 (royal gold — lantern glow, body, text)
- Accent: #1A1A1A (deep black — deepest shadow)

VISUAL ELEMENTS:
- A single traditional lantern (chiragh) on the left two-thirds
- The lantern is more ORNATE than other specs — with subtle gold
  pattern work on its body
- The lantern has a soft inner gold glow (NO literal flame)
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
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- Lantern must NOT show a literal flame — use a glow gradient only
- The lantern reads as DEVOTIONAL, not as celebratory
- ONE focal motif (the lantern)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 05 — Geometric Mandala
**Mood:** Contemplative, balanced, ornate
**Type:** Centered inside the mandala
**Aspect:** 1:1

**Visual Theme:**
- A large circular geometric mandala in deep heritage green + gold
- The mandala is ORNATE — more decorative than the Ashra versions
- The mandala stroke is in royal gold at 60-80% opacity
- Type sits in the clear circular negative space at the center
- Background: deep heritage green
- A small crescent + star at the top of the outermost ring

**Color Logic:**
- Primary: deep heritage green (mandala fills, background)
- Secondary: royal gold (mandala stroke, crescent, text)
- Accent: deep black (deepest ring)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│         ╭───────────╮               │
│       ╱   mandala    ╲             │
│      │   ╭───────╮    │             │
│      │  │  "Milad" │   │            │
│      │  │  un-Nabi"  │   │           │
│      │  │ Mubarak" │   │           │
│      │   ╰───────╯    │             │
│       ╲             ╱              │
│         ╰───────────╯               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Geometric Mandala
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — mandala fills, background)
- Secondary: #D4AF37 (royal gold — mandala stroke, crescent, text)
- Accent: #1A1A1A (deep black — deepest ring)

VISUAL ELEMENTS:
- A large circular geometric mandala in deep heritage green + gold
- The mandala is ORNATE — more decorative than the Ashra versions
- The mandala stroke is in royal gold at 60-80% opacity
- A small crescent + star at the top of the outermost ring
- Type sits in the clear circular negative space at the center
- Background: deep heritage green
- ONE focal motif (the mandala) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Mandala: optically centered, ~72% of post width
- Type: in the mandala's clear center
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The mandala must be SYMMETRIC and CLEAN, not chaotic
- The gold should feel HONORING, not gaudy
- ONE focal motif (the mandala) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 06 — Stained Glass
**Mood:** Jewel-like, dignified, ornate
**Type:** Centered, in the text panel
**Aspect:** 1:1

**Visual Theme:**
- A geometric stained-glass pattern fills the entire background
- The pattern is divided into clean color blocks (primary + secondary)
- A small black accent appears in 1-2 cells
- A clear, unpatterned rectangular panel in the center holds the type
- The contrast between busy pattern and clean panel IS the design

**Color Logic:**
- Primary: deep heritage green (main glass cells)
- Secondary: royal gold (text panel, secondary cells)
- Accent: deep black (1-2 glass cells, decorative)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓┌─────────────┐▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "Milad-un-  │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  Nabi"      │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "Mubarak"   │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "Celebrating"│▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓└─────────────┘▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Stained Glass
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — main glass cells)
- Secondary: #D4AF37 (royal gold — text panel, secondary cells)
- Accent: #1A1A1A (deep black — 1-2 glass cells, decorative)

VISUAL ELEMENTS:
- Geometric stained-glass pattern fills the entire background
- Pattern is divided into clean color blocks (no gradients within cells)
- Black accent appears in 1-2 glass cells
- A clear, unpatterned rectangular panel in the center holds the type
- The contrast between busy pattern and clean panel IS the design
- ONE focal motif (the stained-glass field + central text panel)

TYPOGRAPHY:
- Display face: refined modern serif
- Body face: clean sans-serif
- Title: 10% of post height, centered inside the panel, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Wish message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Text panel: ~50% of post width, ~40% of post height, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The pattern must be CLEAN GEOMETRIC, not a chaotic mess
- The black cells should feel ACCENT, not dominant
- ONE focal motif (the stained-glass field + text panel)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 07 — Crescent Crown
**Mood:** Heroic-celestial, the birth symbol
**Type:** Centered, beneath the crescent
**Aspect:** [VERTICAL] 4:5 (1080 × 1350)

**Visual Theme:**
- A very large gold crescent sits in the upper half
- A star sits inside or beside the crescent
- The crescent is the "birth" symbol — large and central
- A few small stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep heritage green

**Color Logic:**
- Primary: deep heritage green (background)
- Secondary: royal gold (crescent, halo, stars, text)
- Accent: deep black (deepest shadow)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│     ✦       ✦                      │
│   ╱⌒⌒⌒⌒⌒⌒⌒⌒⌒⌒╲                 │
│ ╱    crescent       ╲                │
│ │      ✦             │               │
│ │                    │               │
│  ╲                   ╱               │
│   ╲_______________╱                  │
│       ✦       ✦                      │
│                                     │
│   "Milad-un-Nabi Mubarak"           │
│   "Celebrating the birth            │
│    of the Holy Prophet ﷺ"          │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 4:5 (1080x1350) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Crescent Crown [VERTICAL]
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — background)
- Secondary: #D4AF37 (royal gold — crescent, halo, stars, text)
- Accent: #1A1A1A (deep black — deepest shadow)

VISUAL ELEMENTS:
- A very large gold crescent in the upper half
- A star sits inside or beside the crescent
- A few small stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep heritage green
- ONE focal motif (the crescent + stars)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Crescent: upper half, ~55% of post width (larger than Layout 01)
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
- The crescent reads as REVERENT and CENTRAL
- The gold must feel HONORING, not gaudy
- ONE focal motif (the crescent + stars)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 08 — Calligraphy of Reverence
**Mood:** Type-driven, the day's word
**Type:** Massive, the design itself
**Aspect:** 1:1

**Visual Theme:**
- "Milad-un-Nabi Mubarak" is THE design — rendered in a luminous
  calligraphic or display serif at huge scale
- The type appears to glow against the deep heritage green
- A single hairline gold rule separates title from message
- Background: deep heritage green
- A small crescent + star as a micro-element

**Color Logic:**
- Primary: deep heritage green (background)
- Secondary: royal gold (text, hairline rule, crescent, star)
- Accent: deep black (NOT used in this layout)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│                                     │
│   M I L A D - U N - N A B I         │
│            M U B A R A K             │
│         ──────────── (rule)         │
│         "Celebrating the birth      │
│          of the Holy Prophet ﷺ"    │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 1:1 (1080x1080) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Calligraphy of Reverence
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — background)
- Secondary: #D4AF37 (royal gold — text, hairline rule, crescent, star)
- Accent: #1A1A1A (deep black — NOT USED in this layout)

VISUAL ELEMENTS:
- "Milad-un-Nabi Mubarak" is THE design — rendered in a calligraphic
  or display serif at massive scale (~13-15% of post height)
- The type appears to glow against the deep heritage green
- A single hairline gold rule separates title from message
- A small crescent + star as a micro-element
- Background: solid deep heritage green
- NO second decorative motif. The type is the art.

TYPOGRAPHY:
- Display face: calligraphic Latin OR Didone serif
- Body face: clean sans-serif
- Hero phrase "Milad-un-Nabi Mubarak": 13-15% of post height, centered, secondary
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%
- Letter spacing on hero: +3%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
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

### Layout 09 — Mihrab of Light
**Mood:** Threshold, the light of guidance
**Type:** Centered, inside the arch
**Aspect:** 1:1

**Visual Theme:**
- A stylized pointed arch (mihrab) frames the post's center
- Inside the arch: a luminous gold gradient suggesting "light of guidance"
- The arch line is in royal gold
- Type sits inside the arch, in the gradient
- Background outside the arch: deep heritage green
- A small crescent + star at the arch's apex as a micro-element

**Color Logic:**
- Primary: deep heritage green (outside the arch)
- Secondary: royal gold (arch line, gradient inside, text)
- Accent: deep black (deepest shadow)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│            ╱    ╲                    │
│           │░░░░░│                   │
│           │░░░░░│ "Milad-un-      │
│           │░░░░░│  Nabi"           │
│           │░░░░░│  "Mubarak"       │
│           │░░░░░│                   │
│           │░░░░░│ "Celebrating     │
│           │░░░░░│  the birth"      │
│           ╲░░░░╱                    │
│            ╲____╱ ☾ ✦                │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 09:**
```
Generate a 1:1 (1080x1080) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Mihrab of Light
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — outside the arch)
- Secondary: #D4AF37 (royal gold — arch line, gradient inside, text)
- Accent: #1A1A1A (deep black — deepest shadow)

VISUAL ELEMENTS:
- Stylized pointed arch (mihrab) framing the post's center
- Inside the arch: luminous gold gradient (the "light of guidance")
- The arch line is in royal gold
- Type sits inside the arch, in the gradient
- Background outside the arch: deep heritage green
- A small crescent + star at the arch's apex as a micro-element
- ONE focal motif (the arch of light) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
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
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The arch is STYLIZED — line work, not an architectural drawing
- The arch reads as a WINDOW of light, not a mosque
- The "light" is LUMINOUS, not a literal sun or star
- ONE focal motif (the arch of light) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 10 — Floral Wreath of Respect
**Mood:** Soft, reverent, warm respect
**Type:** Centered, framed by florals
**Aspect:** 1:1

**Visual Theme:**
- A circular floral wreath of stylized rose and jasmine surrounds
  the post's center
- The wreath is rendered in royal gold line work on heritage green
- A second smaller crescent + star inside the wreath as a micro-element
- Type sits in the clear center, never overlapping the wreath
- Background: deep heritage green with a subtle gradient

**Color Logic:**
- Primary: deep heritage green (background, gradient)
- Secondary: royal gold (wreath line work, crescent, star, text)
- Accent: deep black (NOT used in this layout)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│        ❀─────❀─────❀               │
│      ❀       ☾ ✦     ❀              │
│    ❀   "Milad-un-    ❀            │
│    ❀    Nabi          ❀           │
│    ❀    Mubarak"     ❀           │
│      ❀               ❀              │
│        ❀─────❀─────❀               │
│                                     │
│   "Celebrating the birth            │
│    of the Holy Prophet ﷺ"          │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Milad-un-Nabi Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Floral Wreath of Respect
EVENT TITLE: "Milad-un-Nabi Mubarak"
GREETING SUBTITLE: "Celebrating the birth of the Holy Prophet ﷺ"
WISH MESSAGE: "Peace and blessings upon you"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #2C5530 (deep heritage green — background, gradient)
- Secondary: #D4AF37 (royal gold — wreath line work, crescent, star, text)
- Accent: #1A1A1A (deep black — NOT USED in this layout)

VISUAL ELEMENTS:
- A circular floral wreath of stylized rose and jasmine surrounds
  the post's center
- The wreath is rendered in gold LINE WORK (NOT filled) on green
- A smaller crescent + star inside the wreath as a micro-element
- Type sits in the clear center, never overlapping the wreath
- Background: deep heritage green with a subtle gradient
- ONE focal motif (the wreath) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant modern serif
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Wreath: optically centered, ~70% of post width
- Type: in the wreath's clear center
- Crescent + star: inside the wreath
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The florals must be STYLIZED line work, NOT photorealistic
- The wreath reads as REVERENT Islamic respect, not as
  Valentine's romance
- ONE focal motif (the wreath) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given year's Milad-un-Nabi post.

| Year's Tone | Recommended Layouts |
|-------------|---------------------|
| Default / reverent crescent | 01 Crescent of Birth, 07 Crescent Crown |
| Ornate, devotional | 02 Ornate Mihrab, 09 Mihrab of Light |
| Soft, heritage | 03 Floral Heritage, 10 Floral Wreath of Respect |
| Warm, intimate | 04 Lantern of Devotion |
| Contemplative, balanced | 05 Geometric Mandala |
| Jewel-like, dignified | 06 Stained Glass |
| Type-driven, brand-led | 08 Calligraphy of Reverence |
| Default rotation | 01, 05, 08, 09 (one of these per cycle) |

**Recommended rotation pattern (4 years):**
- Year 1: Layout 01 — Crescent of Birth
- Year 2: Layout 05 — Geometric Mandala
- Year 3: Layout 08 — Calligraphy of Reverence
- Year 4: Layout 09 — Mihrab of Light

This guarantees 4 visually distinct posts over a 4-year cycle, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_islamic_milad_un_nabi_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_islamic_milad_un_nabi_01_20260905_v1.png   (Layout 01)
gull_real_estate_builders_islamic_milad_un_nabi_07_20260905_v1.png   (Layout 07, vertical)
gull_real_estate_builders_islamic_milad_un_nabi_08_20260905_v1.png   (Layout 08)
```

---

## 6. CTA Bar Specification (Identical Across All 10 Layouts)

The CTA bar is the ONE element that never changes. It anchors brand recognition across all the visual variety above.

```
HEIGHT: bottom 12% of the post
GROUND COLOR: primary color of the selected layout (heritage green)
LEFT SIDE: SVG phone icon (stroke: secondary gold) + "0314 9393930"
RIGHT SIDE: SVG globe icon (stroke: secondary gold) + "gullrealestate.github.io"
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

Use this for every Milad-un-Nabi post.

```
□ Layout number selected (01-10)
□ Color palette confirmed (ONLY heritage green + gold + black, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-1 micro = max 2)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary ground, secondary icons
□ Aspect ratio: 1:1 default, 4:5 for Layout 07
□ Reverent rule: composition feels SOFT, DIGNIFIED, HONORING
□ Mood check: reverent/dignified/loving/respectful/soft/reflective
□ Prohibited elements reviewed (faces, figures, prayer scenes, religious
  text, Western party imagery, balloons, confetti, neon, etc.)
□ Filename follows convention
```

## 8. Post-Generation Checklist

```
□ No faces or identifiable people (CRITICAL)
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
□ Mood is reverent and loving, never Western-party or gaudy
□ Gold feels HONORING, never flat yellow or excessive
□ Lanterns (if used) have glow gradients, no literal flames
□ Mosque silhouettes (if used) are STYLIZED, contain NO people
□ Florals (if used) are stylized line work, NOT photorealistic
□ The Prophet ﷺ is NEVER depicted in any form
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Milad-un-Nabi-Specific)

Milad-un-Nabi (12th Rabi-ul-Awal) is the celebration of the birth of the Holy Prophet Muhammad ﷺ. It is observed across the Muslim world with deep love, respect, and reverence. The visual treatment must reflect that — but it must NEVER cross into:

- **No depiction of the Prophet ﷺ. EVER.** This is the strictest of all our specs on this point. NO face, NO figure, NO silhouette, NO implied person, NO likeness. The Prophet ﷺ is never depicted in Islamic art, and our specs follow that tradition absolutely.
- **No Western party imagery.** Milad is observed with love and respect, not balloons and confetti. The visual register is REVERENT, not celebratory-in-a-Western-party-sense.
- **Gold is reverent, not gaudy.** Royal gold is the luminous element, but it must feel HONORING, not materialistic. Use gradients and luminous quality, but don't pile on so much that it becomes cheap.
- **No religious text.** A greeting in English is fine. Verses and Arabic script are not used. The Prophet's ﷺ name and the ﷺ honorific are the only Arabic-style elements permitted in the prompt text (the ﷺ is preserved as a typographic mark of respect).
- **No worship scenes.** The day is honored in the greeting, not depicted literally.
- **South Asian Islamic floral heritage.** Rose and jasmine are common in South Asian Islamic art and are appropriate here as STYLIZED line work, not photorealistic florals.
- **Mosque silhouettes are allowed, but stylized.** A geometric mosque shape with NO people inside is fine. A mosque with worshippers is not.
- **Decorative restraint.** Maximum 2 motifs per post (same as Eid-ul-Adha). The composition should feel HONORING, not abundant.
- **Materialism is the wrong register.** Milad is love and respect, not shopping or gift-giving aesthetics. Avoid any imagery that reads as commercial.

The single most important rule for this spec:
> **Reverent, not festive. Loving, not loud. Honoring, not celebrating. The Prophet ﷺ is never depicted.**

When in doubt: **subtract, don't add.** A simpler post is more respectful than a busier one. If a layout choice starts to read as "birthday card", "Western party invite", "wedding invitation", or "Christmas card", stop.

---

**Document Version:** 1.0 - Milad-un-Nabi Post Specification
**Last Updated:** July 28, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Milad-un-Nabi annual posts
