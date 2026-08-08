# Gull Real Estate & Builders - Pakistan Independence Day Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Pakistan Independence Day** (14th August). It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be published with visual variety year over year.

Independence Day is the **first national event** in the natural sequence — a major shift in tone from the Islamic events. The day is **patriotic, celebratory, proud, and unifying**. It is the most openly celebratory event in the entire spec series — more joyful than Eid-ul-Fitr, more festive than the Ashras. The visual register is **national pride, professional polish, and unity** — never political-party-aligned, never divisive, never aggressive.

The day honors Pakistan's independence (1947) and the founders who made it possible. The 10 layouts feature iconic Pakistani iconography (crescent + star, Minar-e-Pakistan, the flag) and **stylized silhouettes of founding figures** — Quaid-e-Azam Muhammad Ali Jinnah, Allama Muhammad Iqbal, Sir Syed Ahmad Khan, and Choudhry Rahmat Ali. Silhouettes are used because realistic faces/likenesses are restricted in commercial use; silhouettes are the standard for honoring these figures in professional Pakistani design.

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
❌ NO faces or identifiable likenesses of any real person
   (CRITICAL — see "Founder Figure Rules" in Section 2.6 below)
❌ NO mosques with worshippers or prayer scenes
❌ NO religious text (Quran verses, Hadith, Arabic script as content)
❌ NO political party logos or symbols (PML-N, PPP, PTI, JI, MQMP, etc.)
❌ NO flags of any nation OTHER than Pakistan
❌ NO military combat imagery, weapons, or aggressive violence
❌ NO nudity or suggestive content
❌ NO bird, nest, or decorative emblem in or near the logo space
❌ NO Western-style party imagery (balloons, confetti, party hats,
   fireworks, "happy birthday" aesthetic, neon colors)
❌ NO gaudy or excessive gold that reads as cheap
❌ NO low-quality, pixelated, or busy backgrounds
❌ NO content that could be read as inflammatory, sectarian, or divisive
```

---

## 2. Strict Design Language (Applies to All 10 Layouts)

This is the spine of the spec. The 10 layouts all live inside these rules.

### 2.1 Color Discipline
```
- ONLY THREE COLORS are allowed in the entire post:
  * Primary: #01411C (Pakistan green)
  * Secondary: #FFFFFF (white)
  * Accent: #E8B923 (gold)
- No fourth color. No exceptions.
- Gradient stops are allowed ONLY between Primary and Secondary
  (the green and white natural flow), or between Primary and
  Accent (green and gold).
- The Primary (Pakistan green) is the dominant element — used
  for backgrounds and as the foundation of the composition.
- The Secondary (white) is the breathing room — used for type,
  text contrast, and the white band of the flag.
- The Accent (gold) is the festive element — used for type,
  decorative motifs, the crescent and star, and CTA icons.
  Gold is CELEBRATORY here (more than Eid-ul-Adha's earthy amber).
- Backgrounds: solid green, solid white, or a green-to-white
  gradient. NOTHING else.
- Text contrast: AAA where possible, AA at minimum
```

### 2.2 Typography Discipline
```
- Use EXACTLY TWO typefaces per post:
  * One display face (the EVENT TITLE)
  * One body face (subtitle, message, CTA)
- The display face can be a refined serif (Didone or modern
  transitional), a clean modern sans, or — for the most
  patriotic feel — a condensed sans-serif with strong letterforms.
- The body face is always a clean, highly legible sans-serif.
- Type sizes (as % of post height):
  * Event Title: 10-12% (Independence Day posts often feature
    larger titles for impact)
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
- Negative space: minimum 12% of the post must be empty.
- The CTA bar always sits in the bottom 12% of the post.
- The logo space always sits in the top-left 18% × 18% box.
- The event title is always centered on the dominant axis.
- PATRIOTIC RULE: the composition should feel PROUD, UNIFYING,
  and PROFESSIONAL. Decoration is allowed to be more present
  than the Islamic Ashra specs, but never political-party-aligned.
- No element may overlap the logo space or the CTA bar.
```

### 2.4 Decorative Discipline
```
- Decorative elements are SYMBOLIC, PATRIOTIC, and PROFESSIONAL.
- Allowed motifs: Pakistani flag crescent + star (stylized, not
  literal flag), Minar-e-Pakistan silhouette (stylized, non-
  identifiable as anything other than a generic monument),
  abstract flag movement (NOT realistic fabric), stylized
  silhouettes of founding figures (Quaid-e-Azam, Allama Iqbal,
  Sir Syed Ahmad Khan, Choudhry Rahmat Ali — all as abstract
  silhouettes ONLY, never realistic faces), geometric Islamic
  patterns, arch/mihrab (line work).
- Maximum THREE decorative motifs per post. (Independence Day
  is celebratory, like Eid-ul-Fitr — slightly more decoration
  than the Ashra specs.)
- Decorative opacity: hero motif 60-100%, micro-elements 20-50%.
- Patterns are reserved for backgrounds or as decorative frames,
  at ≤20% opacity.
- No decorative element may be placed inside the logo space.
- Flags (when used) must be STYLIZED, not realistic fabric. The
  Pakistani flag is the ONLY flag permitted. The flag should
  read as a PATRIOTIC SYMBOL, not as a banner.
- Minar-e-Pakistan silhouettes (when used) must be STYLIZED,
  non-identifiable as anything other than a generic tower.
```

### 2.5 Mood Discipline
```
Pakistan Independence Day is patriotic celebration of the nation's
freedom, with national pride and unity.

ALLOWED MOODS:
  - Patriotic
  - Proud
  - Celebratory
  - Unifying
  - Hopeful
  - Joyful
  - Bright
  - Grateful
  - Professional

NOT ALLOWED MOODS (would betray the spirit of the day):
  - Western-party (balloons, confetti, neon, "happy birthday" feel)
  - Political-party-aligned (no party symbolism)
  - Loud or aggressive (no militant imagery)
  - Sectarian or divisive
  - Military combat imagery
  - Solemn (this is CELEBRATION, not remembrance)
  - Materialistic
  - Decorative-for-its-own-sake

If a layout choice starts to read as "political party poster",
"military recruitment ad", "Western party invite", or
"sectarian messaging", stop. Independence Day is UNIFYING
patriotic celebration — proud, professional, and inclusive
of all Pakistanis.
```

### 2.6 Founder Figure Rules (CRITICAL)
```
FOUNDING FIGURES may be honored via ABSTRACT SILHOUETTES ONLY.

ALLOWED:
  - Stylized black or gold silhouettes of:
    * Quaid-e-Azam Muhammad Ali Jinnah (founder, most iconic)
    * Allama Muhammad Iqbal (national poet, philosopher)
    * Sir Syed Ahmad Khan (educational reformer, Aligarh founder)
    * Choudhry Rahmat Ali (coined the name "Pakistan" in his
      1933 "Now or Never" pamphlet)
  - The silhouette must be a SINGLE, SIMPLE, ABSTRACT form
  - The silhouette must be PROFILE or 3/4 view, NEVER frontal
    with detailed facial features
  - The silhouette must be CALM and DIGNIFIED, not action pose
  - Multiple silhouettes can appear together, but they should
    not overlap

NOT ALLOWED:
  - NO realistic faces
  - NO detailed facial features (eyes, nose, mouth)
  - NO photorealistic portraits
  - NO action poses (no gesturing, no speech-making poses)
  - NO depiction of the figures in political contexts
    (no Parliament, no microphone, no specific historical scene)
  - NO depiction in a way that could be confused with a
    political party leader
  - NO depiction of any CURRENT political figure
  - NO depiction of the figures in religious contexts
    (no mosques, no prayer scenes, no religious speeches)

WHY SILHOUETTES:
  - Likenesses of real people are restricted in commercial use
  - Silhouettes are the standard for honoring founding figures
    in professional Pakistani design
  - Silhouettes avoid any political controversy
  - Silhouettes read as SYMBOL, not as portrait

WHEN IN DOUBT:
  - If the silhouette starts to look like a real portrait,
    simplify it further until it's clearly a SHAPE, not a face
  - The silhouette should be RECOGNIZABLE as a person in profile,
    but NOT recognizable as a specific real individual
```

### 2.7 Aspect Ratio & Resolution
```
- All layouts default to 1:1 (1080 × 1080 px)
- Layouts marked [VERTICAL] use 4:5 (1080 × 1350 px)
- Layouts marked [STORY] use 9:16 (1080 × 1920 px) for IG/FB stories
- Resolution: minimum 1080px on the short edge
- Color mode: RGB
- Format: PNG (preferred) or JPG
```

---

## 3. The 10 Pakistan Independence Day Layouts

Each layout is a complete design system. Pick the layout that matches this year's mood, then run the prompt.

### Layout 01 — Crescent & Star Hero
**Mood:** The flag's symbol, heroically scaled
**Type:** Centered, beneath the crescent
**Aspect:** 1:1

**Visual Theme:**
- A large gold crescent + star sit in the upper half — the Pakistani
  flag's symbol at heroic scale
- The crescent and star are the centerpiece
- A few small green stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep Pakistan green

**Color Logic:**
- Primary: Pakistan green (background)
- Secondary: white (small stars, text)
- Accent: gold (crescent, hero star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│     ✦       ✦                      │
│   ╱⌒⌒⌒⌒⌒⌒⌒⌒⌒⌒╲                 │
│ ╱   crescent + star   ╲             │
│ │       ✦             │             │
│  ╲                   ╱              │
│   ╲_______________╱                │
│       ✦       ✦                    │
│                                     │
│   "Pakistan Independence Day"       │
│   "14th August Mubarak"             │
│                                     │
│   "Long Live Pakistan"              │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Crescent & Star Hero
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — background)
- Secondary: #FFFFFF (white — small stars, text)
- Accent: #E8B923 (gold — crescent, hero star)

VISUAL ELEMENTS:
- A large gold crescent + star in the upper half — the Pakistani
  flag's symbol at heroic scale
- A few small white stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep Pakistan green
- ONE focal motif (the crescent + star)

TYPOGRAPHY:
- Display face: clean modern sans (condensed) or modern serif
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, accent color

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Crescent + star: upper half, ~50% of post width
- Star trail: along the crescent's curve
- Type: lower half, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery, weapons, or aggressive violence
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The crescent + star are the PAKISTANI FLAG SYMBOL, not religious iconography
- ONE focal motif (the crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 02 — Minar-e-Pakistan
**Mood:** Monumental, patriotic, the national landmark
**Type:** Centered, around the monument
**Aspect:** 1:1

**Visual Theme:**
- A stylized Minar-e-Pakistan silhouette rises in the upper-center
- The Minar is the iconic Lahore monument
- Type wraps around the Minar or sits below it
- A small crescent + star at the Minar's apex
- Background: deep Pakistan green
- The Minar reads as a SYMBOL, not a literal architectural drawing

**Color Logic:**
- Primary: Pakistan green (background)
- Secondary: white (Minar silhouette, text)
- Accent: gold (crescent, star at apex)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│                  │                  │
│                  │                  │
│                 ╱│╲                 │
│                ╱ │ ╲                │
│               │  │  │               │
│               │  │  │               │
│              ╱   │   ╲              │
│             │    │    │             │
│            ╱     │     ╲            │
│           │      │      │           │
│          ╱       │       ╲          │
│         │        │        │         │
│        ╱═════════╧═════════╲        │
│                                     │
│   "Pakistan Independence Day"       │
│   "Long Live Pakistan"              │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Minar-e-Pakistan
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — background)
- Secondary: #FFFFFF (white — Minar silhouette, text)
- Accent: #E8B923 (gold — crescent, star at apex)

VISUAL ELEMENTS:
- A stylized Minar-e-Pakistan silhouette rises in the upper-center
- The Minar is the iconic Lahore monument
- A small gold crescent + star at the Minar's apex
- Type wraps around the Minar or sits below it
- Background: deep Pakistan green
- ONE focal motif (the Minar)

TYPOGRAPHY:
- Display face: clean modern sans (condensed) or modern serif
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, accent color

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Minar: upper-center, ~30% of post width
- Crescent + star: at the Minar's apex
- Type: below the Minar, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The Minar must be STYLIZED, not a literal architectural drawing
- ONE focal motif (the Minar)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 03 — Flag Waving
**Mood:** Movement, pride, festive
**Type:** Centered, overlaid on the flag
**Aspect:** 1:1

**Visual Theme:**
- An abstract stylized flag waves across the post
- The flag is NOT realistic fabric — it's an abstract STYLIZED
  representation with the crescent + star
- The flag's green and white bands are abstract, simplified
- Type sits overlaid on the flag, in white
- A few small gold stars trail in the corners

**Color Logic:**
- Primary: Pakistan green (flag green band, background)
- Secondary: white (flag white band, text)
- Accent: gold (crescent, star, decorative)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│ ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ │
│ ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
│ ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
│ ▓▓▓▓ "Pakistan Independence Day" ▓▓ │
│ ▓▓▓▓ "14th August Mubarak"       ▓▓ │
│ ▓▓▓▓ "Long Live Pakistan"         ▓▓ │
│ ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
│ ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ │
│ ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 1:1 (1080x1080) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Flag Waving
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — flag green band, background)
- Secondary: #FFFFFF (white — flag white band, text)
- Accent: #E8B923 (gold — crescent, star, decorative)

VISUAL ELEMENTS:
- An abstract stylized flag waves across the post
- The flag is NOT realistic fabric — it's an abstract STYLIZED
  representation with the crescent + star
- The flag's green and white bands are abstract, simplified
- Type sits overlaid on the flag, in white
- A few small gold stars trail in the corners
- ONE focal motif (the stylized flag) + optional micro (corner stars)

TYPOGRAPHY:
- Display face: clean modern sans (condensed, bold)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Flag: across the post, stylized, with crescent + star
- Type: overlaid on the flag, centered
- Negative space: minimum 10% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The flag is STYLIZED, NOT realistic fabric
- The crescent + star are the PAKISTANI FLAG SYMBOL, not religious iconography
- ONE focal motif (the flag)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 04 — Quaid's Silhouette
**Mood:** Reverent, founder-honoring, dignified
**Type:** Centered, paired with the silhouette
**Aspect:** 1:1

**Visual Theme:**
- An abstract gold silhouette of the Quaid-e-Azam sits in the upper half
- The silhouette is PROFILE view, simple, dignified
- A small crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep Pakistan green
- This is the FOUNDER, honored with the most iconic of all Pakistani
  patriotic figures

**Color Logic:**
- Primary: Pakistan green (background)
- Secondary: white (text)
- Accent: gold (Quaid silhouette, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│       ╱─╲                          │
│      │   │   (Quaid silhouette)    │
│      │   │                          │
│      │  /                           │
│      │ /                            │
│      │/                             │
│     ╱│                              │
│                                     │
│   "Pakistan Independence Day"       │
│   "14th August Mubarak"             │
│                                     │
│   "Long Live Pakistan"              │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Quaid's Silhouette
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — background)
- Secondary: #FFFFFF (white — text)
- Accent: #E8B923 (gold — Quaid silhouette, crescent, star)

VISUAL ELEMENTS:
- An abstract gold silhouette of the Quaid-e-Azam sits in the upper half
- The silhouette is PROFILE view, simple, dignified
- A small crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep Pakistan green
- ONE focal motif (the Quaid silhouette) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: clean modern sans (condensed, bold)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, accent color

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Quaid silhouette: upper half, ~30% of post width
- Crescent + star: above the silhouette
- Type: lower half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES (CRITICAL — see Section 2.6):
- NO realistic faces, NO detailed facial features
- NO photorealistic portrait
- The silhouette must be a SINGLE, SIMPLE, ABSTRACT form
- The silhouette must be PROFILE view, NEVER frontal
- The silhouette must be CALM and DIGNIFIED, not action pose
- NO depiction in a political context (no Parliament, no microphone)
- NO political party logos or symbols
- NO flags of other nations
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the Quaid silhouette) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 05 — Iqbal's Silhouette
**Mood:** Poetic, philosophical, the national poet
**Type:** Centered, paired with the silhouette
**Aspect:** 1:1

**Visual Theme:**
- An abstract gold silhouette of Allama Iqbal sits in the upper half
- The silhouette is PROFILE view, simple, dignified — perhaps with
  a hint of his iconic sherwani and Jinnah cap
- A small crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep Pakistan green

**Color Logic:**
- Primary: Pakistan green (background)
- Secondary: white (text)
- Accent: gold (Iqbal silhouette, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│       ╱─╲                          │
│      │   │   (Iqbal silhouette)    │
│      │   │                          │
│      │  /                           │
│      │ /                            │
│      │/                             │
│     ╱│                              │
│                                     │
│   "Pakistan Independence Day"       │
│   "14th August Mubarak"             │
│                                     │
│   "Long Live Pakistan"              │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Iqbal's Silhouette
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — background)
- Secondary: #FFFFFF (white — text)
- Accent: #E8B923 (gold — Iqbal silhouette, crescent, star)

VISUAL ELEMENTS:
- An abstract gold silhouette of Allama Iqbal sits in the upper half
- The silhouette is PROFILE view, simple, dignified
- A small crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep Pakistan green
- ONE focal motif (the Iqbal silhouette) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: clean modern sans (condensed, bold)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, accent color

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Iqbal silhouette: upper half, ~30% of post width
- Crescent + star: above the silhouette
- Type: lower half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES (CRITICAL — see Section 2.6):
- NO realistic faces, NO detailed facial features
- NO photorealistic portrait
- The silhouette must be a SINGLE, SIMPLE, ABSTRACT form
- The silhouette must be PROFILE view, NEVER frontal
- The silhouette must be CALM and DIGNIFIED, not action pose
- NO political party logos or symbols
- NO flags of other nations
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the Iqbal silhouette) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 06 — Sir Syed's Silhouette
**Mood:** Educational, foundational, the reformer
**Type:** Centered, paired with the silhouette
**Aspect:** 1:1

**Visual Theme:**
- An abstract gold silhouette of Sir Syed Ahmad Khan sits in the
  upper half
- The silhouette is PROFILE view, simple, dignified
- A small crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep Pakistan green
- Sir Syed is the educational reformer whose vision laid the
  intellectual groundwork for Pakistan

**Color Logic:**
- Primary: Pakistan green (background)
- Secondary: white (text)
- Accent: gold (Sir Syed silhouette, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│       ╱─╲                          │
│      │   │   (Sir Syed silhouette) │
│      │   │                          │
│      │  /                           │
│      │ /                            │
│      │/                             │
│     ╱│                              │
│                                     │
│   "Pakistan Independence Day"       │
│   "14th August Mubarak"             │
│                                     │
│   "Long Live Pakistan"              │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Sir Syed's Silhouette
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — background)
- Secondary: #FFFFFF (white — text)
- Accent: #E8B923 (gold — Sir Syed silhouette, crescent, star)

VISUAL ELEMENTS:
- An abstract gold silhouette of Sir Syed Ahmad Khan sits in the upper half
- The silhouette is PROFILE view, simple, dignified
- A small crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep Pakistan green
- ONE focal motif (the Sir Syed silhouette) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: clean modern sans (condensed, bold)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, accent color

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Sir Syed silhouette: upper half, ~30% of post width
- Crescent + star: above the silhouette
- Type: lower half, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES (CRITICAL — see Section 2.6):
- NO realistic faces, NO detailed facial features
- NO photorealistic portrait
- The silhouette must be a SINGLE, SIMPLE, ABSTRACT form
- The silhouette must be PROFILE view, NEVER frontal
- The silhouette must be CALM and DIGNIFIED, not action pose
- NO political party logos or symbols
- NO flags of other nations
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the Sir Syed silhouette) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 07 — Founders Triptych
**Mood:** Multi-figure honoring, the foundation
**Type:** Centered, paired with the silhouettes
**Aspect:** [VERTICAL] 4:5 (1080 × 1350)

**Visual Theme:**
- THREE abstract gold silhouettes in the upper half:
  - Quaid-e-Azam (founder, largest, center)
  - Allama Iqbal (poet, left)
  - Sir Syed Ahmad Khan (reformer, right)
- Each silhouette is a single, simple, profile form
- A small crescent + star above the triptych
- Type sits in the lower half
- Background: deep Pakistan green

**Color Logic:**
- Primary: Pakistan green (background)
- Secondary: white (text)
- Accent: gold (all three silhouettes, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│   ╱─╲     ╱─╲     ╱─╲             │
│  │   │   │   │   │   │             │
│  │   │   │   │   │   │             │
│  │  /    │  /    │  /              │
│  │ /     │ /     │ /               │
│  │/      │/      │/                │
│ ╱│     ╱│     ╱│                  │
│ (Iqbal) (Quaid) (Sir Syed)         │
│                                     │
│   "Pakistan Independence Day"       │
│   "14th August Mubarak"             │
│                                     │
│   "Long Live Pakistan"              │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 4:5 (1080x1350) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Founders Triptych [VERTICAL]
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — background)
- Secondary: #FFFFFF (white — text)
- Accent: #E8B923 (gold — all three silhouettes, crescent, star)

VISUAL ELEMENTS:
- THREE abstract gold silhouettes in the upper half:
  - Quaid-e-Azam (founder, largest, center)
  - Allama Iqbal (poet, left)
  - Sir Syed Ahmad Khan (reformer, right)
- Each silhouette is a SINGLE, SIMPLE, PROFILE form
- A small crescent + star above the triptych
- Type sits in the lower half
- Background: deep Pakistan green
- ONE focal motif (the triptych) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: clean modern sans (condensed, bold)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, accent color

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Silhouettes: upper half, three in a row, Quaid slightly larger
- Crescent + star: above the triptych
- Type: lower half, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES (CRITICAL — see Section 2.6):
- NO realistic faces, NO detailed facial features
- Each silhouette must be a SINGLE, SIMPLE, ABSTRACT form
- Each silhouette must be PROFILE view, NEVER frontal
- Each silhouette must be CALM and DIGNIFIED, not action pose
- The three silhouettes should NOT overlap
- NO political party logos or symbols
- NO flags of other nations
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the triptych) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 08 — Calligraphy of Freedom
**Mood:** Type-driven, the day's word
**Type:** Massive, the design itself
**Aspect:** 1:1

**Visual Theme:**
- "14th August Mubarak" is THE design — rendered in a bold condensed
  sans-serif at huge scale
- The type appears bold and proud against the deep Pakistan green
- A single hairline gold rule separates title from message
- Background: deep Pakistan green
- A small crescent + star as a micro-element

**Color Logic:**
- Primary: Pakistan green (background)
- Secondary: white (text)
- Accent: gold (hairline rule, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│                                     │
│     1 4 T H   A U G U S T           │
│            M U B A R A K             │
│         ──────────── (rule)         │
│         "Pakistan Independence      │
│          Day"                        │
│                                     │
│         "Long Live Pakistan"        │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 1:1 (1080x1080) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Calligraphy of Freedom
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — background)
- Secondary: #FFFFFF (white — text)
- Accent: #E8B923 (gold — hairline rule, crescent, star)

VISUAL ELEMENTS:
- "14th August Mubarak" is THE design — rendered in a bold condensed
  sans-serif at massive scale (~14-16% of post height)
- A single hairline gold rule separates title from message
- A small crescent + star as a micro-element
- Background: solid deep Pakistan green
- NO second decorative motif. The type is the art.

TYPOGRAPHY:
- Display face: bold condensed sans-serif (the most patriotic option)
- Body face: clean sans-serif
- Hero phrase "14th August Mubarak": 14-16% of post height, centered, secondary
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, accent color
- Letter spacing on hero: +2%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Hero phrase: vertically and horizontally centered, dominates
- Subtitle + message: below the hero, centered
- Negative space: minimum 18% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- ONE focal point (the type) — type-driven
- Maximum one decorative element (the hairline rule) + one micro

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 09 — Geometric Pakistan
**Mood:** Contemplative, balanced, the national pattern
**Type:** Centered inside the mandala
**Aspect:** 1:1

**Visual Theme:**
- A large circular geometric mandala in Pakistan green + gold
- The mandala is PATRIOTIC, with flag-inspired patterns
- A small crescent + star at the top of the outermost ring
- Type sits in the clear circular negative space at the center
- Background: white

**Color Logic:**
- Primary: Pakistan green (mandala fills)
- Secondary: white (background, text)
- Accent: gold (mandala stroke, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│         ╭───────────╮               │
│       ╱   mandala    ╲             │
│      │   ╭───────╮    │             │
│      │  │ "Pakistan"│   │            │
│      │  │   "14th    │   │           │
│      │  │  August"   │   │           │
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
Generate a 1:1 (1080x1080) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Geometric Pakistan
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — mandala fills)
- Secondary: #FFFFFF (white — background, text)
- Accent: #E8B923 (gold — mandala stroke, crescent, star)

VISUAL ELEMENTS:
- A large circular geometric mandala in Pakistan green + gold
- The mandala is PATRIOTIC, with flag-inspired patterns
- A small crescent + star at the top of the outermost ring
- Type sits in the clear circular negative space at the center
- Background: solid white
- ONE focal motif (the mandala) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: clean modern sans (condensed, bold)
- Body face: clean sans-serif
- Title: 10% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Patriotic message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Mandala: optically centered, ~75% of post width
- Type: in the mandala's clear center
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The mandala must be SYMMETRIC and CLEAN, not chaotic
- ONE focal motif (the mandala) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

### Layout 10 — Stained Glass Nation
**Mood:** Jewel-like, dignified, patriotic
**Type:** Centered, in the text panel
**Aspect:** 1:1

**Visual Theme:**
- A geometric stained-glass pattern fills the entire background
- The pattern is divided into clean color blocks (primary + secondary)
- Gold accent appears in 1-2 glass cells
- A clear, unpatterned rectangular panel in the center holds the type
- The contrast between busy pattern and clean panel IS the design

**Color Logic:**
- Primary: Pakistan green (main glass cells)
- Secondary: white (text panel, secondary cells)
- Accent: gold (1-2 glass cells, decorative)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓┌─────────────┐▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "Pakistan   │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ Independ-  │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  ence Day"  │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "14th Aug"  │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "Long Live  │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  Pakistan"  │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓└─────────────┘▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Pakistan Independence
Day" for Gull Real Estate & Builders.

LAYOUT: Stained Glass Nation
EVENT TITLE: "Pakistan Independence Day"
GREETING SUBTITLE: "14th August Mubarak"
PATRIOTIC MESSAGE: "Long Live Pakistan"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #01411C (Pakistan green — main glass cells)
- Secondary: #FFFFFF (white — text panel, secondary cells)
- Accent: #E8B923 (gold — 1-2 glass cells, decorative)

VISUAL ELEMENTS:
- Geometric stained-glass pattern fills the entire background
- Pattern is divided into clean color blocks (no gradients within cells)
- Gold accent appears in 1-2 glass cells
- A clear, unpatterned rectangular panel in the center holds the type
- The contrast between busy pattern and clean panel IS the design
- ONE focal motif (the stained-glass field + central text panel)

TYPOGRAPHY:
- Display face: clean modern sans (condensed, bold)
- Body face: clean sans-serif
- Title: 10% of post height, centered inside the panel, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Patriotic message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, secondary icons + text
- Text panel: ~50% of post width, ~45% of post height, centered
- Negative space: minimum 12% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The pattern must be CLEAN GEOMETRIC, not a chaotic mess
- The gold cells should feel ACCENT, not dominant
- ONE focal motif (the stained-glass field + text panel)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the primary + secondary palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given year's Independence Day post.

| Year's Tone | Recommended Layouts |
|-------------|---------------------|
| Default / flag's symbol | 01 Crescent & Star Hero |
| Monumental, the landmark | 02 Minar-e-Pakistan |
| Movement, festive | 03 Flag Waving |
| Founder-honoring (Quaid) | 04 Quaid's Silhouette |
| Poetic, philosophical | 05 Iqbal's Silhouette |
| Educational, foundational | 06 Sir Syed's Silhouette |
| Multi-figure honoring | 07 Founders Triptych |
| Type-driven, brand-led | 08 Calligraphy of Freedom |
| Contemplative, balanced | 09 Geometric Pakistan |
| Jewel-like, dignified | 10 Stained Glass Nation |
| Default rotation | 01, 02, 04, 08 (one of these per cycle) |

**Recommended rotation pattern (4 years):**
- Year 1: Layout 01 — Crescent & Star Hero
- Year 2: Layout 02 — Minar-e-Pakistan
- Year 3: Layout 04 — Quaid's Silhouette
- Year 4: Layout 08 — Calligraphy of Freedom

This guarantees 4 visually distinct posts over a 4-year cycle, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_national_independence_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_national_independence_01_20260814_v1.png   (Layout 01)
gull_real_estate_builders_national_independence_04_20260814_v1.png   (Layout 04)
gull_real_estate_builders_national_independence_07_20260814_v1.png   (Layout 07, vertical)
```

---

## 6. CTA Bar Specification (Identical Across All 10 Layouts)

The CTA bar is the ONE element that never changes. It anchors brand recognition across all the visual variety above.

```
HEIGHT: bottom 12% of the post
GROUND COLOR: primary color of the selected layout (Pakistan green)
LEFT SIDE: SVG phone icon (stroke: secondary white) + "0314 9393930"
RIGHT SIDE: SVG globe icon (stroke: secondary white) + "gullrealestate.github.io"
DIVIDER: thin vertical line in secondary white, 30% opacity, centered
PADDING: equal left/right padding (8% of post width)
ICON SIZE: 24x24 logical units, scalable
TEXT SIZE: 3% of post height
TEXT COLOR: secondary white
```

### Phone Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[SECONDARY_WHITE]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
</svg>
```

### Globe Icon SVG
```svg
<svg viewBox="0 0 24 24" fill="none" stroke="[SECONDARY_WHITE]" stroke-width="2"
     stroke-linecap="round" stroke-linejoin="round">
  <circle cx="12" cy="12" r="10"/>
  <line x1="2" y1="12" x2="22" y2="12"/>
  <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/>
</svg>
```

---

## 7. Pre-Generation Checklist

Use this for every Independence Day post.

```
□ Layout number selected (01-10)
□ Color palette confirmed (ONLY Pakistan green + white + gold, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-2 micro = max 3)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary ground, secondary icons
□ Aspect ratio: 1:1 default, 4:5 for Layout 07
□ Patriotic rule: composition feels PROUD, UNIFYING, PROFESSIONAL
□ Founder figure rules reviewed (if Layouts 04, 05, 06, 07 used)
□ Mood check: patriotic/proud/celebratory/unifying/hopeful/joyful
□ Prohibited elements reviewed (faces, party logos, religious text,
  party imagery, military combat, etc.)
□ Filename follows convention
```

## 8. Post-Generation Checklist

```
□ No faces or identifiable likenesses (CRITICAL for all founder figures)
□ No mosque with worshippers or prayer scenes
□ No religious text, verses, or Arabic script
□ No political party logos or symbols
□ No flags of other nations
□ No military combat imagery, weapons, or aggressive violence
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
□ Mood is patriotic and unifying, never political-party-aligned
□ IF founder silhouette used (Layouts 04, 05, 06, 07):
  - Silhouette is PROFILE view, NEVER frontal
  - Silhouette is a SIMPLE, ABSTRACT form, not a detailed face
  - Silhouette is CALM and DIGNIFIED, not in action pose
  - Silhouette is NOT in any political context (no Parliament, no mic)
  - The figure reads as SYMBOL, not as portrait
□ Flag (if used in Layout 03) is STYLIZED, not realistic fabric
□ Minar (if used in Layout 02) is STYLIZED, not architectural drawing
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Independence Day-Specific)

Pakistan Independence Day (14th August) commemorates the independence of Pakistan in 1947. It is a day of patriotic celebration, national pride, and unity. The visual treatment must reflect that — but it must remain **unifying, professional, and inclusive**.

- **No political party alignment.** The post must not read as PML-N, PPP, PTI, JI, MQMP, or any other party. NO party flags, NO party colors, NO party slogans, NO party leaders (current or recent). The post is for ALL Pakistanis.
- **No current political figures.** Only the founding historical figures (Jinnah, Iqbal, Sir Syed, Choudhry Rahmat Ali) are honored, and only as ABSTRACT SILHOUETTES, never as realistic faces.
- **Founder figures are honored as SILHOUETTES ONLY.** No realistic faces, no detailed features, no photorealistic portraits. Profile view only. Simple, abstract, dignified. They read as SYMBOL, not as portrait.
- **No military combat imagery.** Independence Day is a celebration of FREEDOM, not a military commemoration. No weapons, no battle scenes, no war imagery. (Defence Day covers military tribute.)
- **No flags of other nations.** Only the Pakistani flag is permitted. No Indian flag, no Allied flags, no UN flag — even in historical context.
- **No religious content.** A greeting in English is fine. Verses, Hadith, Arabic script are not used. The crescent + star are the NATIONAL flag symbol, not religious iconography.
- **No Western party imagery.** No balloons, no confetti, no party hats, no fireworks. Independence Day is patriotic celebration, not Western party.
- **Gold is celebratory, not gaudy.** Use gradients and luminous quality, but don't pile on. Festive, not cheap.
- **Minar-e-Pakistan silhouettes (when used) must be STYLIZED.** A simple geometric tower, not a literal architectural drawing. The Minar is a SYMBOL, not a building.
- **The flag (when used) must be STYLIZED.** Not realistic fabric. The flag is a SYMBOL of national pride, not a banner.
- **Founders Triptych (Layout 07) is the most powerful founder-honoring layout.** It honors the three most important founding figures: Jinnah (the founder), Iqbal (the philosopher-poet), Sir Syed (the educational reformer). They appear together as a TRIBUTE TO THE FOUNDATION, not as a political statement.

The single most important rule for this spec:
> **Unifying, not partisan. Patriotic, not aggressive. Proud, not political. Pakistan is for all Pakistanis.**

When in doubt: **subtract, don't add.** A simpler post is more professional than a busier one. If a layout choice starts to read as "political party poster", "military recruitment ad", "Western party invite", or "sectarian messaging", stop.

---

**Document Version:** 1.0 - Pakistan Independence Day Post Specification
**Last Updated:** July 31, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Pakistan Independence Day annual posts
