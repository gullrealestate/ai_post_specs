# Gull Real Estate & Builders - Pakistan Defence Day Post Specification

## Document Overview
This is a **standalone, single-event specification** for generating social media posts for **Pakistan Defence Day** (6th September — Shahadat-e-6th September, honoring the martyrs of the 1965 war and Pakistan's defenders). It is a companion to the main Gull Real Estate & Builders spec and follows all of its core identity rules (company name, contact, logo handling, prohibited elements). What this document adds is a **strict design language** and **10 distinct layouts** so the same event can be published with visual variety year over year.

Defence Day is the **third national event** in the natural sequence. Where Independence Day is celebration and Pakistan Day is commemoration, **Defence Day is solemn tribute**. The day honors the martyrs of the 1965 war with India and all the defenders of Pakistan — soldiers, officers, and civilians who gave their lives. The visual register is **subdued, respectful, restrained patriotic** — closer to Youm-e-Ashura in tone than to Independence Day. The post should always feel like a moment of silent gratitude, not celebration.

The 10 layouts feature Pakistani iconography (crescent + star, Minar-e-Pakistan, the flag) and **stylized silhouettes of founding figures** — but rendered in a more restrained, respectful way than on Independence Day or Pakistan Day. The black + white + green palette grounds the post in solemnity.

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
   (CRITICAL — Defence Day honors the DEFENDERS, not the WAR)
❌ NO tanks, jets, missiles, guns, or military equipment of any kind
❌ NO battle scenes, war scenes, or specific historical battles
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
  * Primary: #1A1A1A (deep black)
  * Secondary: #FFFFFF (white)
  * Accent: #01411C (Pakistan green)
- No fourth color. No exceptions.
- Gradient stops are allowed ONLY between Primary and Secondary
  (the black and white natural flow), or between Primary and
  Accent (black and green).
- The Primary (deep black) is the dominant element — used
  for backgrounds and as the foundation of the composition.
  Black grounds the post in SOLEMNITY.
- The Secondary (white) is the breathing room — used for type,
  text contrast, and the white band of the flag.
- The Accent (Pakistan green) is the PATRIOTIC element — used
  sparingly for the crescent + star, decorative motifs, and
  CTA icons. Green appears in RESTRAINED amounts — not as a
  full background like on Independence Day.
- Backgrounds: solid black, solid white, or a black-to-white
  gradient. NOTHING else.
- Text contrast: AAA where possible, AA at minimum
```

### 2.2 Typography Discipline
```
- Use EXACTLY TWO typefaces per post:
  * One display face (the EVENT TITLE)
  * One body face (subtitle, message, CTA)
- The display face must be a refined, dignified serif (Didone or
  modern transitional) OR a clean modern sans. NO calligraphic
  faces, NO playful faces — the tone is subdued, not festive.
- The body face is always a clean, highly legible sans-serif.
- Type sizes (as % of post height):
  * Event Title: 9-11% (slightly smaller than Independence Day —
    the day is more restrained)
  * Subtitle / Greeting: 3.5-4.5%
  * Patriotic Message: 3%
  * CTA: 3%
- Letter spacing on the title: +2% to +4% (slightly more expanded
  than other specs — silence has space)
- Title and message must remain readable at 200×200 thumbnail size
```

### 2.3 Composition Discipline
```
- One focal point only. The eye should land on it within 0.5 seconds.
- Grid: 12-column virtual grid; elements snap to thirds or halves.
- Negative space: minimum 25% of the post must be empty. More
  breathing room than any other national event spec — silence
  is the design.
- The CTA bar always sits in the bottom 12% of the post.
- The logo space always sits in the top-left 18% × 18% box.
- The event title is always centered on the dominant axis.
- SOLEMN RULE: the composition should feel STILL, RIGID, HONORING.
  Decoration is more restrained than Independence Day or Pakistan Day.
  Maximum 1-2 motifs per post.
- No element may overlap the logo space or the CTA bar.
```

### 2.4 Decorative Discipline
```
- Decorative elements are SYMBOLIC, PATRIOTIC, and SOLEMN.
- Allowed motifs: Pakistani flag crescent + star (stylized, in
  green or white), Minar-e-Pakistan silhouette (stylized, in
  white on black or black on white), abstract flag at half-mast
  (NOT realistic fabric), stylized silhouettes of founding
  figures (Quaid-e-Azam, Allama Iqbal, Sir Syed Ahmad Khan,
  Choudhry Rahmat Ali — all as abstract silhouettes ONLY),
  abstract geometric salute (a single hand-salute shape, very
  abstract), simple geometric Islamic patterns, abstract
  ornamental rules and frames.
- Maximum TWO decorative motifs per post. (Defence Day is
  RESTRAINED — 2 motifs is the cap, but the post should feel
  closer to 1 motif + minimal ornament.)
- Decorative opacity: hero motif 60-100%, micro-element 20-40%.
- Patterns are reserved for backgrounds only, at ≤10% opacity
  (lower than other specs — the post should feel still).
- No decorative element may be placed inside the logo space.
- The "abstract geometric salute" (Layout 02) is a single simple
  geometric shape suggesting a salute — NOT a literal hand, NOT
  a hand-drawn gesture, NOT a military gesture specifically. Just
  a single abstract geometric line/shape.
- Flags (when used) must be STYLIZED, not realistic fabric. The
  Pakistani flag is the ONLY flag permitted. The "half-mast"
  treatment is just a slight visual shift down, NOT a literal
  flag-pole-and-cloth depiction.
- Minar-e-Pakistan silhouettes (when used) must be STYLIZED,
  non-identifiable as anything other than a generic tower.
```

### 2.5 Mood Discipline
```
Defence Day honors the martyrs of the 1965 war and all defenders
of Pakistan.

ALLOWED MOODS:
  - Solemn
  - Reverent
  - Quiet
  - Respectful
  - Grateful
  - Patriotic (in a sober, respectful way)
  - Still
  - Honoring

NOT ALLOWED MOODS (would betray the spirit of the day):
  - Western-party (balloons, confetti, neon, "happy birthday" feel)
  - Celebratory
  - Festive
  - Political-party-aligned
  - Loud or aggressive
  - Militant
  - Sectarian
  - Military recruitment ad aesthetic
  - Materialistic
  - Decorative-for-its-own-sake

If a layout choice starts to read as "military recruitment ad",
"war movie poster", "political party poster", or "Western party
invite", stop. Defence Day is SOLEMN TRIBUTE — respectful,
subdued, honoring the fallen, not celebrating war.
```

### 2.6 Founder Figure Rules (CRITICAL)
```
FOUNDING FIGURES may be honored via ABSTRACT SILHOUETTES ONLY.

ALLOWED:
  - Stylized black or white silhouettes of:
    * Quaid-e-Azam Muhammad Ali Jinnah (founder, most iconic)
    * Allama Muhammad Iqbal (national poet, philosopher)
    * Sir Syed Ahmad Khan (educational reformer, Aligarh founder)
    * Choudhry Rahmat Ali (coined the name "Pakistan")
  - The silhouette must be a SINGLE, SIMPLE, ABSTRACT form
  - The silhouette must be PROFILE or 3/4 view, NEVER frontal
    with detailed facial features
  - The silhouette must be CALM and DIGNIFIED, not action pose
  - The silhouette must be even MORE restrained than on
    Independence Day or Pakistan Day — the day is somber

NOT ALLOWED:
  - NO realistic faces
  - NO detailed facial features (eyes, nose, mouth)
  - NO photorealistic portraits
  - NO action poses (no gesturing, no military poses, no salutes)
  - NO depiction in military contexts (no uniform, no parade,
    no battlefield, no specific historical scene)
  - NO depiction in a way that could be confused with a
    political party leader or a current military figure
  - NO depiction of the figures in religious contexts

WHY SILHOUETTES:
  - Likenesses of real people are restricted in commercial use
  - Silhouettes are the standard for honoring founding figures
    in professional Pakistani design
  - Silhouettes avoid any political controversy
  - Silhouettes read as SYMBOL, not as portrait

WHEN IN DOUBT:
  - If the silhouette starts to look like a real portrait,
    simplify it further until it's clearly a SHAPE, not a face
  - Defence Day silhouettes should be EVEN MORE RESTRAINED
    than Independence Day or Pakistan Day silhouettes
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

## 3. The 10 Pakistan Defence Day Layouts

Each layout is a complete design system. Pick the layout that matches this year's mood, then run the prompt.

### Layout 01 — Crescent of Remembrance
**Mood:** Subdued, the flag's symbol at half-mast
**Type:** Centered, beneath the crescent
**Aspect:** 1:1

**Visual Theme:**
- A green crescent + star sit in the upper half — the Pakistani
  flag's symbol, but RENDERED IN SOLEMN GREEN ON BLACK
- A few small stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep black

**Color Logic:**
- Primary: deep black (background)
- Secondary: white (small stars, text)
- Accent: Pakistan green (crescent, hero star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ✦ ✦               │
│                                     │
│   ╱⌒⌒⌒⌒⌒⌒⌒⌒⌒⌒╲                 │
│ ╱   crescent + star   ╲             │
│ │       ✦             │             │
│  ╲                   ╱              │
│   ╲_______________╱                │
│       ✦       ✦                    │
│                                     │
│                                     │
│   "Defence Day"                     │
│   "6th September"                   │
│                                     │
│   "Salute to our heroes"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 01:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Crescent of Remembrance
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — background)
- Secondary: #FFFFFF (white — small stars, text)
- Accent: #01411C (Pakistan green — crescent, hero star)

VISUAL ELEMENTS:
- A green crescent + star in the upper half — the Pakistani flag's
  symbol, but RENDERED IN SOLEMN GREEN ON BLACK
- A few small white stars trail along the crescent's curve
- Type sits in the lower half, in the calm
- Background: deep black
- ONE focal motif (the crescent + star)

TYPOGRAPHY:
- Display face: refined modern serif (Didone or transitional)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Crescent + star: upper half, ~45% of post width (smaller than
  Independence Day's heroic scale)
- Star trail: along the crescent's curve
- Type: lower half, centered
- Negative space: minimum 25% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery, weapons, or aggressive violence
- NO tanks, jets, missiles, guns, or military equipment
- NO battle scenes, war scenes, or specific historical battles
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The crescent + star are the PAKISTANI FLAG SYMBOL, not religious
  iconography. They read as SOLEMN, not celebratory.
- ONE focal motif (the crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

### Layout 02 — Martyrs' Salute
**Mood:** Honoring the fallen, abstract tribute
**Type:** Centered, paired with the abstract salute
**Aspect:** 1:1

**Visual Theme:**
- A single abstract geometric "salute" shape in white sits in the
  upper half — NOT a literal hand, NOT a hand-drawn gesture
- The salute is a single simple geometric form (an upward line,
  a triangular wedge, or a simple vertical mark)
- A small crescent + star at the salute's apex
- Type sits in the lower half
- Background: deep black

**Color Logic:**
- Primary: deep black (background)
- Secondary: white (the abstract salute, text)
- Accent: Pakistan green (crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│                                     │
│             │                       │
│             │   (abstract salute)  │
│             │                       │
│             │                       │
│                                     │
│                                     │
│   "Defence Day"                     │
│   "6th September"                   │
│                                     │
│   "Salute to our heroes"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 02:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Martyrs' Salute
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — background)
- Secondary: #FFFFFF (white — the abstract salute, text)
- Accent: #01411C (Pakistan green — crescent, star)

VISUAL ELEMENTS:
- A single abstract geometric "salute" shape in white sits in the
  upper half
- The salute is a SIMPLE GEOMETRIC form (an upward line, a
  triangular wedge, or a simple vertical mark)
- A small crescent + star at the salute's apex
- Type sits in the lower half
- Background: deep black
- ONE focal motif (the abstract salute) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: refined modern serif (Didone or transitional)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Abstract salute: upper-center, ~15% of post width (a single
  simple vertical form)
- Crescent + star: at the salute's apex
- Type: lower half, centered
- Negative space: minimum 25% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES (CRITICAL for this layout):
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery, weapons, or aggressive violence
- NO tanks, jets, missiles, guns, or military equipment
- NO battle scenes, war scenes, or specific historical battles
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- CRITICAL — THE ABSTRACT SALUTE MUST BE:
  * A SINGLE SIMPLE GEOMETRIC FORM (upward line, triangular
    wedge, or simple vertical mark)
  * NOT a literal hand
  * NOT a hand-drawn gesture
  * NOT a military gesture specifically
  * NOT depicting any fingers, palm, wrist, or body part
  * The salute reads as ABSTRACT SYMBOL of tribute, not as
    a literal hand or gesture
- ONE focal motif (the abstract salute) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

### Layout 03 — Minar-e-Pakistan
**Mood:** The monument, in subdued palette
**Type:** Centered, around the monument
**Aspect:** 1:1

**Visual Theme:**
- A stylized Minar-e-Pakistan silhouette rises in the upper-center
- The Minar is rendered in white on black — subdued, not the bright
  white-on-green of Independence Day
- Type wraps around the Minar or sits below it
- A small crescent + star at the Minar's apex (in green)
- Background: deep black

**Color Logic:**
- Primary: deep black (background)
- Secondary: white (Minar silhouette, text)
- Accent: Pakistan green (crescent, star at apex)

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
│   "Defence Day"                     │
│   "6th September"                   │
│                                     │
│   "Salute to our heroes"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 03:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Minar-e-Pakistan
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — background)
- Secondary: #FFFFFF (white — Minar silhouette, text)
- Accent: #01411C (Pakistan green — crescent, star at apex)

VISUAL ELEMENTS:
- A stylized Minar-e-Pakistan silhouette rises in the upper-center
- The Minar is rendered in WHITE on BLACK — subdued, solemn
- A small green crescent + star at the Minar's apex
- Type wraps around the Minar or sits below it
- Background: deep black
- ONE focal motif (the Minar)

TYPOGRAPHY:
- Display face: refined modern serif (Didone or transitional)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Minar: upper-center, ~30% of post width
- Crescent + star: at the Minar's apex
- Type: below the Minar, centered
- Negative space: minimum 25% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery, weapons, or aggressive violence
- NO tanks, jets, missiles, guns, or military equipment
- NO battle scenes, war scenes, or specific historical battles
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The Minar must be STYLIZED, not a literal architectural drawing
- The Minar reads as SOLEMN, not celebratory
- ONE focal motif (the Minar)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

### Layout 04 — Quaid's Silhouette
**Mood:** Reverent, founder-honoring, dignified
**Type:** Centered, paired with the silhouette
**Aspect:** 1:1

**Visual Theme:**
- An abstract white silhouette of the Quaid-e-Azam sits in the upper half
- The silhouette is PROFILE view, simple, dignified
- A small green crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep black
- The Quaid is honored as the founder who built the nation that
  the defenders protect

**Color Logic:**
- Primary: deep black (background)
- Secondary: white (Quaid silhouette, text)
- Accent: Pakistan green (crescent, star)

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
│                                     │
│   "Defence Day"                     │
│   "6th September"                   │
│                                     │
│   "Salute to our heroes"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 04:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Quaid's Silhouette
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — background)
- Secondary: #FFFFFF (white — Quaid silhouette, text)
- Accent: #01411C (Pakistan green — crescent, star)

VISUAL ELEMENTS:
- An abstract white silhouette of the Quaid-e-Azam sits in the upper half
- The silhouette is PROFILE view, simple, dignified
- A small green crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep black
- ONE focal motif (the Quaid silhouette) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: refined modern serif (Didone or transitional)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Quaid silhouette: upper half, ~30% of post width
- Crescent + star: above the silhouette
- Type: lower half, centered
- Negative space: minimum 25% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES (CRITICAL — see Section 2.6):
- NO realistic faces, NO detailed facial features
- NO photorealistic portrait
- The silhouette must be a SINGLE, SIMPLE, ABSTRACT form
- The silhouette must be PROFILE view, NEVER frontal
- The silhouette must be CALM and DIGNIFIED, not action pose
- NO military context (no uniform, no parade, no battlefield)
- NO political party logos or symbols
- NO flags of other nations
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the Quaid silhouette) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

### Layout 05 — Iqbal's Silhouette
**Mood:** Poetic, philosophical, the soul of the nation
**Type:** Centered, paired with the silhouette
**Aspect:** 1:1

**Visual Theme:**
- An abstract white silhouette of Allama Iqbal sits in the upper half
- The silhouette is PROFILE view, simple, dignified
- A small green crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep black
- Iqbal is honored as the philosopher-poet whose words inspire
  the defenders

**Color Logic:**
- Primary: deep black (background)
- Secondary: white (Iqbal silhouette, text)
- Accent: Pakistan green (crescent, star)

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
│                                     │
│   "Defence Day"                     │
│   "6th September"                   │
│                                     │
│   "Salute to our heroes"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 05:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Iqbal's Silhouette
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — background)
- Secondary: #FFFFFF (white — Iqbal silhouette, text)
- Accent: #01411C (Pakistan green — crescent, star)

VISUAL ELEMENTS:
- An abstract white silhouette of Allama Iqbal sits in the upper half
- The silhouette is PROFILE view, simple, dignified
- A small green crescent + star sits above the silhouette
- Type sits in the lower half, in the calm
- Background: deep black
- ONE focal motif (the Iqbal silhouette) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: refined modern serif (Didone or transitional)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Iqbal silhouette: upper half, ~30% of post width
- Crescent + star: above the silhouette
- Type: lower half, centered
- Negative space: minimum 25% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES (CRITICAL — see Section 2.6):
- NO realistic faces, NO detailed facial features
- NO photorealistic portrait
- The silhouette must be a SINGLE, SIMPLE, ABSTRACT form
- The silhouette must be PROFILE view, NEVER frontal
- The silhouette must be CALM and DIGNIFIED, not action pose
- NO military context
- NO political party logos or symbols
- NO flags of other nations
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- ONE focal motif (the Iqbal silhouette) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

### Layout 06 — Crescent & Star at Half-Mast
**Mood:** Subdued patriotic, the flag at rest
**Type:** Centered, beneath the lowered crescent
**Aspect:** 1:1

**Visual Theme:**
- A green crescent + star sit slightly LOWER in the post — visually
  offset as if at half-mast (a quiet visual gesture, not a literal
  flag-pole-and-cloth)
- A few small white stars trail along the crescent's curve
- Type sits in the lower half, with extra breathing room
- Background: deep black

**Color Logic:**
- Primary: deep black (background)
- Secondary: white (small stars, text)
- Accent: Pakistan green (crescent, hero star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]                              │
│                                     │
│                                     │
│                                     │
│                                     │
│   ╱⌒⌒⌒⌒⌒⌒⌒⌒⌒⌒╲                 │
│ ╱   crescent + star   ╲             │
│ │       ✦             │             │
│  ╲                   ╱              │
│   ╲_______________╱                │
│       ✦       ✦                    │
│                                     │
│   "Defence Day"                     │
│   "6th September"                   │
│                                     │
│   "Salute to our heroes"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 06:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Crescent & Star at Half-Mast
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — background)
- Secondary: #FFFFFF (white — small stars, text)
- Accent: #01411C (Pakistan green — crescent, hero star)

VISUAL ELEMENTS:
- A green crescent + star sit slightly LOWER in the post — visually
  offset as if at half-mast (a quiet visual gesture)
- A few small white stars trail along the crescent's curve
- Type sits in the lower half, with extra breathing room
- Background: deep black
- ONE focal motif (the crescent + star at half-mast)

TYPOGRAPHY:
- Display face: refined modern serif (Didone or transitional)
- Body face: clean sans-serif
- Title: 10% of post height, centered, secondary color
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, secondary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Crescent + star: VERTICALLY OFFSET DOWN (visually at half-mast)
- Star trail: along the crescent's curve
- Type: lower half, centered, with extra breathing room above
- Negative space: minimum 30% of post is empty (more than Layout 01)
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery, weapons, or aggressive violence
- NO tanks, jets, missiles, guns, or military equipment
- NO battle scenes, war scenes, or specific historical battles
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The crescent + star are the PAKISTANI FLAG SYMBOL, not religious
  iconography. They read as SOLEMN, not celebratory.
- The "half-mast" treatment is just a slight visual shift down,
  NOT a literal flag-pole-and-cloth depiction
- ONE focal motif (the crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

### Layout 07 — Geometric Pakistan (Solemn)
**Mood:** Contemplative, balanced, restrained
**Type:** Centered inside the mandala
**Aspect:** 1:1

**Visual Theme:**
- A large circular geometric mandala in black + white, with green
  accents
- The mandala is SUBTLE and SOLEMN — less decorative than the
  Eid or Independence Day versions
- A small green crescent + star at the top of the outermost ring
- Type sits in the clear circular negative space at the center
- Background: white

**Color Logic:**
- Primary: deep black (mandala stroke, deepest fills)
- Secondary: white (background, text)
- Accent: Pakistan green (mandala accents, crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│         ╭───────────╮               │
│       ╱   mandala    ╲             │
│      │   ╭───────╮    │             │
│      │  │ "Defence │   │            │
│      │  │   Day"   │   │           │
│      │  │ "6 Sept" │   │           │
│      │   ╰───────╯    │             │
│       ╲             ╱              │
│         ╰───────────╯               │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 07:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Geometric Pakistan (Solemn)
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — mandala stroke, deepest fills)
- Secondary: #FFFFFF (white — background, text)
- Accent: #01411C (Pakistan green — mandala accents, crescent, star)

VISUAL ELEMENTS:
- A large circular geometric mandala in black + white, with green
  accents
- The mandala is SUBTLE and SOLEMN — less decorative than other
  specs' mandala versions
- A small green crescent + star at the top of the outermost ring
- Type sits in the clear circular negative space at the center
- Background: solid white
- ONE focal motif (the mandala) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: refined modern serif (Didone or transitional)
- Body face: clean sans-serif
- Title: 10% of post height, centered, primary color
- Subtitle: 4% of post height, centered, primary at 85%
- Patriotic message: 3% of post height, centered, primary at 75%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Mandala: optically centered, ~72% of post width
- Type: in the mandala's clear center
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery, weapons, or aggressive violence
- NO tanks, jets, missiles, guns, or military equipment
- NO battle scenes, war scenes, or specific historical battles
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The mandala must be SYMMETRIC and CLEAN, not chaotic
- The mandala reads as SOLEMN, not celebratory
- ONE focal motif (the mandala) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

### Layout 08 — Calligraphy of Tribute
**Mood:** Type-driven, the tribute's word
**Type:** Massive, the design itself
**Aspect:** 1:1

**Visual Theme:**
- "Salute to our heroes" is THE design — the explicit tribute,
  rendered in a refined serif at large scale
- A single hairline white rule separates title from message
- Background: deep black
- A small green crescent + star as a micro-element

**Color Logic:**
- Primary: deep black (background)
- Secondary: white (text, hairline rule)
- Accent: Pakistan green (crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│                                     │
│     S A L U T E   T O               │
│       O U R   H E R O E S           │
│         ──────────── (rule)         │
│         "Defence Day"               │
│         "6th September"             │
│                                     │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 08:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Calligraphy of Tribute
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — background)
- Secondary: #FFFFFF (white — text, hairline rule)
- Accent: #01411C (Pakistan green — crescent, star)

VISUAL ELEMENTS:
- "Salute to our heroes" is THE design — the explicit tribute,
  rendered in a refined serif at massive scale (~13-15% of post height)
- A single hairline white rule separates title from message
- A small green crescent + star as a micro-element
- Background: solid deep black
- NO second decorative motif. The type is the art.

TYPOGRAPHY:
- Display face: refined Didone or modern serif
- Body face: clean sans-serif
- Hero phrase "Salute to our heroes": 13-15% of post height, centered, secondary
- Title: 4% of post height, centered, secondary at 85%
- Subtitle: 3% of post height, centered, secondary at 75%
- Letter spacing on hero: +3%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Hero phrase: vertically and horizontally centered, dominates
- Title + date: below the hero, centered
- Negative space: minimum 25% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery, weapons, or aggressive violence
- NO tanks, jets, missiles, guns, or military equipment
- NO battle scenes, war scenes, or specific historical battles
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- ONE focal point (the type) — type-driven
- Maximum one decorative element (the hairline rule) + one micro

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

### Layout 09 — Stained Glass Nation (Solemn)
**Mood:** Jewel-like, dignified, restrained
**Type:** Centered, in the text panel
**Aspect:** 1:1

**Visual Theme:**
- A geometric stained-glass pattern fills the entire background
- The pattern is divided into clean color blocks (black + white)
- A small green accent appears in 1-2 glass cells
- A clear, unpatterned rectangular panel in the center holds the type
- The contrast between busy pattern and clean panel IS the design

**Color Logic:**
- Primary: deep black (main glass cells)
- Secondary: white (text panel, secondary cells)
- Accent: Pakistan green (1-2 glass cells, decorative)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓┌─────────────┐▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "Defence    │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  Day"       │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "6 Sept"    │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│ "Salute to  │▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓│  our heroes"│▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓└─────────────┘▓▓▓▓▓▓▓▓▓▓▓ │
│  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 09:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Stained Glass Nation (Solemn)
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — main glass cells)
- Secondary: #FFFFFF (white — text panel, secondary cells)
- Accent: #01411C (Pakistan green — 1-2 glass cells, decorative)

VISUAL ELEMENTS:
- Geometric stained-glass pattern fills the entire background
- Pattern is divided into clean color blocks (no gradients within cells)
- A small green accent appears in 1-2 glass cells
- A clear, unpatterned rectangular panel in the center holds the type
- The contrast between busy pattern and clean panel IS the design
- ONE focal motif (the stained-glass field + central text panel)

TYPOGRAPHY:
- Display face: refined modern serif (Didone or transitional)
- Body face: clean sans-serif
- Title: 10% of post height, centered inside the panel, secondary color
- Subtitle: 4% of post height, centered, secondary at 80%
- Patriotic message: 3% of post height, centered, secondary at 70%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Text panel: ~50% of post width, ~50% of post height, centered
- Negative space: minimum 15% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery, weapons, or aggressive violence
- NO tanks, jets, missiles, guns, or military equipment
- NO battle scenes, war scenes, or specific historical battles
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The pattern must be CLEAN GEOMETRIC, not a chaotic mess
- The green cells should feel ACCENT, not dominant
- ONE focal motif (the stained-glass field + text panel)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

### Layout 10 — Number Six
**Mood:** The date as quiet monument
**Type:** Centered, paired with the numeral
**Aspect:** 1:1

**Visual Theme:**
- A single monumental white numeral "6" rendered in a refined
  serif occupies the upper half (the day: 6th September)
- A small green crescent + star sits inside or beside the numeral
- Type sits in the lower half, smaller
- Background: deep black
- The numeral reads as a QUIET MONUMENT, not as a date stamp

**Color Logic:**
- Primary: deep black (background)
- Secondary: white (numeral, text)
- Accent: Pakistan green (crescent, star)

**Composition Grid:**
```
┌─────────────────────────────────────┐
│ [LOGO]              ☾ ✦               │
│                                     │
│                                     │
│                                     │
│                6                    │
│                                     │
│                                     │
│                                     │
│   "Defence Day"                     │
│   "6th September"                   │
│                                     │
│   "Salute to our heroes"            │
│                                     │
├─────────────────────────────────────┤
│  📞 0314 9393930  │  🌐 gullreal... │
└─────────────────────────────────────┘
```

**Worked Prompt — Layout 10:**
```
Generate a 1:1 (1080x1080) social media post for "Defence Day" for
Gull Real Estate & Builders.

LAYOUT: Number Six
EVENT TITLE: "Defence Day"
GREETING SUBTITLE: "6th September - Shahadat-e-6th September"
PATRIOTIC MESSAGE: "Salute to our heroes"
COMPANY ATTRIBUTION: "Gull Real Estate & Builders"

COLOR PALETTE (only these 3 colors are allowed in the entire post):
- Primary: #1A1A1A (deep black — background)
- Secondary: #FFFFFF (white — numeral, text)
- Accent: #01411C (Pakistan green — crescent, star)

VISUAL ELEMENTS:
- A single monumental white numeral "6" rendered in a refined
  serif occupies the upper half
- A small green crescent + star sits inside or beside the numeral
- Type sits in the lower half, smaller
- Background: deep black
- ONE focal motif (the numeral) + ONE micro (crescent + star)

TYPOGRAPHY:
- Display face: refined Didone or modern serif (for the numeral AND the title)
- Body face: clean sans-serif
- Numeral "6": 30-40% of post height, centered, secondary
- Title: 8% of post height, centered, secondary
- Subtitle: 4% of post height, centered, secondary at 85%
- Patriotic message: 3% of post height, centered, secondary at 75%
- Letter spacing on title: +3%

COMPOSITION:
- Logo space: clean top-left 18% × 18% box — EMPTY, reserved
- CTA bar: bottom 12%, primary ground, accent icons + text
- Numeral: upper half, monumental, centered
- Type: lower half, smaller, centered
- Negative space: minimum 30% of post is empty
- No element overlaps logo space or CTA bar

STRICT RULES:
- NO faces, no likenesses, no people
- NO mosque with worshippers or prayer scenes
- NO religious text, verses, or Arabic script
- NO political party logos or symbols
- NO flags of other nations
- NO military combat imagery, weapons, or aggressive violence
- NO tanks, jets, missiles, guns, or military equipment
- NO battle scenes, war scenes, or specific historical battles
- NO Western party imagery
- NO bird, nest, or emblem in the logo space
- The numeral must be a CALM, MONUMENTAL number — not stylized,
  not Eastern Arabic, not a logo
- Use Western numeral "6" only (universal readability)
- The numeral reads as a QUIET MONUMENT, not as a date stamp
- ONE focal motif (the numeral) + ONE micro (crescent + star)

QUALITY: High, polished, no artifacts. Harmonize the user-uploaded logo
with the secondary + accent palette naturally.
```

---

## 4. Layout Selection Guide

A practical guide for picking a layout for a given year's Defence Day post.

| Year's Tone | Recommended Layouts |
|-------------|---------------------|
| Default / the flag at rest | 01 Crescent of Remembrance, 06 Crescent at Half-Mast |
| Honoring the fallen, abstract | 02 Martyrs' Salute |
| The monument | 03 Minar-e-Pakistan |
| Founder-honoring (Quaid) | 04 Quaid's Silhouette |
| Poetic, philosophical | 05 Iqbal's Silhouette |
| Contemplative, balanced | 07 Geometric Pakistan (Solemn) |
| Type-driven, brand-led | 08 Calligraphy of Tribute |
| Jewel-like, dignified | 09 Stained Glass Nation (Solemn) |
| The date as monument | 10 Number Six |
| Default rotation | 01, 04, 08, 10 (one of these per cycle) |

**Recommended rotation pattern (4 years):**
- Year 1: Layout 01 — Crescent of Remembrance
- Year 2: Layout 04 — Quaid's Silhouette
- Year 3: Layout 08 — Calligraphy of Tribute
- Year 4: Layout 10 — Number Six

This guarantees 4 visually distinct posts over a 4-year cycle, all staying within the strict design language.

---

## 5. File Naming Convention

```
gull_real_estate_builders_national_defence_[LAYOUT_NUMBER]_[YYYYMMDD]_v1.png

Examples:
gull_real_estate_builders_national_defence_01_20260906_v1.png   (Layout 01)
gull_real_estate_builders_national_defence_08_20260906_v1.png   (Layout 08)
gull_real_estate_builders_national_defence_10_20260906_v1.png   (Layout 10)
```

---

## 6. CTA Bar Specification (Identical Across All 10 Layouts)

The CTA bar is the ONE element that never changes. It anchors brand recognition across all the visual variety above.

```
HEIGHT: bottom 12% of the post
GROUND COLOR: primary color of the selected layout (deep black)
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

Use this for every Defence Day post.

```
□ Layout number selected (01-10)
□ Color palette confirmed (ONLY black + white + green, no fourth)
□ Type system confirmed (display face + body face, no more)
□ Decorative motifs counted (1 hero + 0-1 micro = max 2)
□ Logo space: top-left 18% × 18%, EMPTY, reserved
□ CTA bar: bottom 12%, primary ground, secondary icons
□ Aspect ratio: 1:1 default
□ Solemn rule: composition feels STILL, RIGID, HONORING
□ Founder figure rules reviewed (if Layouts 04, 05 used)
□ Mood check: solemn/reverent/quiet/respectful/grateful
□ Prohibited elements reviewed (faces, military combat, party logos,
  religious text, military equipment, party imagery, etc.)
□ Filename follows convention
```

## 8. Post-Generation Checklist

```
□ No faces or identifiable likenesses
□ No mosque with worshippers or prayer scenes
□ No religious text, verses, or Arabic script
□ No political party logos or symbols
□ No flags of other nations
□ No military combat imagery, weapons, or aggressive violence
□ No tanks, jets, missiles, guns, or military equipment of any kind
□ No battle scenes, war scenes, or specific historical battles
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
□ Mood is solemn and respectful, never celebratory or militant
□ IF founder silhouette used (Layouts 04, 05):
  - Silhouette is PROFILE view, NEVER frontal
  - Silhouette is a SIMPLE, ABSTRACT form, not a detailed face
  - Silhouette is CALM and DIGNIFIED, not in action pose
  - NO military context (no uniform, no parade, no battlefield)
  - The figure reads as SYMBOL, not as portrait
□ IF abstract salute used (Layout 02):
  - The salute is a SIMPLE GEOMETRIC FORM
  - NOT a literal hand, NOT a hand-drawn gesture
  - NOT depicting any fingers, palm, wrist, or body part
□ File named per Section 5 convention
```

---

## 9. Cultural Sensitivity Reminder (Defence Day-Specific)

Defence Day (6th September — Shahadat-e-6th September) commemorates the martyrs of the 1965 war with India and honors all defenders of Pakistan. The visual treatment must reflect that — but it must remain **solemn, respectful, and restrained**.

- **No military combat imagery.** Defence Day honors the DEFENDERS, not the WAR. No tanks, no jets, no missiles, no guns, no military equipment of any kind. No battle scenes, no war scenes, no specific historical battles. The day is a TRIBUTE, not a war movie.
- **No celebration imagery.** This is NOT a party. No balloons, no confetti, no fireworks, no festive elements. The day is solemn, not celebratory.
- **No political party alignment.** The post must not read as PML-N, PPP, PTI, JI, MQMP, or any other party. NO party flags, NO party colors, NO party slogans, NO party leaders (current or recent).
- **No current political figures.** Only the founding historical figures (Jinnah, Iqbal, Sir Syed, Choudhry Rahmat Ali) are honored, and only as ABSTRACT SILHOUETTES, never as realistic faces.
- **Founder figures are honored as SILHOUETTES ONLY.** Even MORE restrained than on Independence Day or Pakistan Day. The day is somber. Profile view only. Simple, abstract, dignified. No military context (no uniform, no parade, no battlefield).
- **The "abstract salute" (Layout 02) is a SIMPLE GEOMETRIC FORM.** NOT a literal hand, NOT a hand-drawn gesture, NOT a military gesture specifically. Just an abstract line or wedge suggesting tribute. The salute reads as ABSTRACT SYMBOL, not as a literal hand.
- **No flags of other nations.** Only the Pakistani flag is permitted. No Indian flag (especially important given the 1965 war context — the Indian flag is OFF-LIMITS, period).
- **No religious content.** A greeting in English is fine. Verses, Hadith, Arabic script are not used. The crescent + star are the NATIONAL flag symbol, not religious iconography.
- **Gold is replaced by GREEN as the accent.** Defence Day's palette is somber black + white + restrained green. There is NO gold in this spec. The mood is not festive enough for gold.
- **Minar-e-Pakistan silhouettes (when used) must be STYLIZED.** A simple geometric tower, not a literal architectural drawing.
- **The "half-mast" treatment (Layout 06) is just a slight visual shift down**, not a literal flag-pole-and-cloth depiction.
- **Defence Day is the most restrained of all national event specs.** Maximum 2 motifs per post, minimum 25% negative space, no calligraphic faces, no decorative excess.

The single most important rule for this spec:
> **Tribute, not celebration. Solemn, not militant. Honoring the fallen, not depicting war.**

When in doubt: **subtract, don't add.** A simpler post is more respectful than a busier one. If a layout choice starts to read as "war movie poster", "military recruitment ad", "political party poster", or "Western party invite", stop.

---

**Document Version:** 1.0 - Pakistan Defence Day Post Specification
**Last Updated:** July 31, 2026
**Classification:** Internal Template Specification
**Use:** AI Image Generation Prompts for Gull Real Estate & Builders - Pakistan Defence Day annual posts
