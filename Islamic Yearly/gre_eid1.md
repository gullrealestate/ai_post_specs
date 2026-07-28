# Gull Real Estate & Builders - Eid-ul-Fitr Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Eid-ul-Fitr** (1st Shawwal — the Celebration of the Spirit of Togetherness, marking the end of Ramadan). It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be published with visual variety year over year.

Eid-ul-Fitr is the **first genuinely festive event** in the natural sequence. After the solemnity of Youm-e-Ashura and the graduated spirituality of the three Ramadan Ashras, Eid-ul-Fitr is the moment of **joy, gratitude, and togetherness**. The visual register is **festive but dignified** — celebratory, warm, abundant, but never gaudy, never loud, never Western-party. Eid is a dignified Islamic celebration; the post should reflect that.

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
❌ NO excessive gold that reads as gaudy rather than festive
❌ NO low-quality, pixelated, or busy backgrounds
❌ NO content that could be read as inflammatory or disrespectful
```

---

## 2. Strict Design Language (Applies to All 10 Layouts)

This is the spine of the spec. The 10 layouts all live inside these rules.

### 2.1 Color Discipline
```
- ONLY THREE COLORS are allowed in the entire post:
  * Primary: #01411C (deep Pakistani green)
  * Secondary: #F5E6C4 (warm cream)
  * Accent: #FFD700 (bright gold)
- No fourth color. No exceptions.
- Gradient stops are allowed ONLY between Primary and Secondary
  (the green and cream natural flow), or between Primary and
  Accent (green and gold).
- The Accent (bright gold) is the festive element — used for type,
  decorative motifs, lantern glows, and CTA icons. Gold is allowed
  to be brighter and more abundant than in the Ashra specs, but it
  must still feel LUMINOUS, never gaudy.
- The Secondary (warm cream) is the breathing room — used as
  background in part of the composition, for text contrast, and as
  a warm grounding color.
- Backgrounds: solid cream, solid green, or a green-to-cream
  gradient. NOTHING else.
- Text contrast: AAA where possible, AA at minimum
```

### 2.2 Typography Discipline
```
- Use EXACTLY TWO typefaces per post:
  * One display face (the EVENT TITLE)
  * One body face (subtitle, message, CTA)
- The display face can be a refined serif (Didone or modern
  transitional), an elegant calligraphic Latin (flowing terminals
  suit Eid's celebratory tone), or a clean modern sans. The
  calligraphic option is the most festive.
- The body face is always a clean, highly legible sans-serif.
- Type sizes (as % of post height):
  * Event Title: 9-11% (Eid posts often feature larger titles
    for celebration)
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
- Negative space: minimum 12% of the post must be empty. Eid posts
  may have more decoration than the Ashra specs, but the
  composition must still BREATHE.
- The CTA bar always sits in the bottom 12% of the post.
- The logo space always sits in the top-left 18% × 18% box.
- The event title is always centered on the dominant axis.
- FESTIVE RULE: the composition should feel ABUNDANT and
  WARM, but never CROWDED. Decoration is allowed to be more
  present than in the Ashra specs, but always with restraint.
- No element may overlap the logo space or the CTA bar.
```

### 2.4 Decorative Discipline
```
- Decorative elements are SYMBOLIC and ABUNDANT (this is Eid).
- Allowed motifs: crescent, star (more abundant than other specs),
  traditional lantern (chiragh, no literal flame), geometric
  Islamic patterns (arabesque, tessellation), mosque silhouettes
  (stylized, non-identifiable, NO people inside), stylized floral
  motifs (rose, jasmine), arch/mihrab (line work), abstract
  ornamental rules and frames.
- Maximum THREE decorative motifs per post. Typically ONE hero
  motif and TWO supporting micro-elements. (Eid allows slightly
  more decoration than the Ashra specs, which maxed at 2.)
- Decorative opacity: hero motif 60-100%, micro-elements 20-50%.
- Patterns are reserved for backgrounds or as decorative frames,
  at ≤20% opacity (slightly more visible than Ashra specs).
- No decorative element may be placed inside the logo space.
- Lanterns, when used, must NOT show a literal flame. Use a glow gradient.
- Mosque silhouettes (when used) must be STYLIZED, non-identifiable,
  and contain NO people inside. They are pure geometric shape.
```

### 2.5 Mood Discipline
```
Eid-ul-Fitr is the celebration of togetherness after Ramadan.

ALLOWED MOODS:
  - Joyful
  - Grateful
  - Warm
  - Together
  - Festive (in a dignified Islamic way)
  - Abundant
  - Bright
  - Celebratory (in a dignified Islamic way)

NOT ALLOWED MOODS (would betray the spirit of Eid):
  - Western-party (balloons, confetti, neon, "happy birthday" feel)
  - Loud or chaotic
  - Gaudy or excessive gold
  - Solemn (this is CELEBRATION, not remembrance)
  - Sober (Eid is a JOY, not a quiet moment)
  - Decorative-for-its-own-sake (decoration serves the celebration)
  - Materialistic (Eid is spiritual togetherness, not shopping)

If a layout choice starts to read as "birthday card", "Halloween
poster", "Western party invite", or "wedding invitation", stop.
Eid-ul-Fitr is dignified Islamic celebration — joyful, warm,
abundant, but reverent.
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

## 3. The 10 Eid-ul-Fitr Layouts

Each layout is a complete design system. Pick the layout that matches this year's mood, then run the prompt.

### Layout 01 — Lantern Row
**Mood:** Eid's signature, warm, abundant
**Type:** Centered, above the lanterns
**Aspect:** 1:1

**Visual Theme:**
- Three traditional lanterns (chiragh) in a row across the lower third
- Each lantern has a soft inner glow (no literal flame)
- Lanterns are the Eid signature — abundant and warm
- Type sits in the upper two-thirds, in the calm
- A small crescent + star in the upper third as a micro-element

**Color Logic:**
- Primary: deep Pakistani green (background)
- Secondary: warm cream (text, lantern body)
- Accent: bright gold (lantern glow, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│              ☾ ✦                     │
│                                     │
│                                     │
│       "Eid-ul-Fitr Mubarak"         │
│       "Celebrating the spirit        │
│        of togetherness"             │
│                                     │
│   ┌─────┐   ┌─────┐   ┌─────┐       │
│   │ glow│   │ glow│   │ glow│       │
│   │     │   │     │   │     │       │
│   └─────┘   └─────┘   └─────┘       │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Lantern Row
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — background)
- Secondary: #F5E6C4 (warm cream — text, lantern body)
- Accent: #FFD700 (bright gold — lantern glow, crescent, star)

VISUAL ELEMENTS:
- Three traditional lanterns (chiragh) in a row across the lower third
- Each lantern has a soft inner glow (NO literal flame)
- A small crescent + star in the upper third as a micro-element
- Background: deep Pakistani green
- ONE focal motif (the lantern row) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Lanterns: lower third, evenly spaced, equal sizes
- Type: upper two-thirds, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery (balloons, confetti, party hats, fireworks)
- NO bird, nest, or emblem in the logo space
- Lanterns must NOT show a literal flame — use a glow gradient only
- The lanterns read as EID warmth, not as night lanterns alone
- ONE focal motif (the lantern row) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 02 — Geometric Burst
**Mood:** Celebratory, radiant, festive
**Type:** Centered, above the burst
**Aspect:** 1:1

**Visual Theme:**
- A radial geometric burst pattern emanates from the lower-center
- The burst is a modern Islamic geometric star (8 or 12 points)
- The burst is in gold with green inner fills
- Type sits in the upper half, in the cream space
- Background: warm cream with a subtle green gradient

**Color Logic:**
- Primary: deep Pakistani green (burst fills, gradient)
- Secondary: warm cream (background, text)
- Accent: bright gold (burst stroke, decorative)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│   "Eid-ul-Fitr Mubarak"             │
│   "May Allah bless you              │
│    and your family"                 │
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

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Geometric Burst
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — burst fills, gradient)
- Secondary: #F5E6C4 (warm cream — background, text)
- Accent: #FFD700 (bright gold — burst stroke, decorative)

VISUAL ELEMENTS:
- A radial geometric burst pattern emanates from the lower-center
- The burst is a modern Islamic geometric star (8 or 12 points)
- The burst is in gold with green inner fills
- Type sits in the upper half, in the cream space
- Background: warm cream with a subtle green gradient
- ONE focal motif (the burst) — no second decorative element

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Burst: lower-center, ~50% of post width
- Type: upper half, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The burst is a MODERN ISLAMIC GEOMETRIC STAR, not a firework,
  not an explosion, not a Western celebration burst
- ONE focal motif (the burst) — no second decorative element

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 03 — Crescent Crown
**Mood:** Heroic-celestial, celebratory, Eid's signature
**Type:** Centered, beneath the crescent
**Aspect:** 1:1

**Visual Theme:**
- A large gold crescent with star sits in the upper half
- The crescent has a festive gold halo
- A row of small stars trails along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep Pakistani green

**Color Logic:**
- Primary: deep Pakistani green (background)
- Secondary: warm cream (text, stars)
- Accent: bright gold (crescent, halo)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│       ✦       ✦                      │
│     ╱⌒⌒⌒⌒⌒⌒⌒⌒⌒⌒╲                 │
│   ╱   crescent + halo   ╲             │
│  │       ✦             │             │
│   ╲                   ╱              │
│     ╲_______________╱                │
│         ✦       ✦                    │
│                                     │
│       "Eid-ul-Fitr Mubarak"         │
│       "May Allah bless you          │
│        and your family"             │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Crescent Crown
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — background)
- Secondary: #F5E6C4 (warm cream — text, small stars)
- Accent: #FFD700 (bright gold — crescent, halo)

VISUAL ELEMENTS:
- A large gold crescent with star in the upper half
- A festive gold halo radiates from the crescent
- A row of small stars trails along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep Pakistani green
- ONE focal motif (the crescent + halo + stars as one Eid symbol)

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
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The crescent reads as CELEBRATORY EID, not as Halloween
- The gold must be LUMINOUS, not flat yellow
- ONE focal motif (the crescent + stars)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 04 — Mihrab of Joy
**Mood:** Threshold, festive, framed
**Type:** Centered, inside the arch
**Aspect:** 1:1

**Visual Theme:**
- A stylized pointed arch (mihrab) frames the post's center
- Inside the arch: a festive gold-to-cream gradient
- The arch line is in bright gold
- Type sits inside the arch, in the gradient
- Background outside the arch: deep Pakistani green
- A small crescent + star at the arch's apex as a micro-element

**Color Logic:**
- Primary: deep Pakistani green (outside the arch)
- Secondary: warm cream (gradient inside, text)
- Accent: bright gold (arch line, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│            ╱    ╲                    │
│           │░░░░░│                   │
│           │░░░░░│ "Eid-ul-Fitr"    │
│           │░░░░░│  "Mubarak"       │
│           │░░░░░│                   │
│           │░░░░░│ "May Allah       │
│           │░░░░░│  bless you"      │
│           ╲░░░░╱                    │
│            ╲____╱ ☾ ✦                │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Mihrab of Joy
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — outside the arch)
- Secondary: #F5E6C4 (warm cream — gradient inside, text)
- Accent: #FFD700 (bright gold — arch line, crescent, star)

VISUAL ELEMENTS:
- Stylized pointed arch (mihrab) framing the post's center
- Inside the arch: festive gold-to-cream gradient
- The arch line is in bright gold
- Type sits inside the arch, in the gradient
- Background outside the arch: deep Pakistani green
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
- The arch reads as a WINDOW of joy, not a mosque
- ONE focal motif (the arch) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 05 — Stained Glass
**Mood:** Eid, jewel-like, dignified
**Type:** Centered, in the text panel
**Aspect:** 1:1

**Visual Theme:**
- A geometric stained-glass pattern fills the entire background
- The pattern is divided into clean color blocks (primary + secondary)
- Gold accent appears in 1-2 glass cells
- A clear, unpatterned rectangular panel in the center holds the type
- The contrast between busy pattern and clean panel IS the design

**Color Logic:**
- Primary: deep Pakistani green (main glass cells)
- Secondary: warm cream (text panel, secondary cells)
- Accent: bright gold (1-2 glass cells, decorative)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓┌─────────────┐▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "Eid-ul-Fitr │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  Mubarak"   │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "May Allah   │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  bless you"  │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓└─────────────┘▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Stained Glass
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — main glass cells)
- Secondary: #F5E6C4 (warm cream — text panel, secondary cells)
- Accent: #FFD700 (bright gold — 1-2 glass cells, decorative)

VISUAL ELEMENTS:
- Geometric stained-glass pattern fills the entire background
- Pattern is divided into clean color blocks (no gradients within cells)
- Gold accent appears in 1-2 glass cells
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
- The gold cells should feel ACCENT, not dominant
- ONE focal motif (the stained-glass field + text panel)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 06 — Arabesque Frame
**Mood:** Contemplative, balanced, Eid's classic
**Type:** Centered inside the frame
**Aspect:** 1:1

**Visual Theme:**
- A large circular geometric arabesque frame surrounds the post's center
- The frame is rendered in bright gold with green inner shapes
- Type sits in the clear circular negative space at the center
- Background: warm cream
- A small crescent + star at the top of the frame

**Color Logic:**
- Primary: deep Pakistani green (background gradient, frame shapes)
- Secondary: warm cream (background, text)
- Accent: bright gold (frame stroke, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│         ╭───────────╮               │
│       ╱   arabesque  ╲             │
│      │   ╭───────╮    │             │
│      │  │ "Eid-ul-  │   │            │
│      │  │  Fitr     │   │           │
│      │  │ Mubarak"  │   │           │
│      │   ╰───────╯    │             │
│       ╲             ╱              │
│         ╰───────────╯               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Arabesque Frame
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — frame shapes, gradient)
- Secondary: #F5E6C4 (warm cream — background, text)
- Accent: #FFD700 (bright gold — frame stroke, crescent, star)

VISUAL ELEMENTS:
- A large circular geometric arabesque frame surrounds the post's center
- The frame is rendered in bright gold with green inner shapes
- A small crescent + star at the top of the frame
- Type sits in the clear circular negative space at the center
- Background: warm cream
- ONE focal motif (the arabesque frame) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Wish message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
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
- The gold should feel FESTIVE but not gaudy
- ONE focal motif (the arabesque frame) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 07 — Calligraphy of Eid
**Mood:** Type-driven, joyful, the celebration's word
**Type:** Massive, the design itself
**Aspect:** 1:1

**Visual Theme:**
- "Eid Mubarak" is THE design — rendered in a luminous calligraphic
  or display serif at huge scale
- The type appears to glow against the deep green
- A single hairline gold rule separates title from message
- Background: deep Pakistani green
- A small crescent + star as a micro-element

**Color Logic:**
- Primary: deep Pakistani green (background)
- Secondary: warm cream (text)
- Accent: bright gold (hairline rule, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│                                     │
│       E I D   M U B A R A K         │
│         ──────────── (rule)         │
│         "May Allah bless you        │
│          and your family"           │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Calligraphy of Eid
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — background)
- Secondary: #F5E6C4 (warm cream — text)
- Accent: #FFD700 (bright gold — hairline rule, crescent, star)

VISUAL ELEMENTS:
- "Eid Mubarak" is THE design — rendered in a calligraphic or
  display serif at massive scale (~13-15% of post height)
- The type appears to glow against the deep green
- A single hairline gold rule separates title from message
- A small crescent + star as a micro-element
- Background: solid deep Pakistani green
- NO second decorative motif. The type is the art.

TYPOGRAPHY:
- Display face: calligraphic Latin OR Didone serif
- Body face: clean sans-serif
- Hero phrase "Eid Mubarak": 13-15% of post height, centered, secondary
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

### Layout 08 — Lantern Cascade
**Mood:** Hanging lanterns, abundant, vertical
**Type:** Centered, between the lanterns
**Aspect:** [VERTICAL] 4:5 (1080 × 1350)

**Visual Theme:**
- A vertical arrangement of 3-4 traditional lanterns hanging from
  the top of the post
- The lanterns cascade downward at varying heights
- Each lantern has a soft inner glow (no literal flame)
- Type sits in the lower half, between/below the lanterns
- Background: deep Pakistani green

**Color Logic:**
- Primary: deep Pakistani green (background)
- Secondary: warm cream (text, lantern body)
- Accent: bright gold (lantern glow, decorative)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│        ┌─────┐                      │
│        │glow │                      │
│        │     │                      │
│        └─────┘                      │
│            ┌─────┐                  │
│            │glow │                  │
│            │     │                  │
│            └─────┘                  │
│                ┌─────┐              │
│                │glow │              │
│                │     │              │
│                └─────┘              │
│                  ┌─────┐            │
│                  │glow │            │
│                  │     │            │
│                  └─────┘            │
│                                     │
│   "Eid-ul-Fitr Mubarak"             │
│   "May Allah bless you              │
│    and your family"                 │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 4:5 (1080x1350) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Lantern Cascade [VERTICAL]
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — background)
- Secondary: #F5E6C4 (warm cream — text, lantern body)
- Accent: #FFD700 (bright gold — lantern glow, decorative)

VISUAL ELEMENTS:
- A vertical arrangement of 3-4 traditional lanterns hanging from
  the top of the post
- The lanterns cascade downward at varying heights
- Each lantern has a soft inner glow (NO literal flame)
- Type sits in the lower half, between/below the lanterns
- Background: deep Pakistani green
- ONE focal motif (the lantern cascade)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Lanterns: top two-thirds, cascading downward, varying heights
- Type: lower third, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- Lanterns must NOT show a literal flame — use a glow gradient only
- The cascade reads as ABUNDANT EID, not as cluttered
- ONE focal motif (the lantern cascade)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 09 — Constellation of Joy
**Mood:** Abundant stars, festive, hopeful
**Type:** Centered, in the calm
**Aspect:** 1:1

**Visual Theme:**
- An abundant ordered star field fills the background (~30-40 stars)
- The stars are more numerous and slightly larger than other specs
- A few stars are larger, forming a faint Eid pattern
- A large crescent sits as the anchor in the upper third
- Type sits in a calm negative-space pocket in the center-lower

**Color Logic:**
- Primary: deep Pakistani green (background)
- Secondary: warm cream (stars, text)
- Accent: bright gold (crescent, larger stars)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]   ✦  ✦                       │
│          ✦    ☾                     │
│        ✦  ✦  ✦                      │
│   ✦  ✦     "Eid-ul-Fitr"   ✦       │
│              Mubarak"               │
│   ✦    "May Allah       ✦           │
│         bless you"                  │
│     ✦    ✦         ✦                │
│        ✦   ✦                        │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 09:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Constellation of Joy
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — background)
- Secondary: #F5E6C4 (warm cream — stars, text)
- Accent: #FFD700 (bright gold — crescent, larger stars)

VISUAL ELEMENTS:
- An abundant ordered star field fills the background (~30-40 stars)
- The stars are more numerous and slightly larger than other specs
- A few stars are larger, forming a faint Eid pattern
- A large gold crescent sits as the anchor in the upper third
- Type sits in a calm negative-space pocket in the center-lower
- Background: deep Pakistani green
- ONE focal motif (the star field + crescent)

TYPOGRAPHY:
- Display face: elegant calligraphic Latin
- Body face: clean sans-serif
- Title: 9% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Wish message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Star field: distributed, but ordered (not random scatter)
- Type pocket: clear, unstarred, in the center-lower
- Crescent: upper third
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The field is ORDERED, not chaotic. The composition feels
  abundant and festive, not random.
- ONE focal motif (the star field + crescent)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 10 — Floral Eid
**Mood:** Soft, warm, gentle Eid
**Type:** Centered, framed by florals
**Aspect:** 1:1

**Visual Theme:**
- A circular floral wreath of stylized rose and jasmine surrounds
  the post's center
- The wreath is rendered in gold line work (NOT filled) on green
- Type sits in the clear center, never overlapping the wreath
- A small crescent + star at the top of the wreath
- Background: deep Pakistani green

**Color Logic:**
- Primary: deep Pakistani green (background)
- Secondary: warm cream (text, small floral accents)
- Accent: bright gold (wreath line work, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│        ❀─────❀─────❀               │
│      ❀               ❀              │
│    ❀   "Eid-ul-Fitr   ❀            │
│    ❀    Mubarak"      ❀           │
│      ❀               ❀              │
│        ❀─────❀─────❀               │
│                                     │
│   "May Allah bless you              │
│    and your family"                 │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Eid-ul-Fitr Mubarak"
for Gull Real Estate & Builders.

LAYOUT: Floral Eid
EVENT TITLE: "Eid-ul-Fitr Mubarak"
GREETING SUBTITLE: "Celebrating the spirit of togetherness"
WISH MESSAGE: "May Allah bless you and your family"
COMPANY ATTRIBUTION: "From the family at Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (deep Pakistani green — background)
- Secondary: #F5E6C4 (warm cream — text, small floral accents)
- Accent: #FFD700 (bright gold — wreath line work, crescent, star)

VISUAL ELEMENTS:
- A circular floral wreath of stylized rose and jasmine surrounds
  the post's center
- The wreath is rendered in gold LINE WORK (NOT filled) on green
- A small crescent + star at the top of the wreath
- Type sits in the clear center, never overlapping the wreath
- Background: deep Pakistani green
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
- The wreath reads as EID warmth, not as Valentine's romance
- ONE focal motif (the wreath) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given year's Eid-ul-Fitr post.

| Year's Tone | Recommended Layouts |
|-------------|---------------------|
| Default / Eid's signature | 01 Lantern Row, 03 Crescent Crown |
| Radiant, festive | 02 Geometric Burst, 09 Constellation of Joy |
| Threshold, framed | 04 Mihrab of Joy, 05 Stained Glass |
| Contemplative, balanced | 06 Arabesque Frame |
| Type-driven, brand-led | 07 Calligraphy of Eid |
| Hanging, abundant | 08 Lantern Cascade |
| Soft, gentle | 10 Floral Eid |
| Default rotation | 01, 03, 06, 07 (one of these per cycle) |

**Recommended rotation pattern (4 years):**
- Year 1: Layout 01 — Lantern Row
- Year 2: Layout 03 — Crescent Crown
- Year 3: Layout 06 — Arabesque Frame
- Year 4: Layout 07 — Calligraphy of Eid

This guarantees 4 visually distinct posts over a 4-year cycle, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_islamic_eid_ul_fitr_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_islamic_eid_ul_fitr_01_20270320_v1.png   (Layout 01)
gull_real_estate_builders_islamic_eid_ul_fitr_06_20270320_v1.png   (Layout 06)
gull_real_estate_builders_islamic_eid_ul_fitr_07_20270320_v1.png   (Layout 07)
```

---

## 6. CTA Bar Specification (Identical Across All 10 Layouts)

The CTA bar is the ONE element that never changes. It anchors brand recognition across all the visual variety above.

```
HEIGHT: bottom 12% of the post
GROUND COLOR: primary color of the selected layout (green)
LEFT SIDE: SVG phone icon (stroke: secondary cream) + "0314 9393930"
RIGHT SIDE: SVG globe icon (stroke: secondary cream) + "gullrealestate.github.io"
DIVIDER: thin vertical line in secondary cream, 30% opacity, centered
PADDING: equal left/right padding (8% of post width)
ICON SIZE: 24x24 logical units, scalable
TEXT SIZE: 3% of post height
TEXT COLOR: secondary cream
```

### Phone Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[SECONDARY_CREAM]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
</svg>
```

### Globe Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[SECONDARY_CREAM]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <circle cx="12" cy="12" r="10"/>
  <line x1="2" y1="12" x2="22" y2="12"/>
  <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/>
</svg>
```

---

## 7. Pre-Generation Checklist

Use this for every Eid-ul-Fitr post.

```
□ Layout number selected (01-10)
□ Color palette confirmed (ONLY green + cream + gold, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-2 micro = max 3)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary ground, secondary icons
□ Aspect ratio: 1:1 default, 4:5 for Layout 08
□ Festive rule: composition feels ABUNDANT but not CROWDED
□ Mood check: joyful/grateful/warm/together/festive/abundant
□ Prohibited elements reviewed (faces, prayer scenes, religious text,
  Western party imagery, balloons, confetti, neon, etc.)
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
□ Maximum three decorative motifs (one hero + optional micro)
□ CTA bar matches Section 6 spec exactly
□ Aspect ratio matches layout choice
□ Mood is festive but dignified, never Western-party or gaudy
□ Gold is FESTIVE but never flat yellow, never gaudy
□ Lanterns (if used) have glow gradients, no literal flames
□ Mosque silhouettes (if used) are STYLIZED, contain NO people
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Eid-ul-Fitr-Specific)

Eid-ul-Fitr (1st Shawwal) is the celebration marking the end of Ramadan. It is a day of joy, gratitude, family, and togetherness. The visual treatment must reflect that — but it must be DIGNIFIED ISLAMIC CELEBRATION, not Western party.

- **No Western party imagery.** No balloons, no confetti, no party hats, no fireworks, no neon colors, no "happy birthday" aesthetic. Eid is dignified Islamic celebration.
- **Gold is festive, not gaudy.** Gold reads as divine light and Eid warmth. Use gradients and luminous quality, but don't pile on so much that it becomes cheap. Festive abundance, not material excess.
- **Mosque silhouettes are allowed, but stylized.** A geometric mosque shape with NO people inside is fine. A mosque with worshippers is not.
- **Lanterns are Eid's signature, used abundantly.** This is the one event where lantern rows, cascades, and clusters feel right. They symbolize Eid warmth, not night-time quiet.
- **Florals are festive, not romantic.** Rose and jasmine are common in South Asian Islamic celebration. They are warm and abundant, not Valentine's romance.
- **No worship scenes.** The day is honored in the greeting, not depicted literally.
- **No religious text.** A greeting in English is fine. Verses and Arabic script are not used.
- **Decorative abundance is allowed.** This is the most decorative event in the natural sequence — up to 3 motifs per post. But "abundant" is not "crowded." Always with breathing room.
- **Materialism is the wrong register.** Eid is spiritual togetherness and gratitude, not shopping or gift-giving aesthetics. Avoid any imagery that reads as commercial.

The single most important rule for this spec:
> **Festive, not gaudy. Abundant, not crowded. Together, not loud. Eid is dignified Islamic celebration.**

When in doubt: **subtract, don't add.** A simpler post is more respectful than a busier one. If a layout choice starts to read as "birthday card", "Western party invite", "wedding invitation", or "Valentine's card", stop.

---

**Document Version:** 1.0 - Eid-ul-Fitr Post Specification
**Last Updated:** July 28, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Eid-ul-Fitr annual posts
