# Instructions

Always invoke the `frontend-design` skill before any frontend implementation task (building components, pages, or UI code).

---

# Project Brief

## 1. Final Product — Adaptive PDP Design System

### Context
A retail brand wants to personalize experiences beyond recommendations. The product stays the same, but how it's presented should change depending on who the user is. Design teams struggle to manage multiple layouts manually.

### Challenge
- Create an adaptable design system
- A single PDP (Product Detail Page)
- Based on that, generate 2–3 PDP layout versions for the same product, adjusting structure and emphasis based on user behavior or interests (different component order, different emphasis — price, benefits, reviews, bundles)

### User Types
| User Type | Description |
|---|---|
| **Expert user** | Knows what they want |
| **Explorer / browser** | Browsing and discovering |
| **Price-sensitive user** | Primarily motivated by cost |

### Deliverables
- Claude Code setup using a Figma MCP connection ✓
- Design system + reusable components
- Multiple layouts for one product
- Clickable prototype showing the contrast between layouts
- Short explanation of layout logic

---

## 2. Technical Dashboard

### Context
Vibe-code a dashboard UI with Claude MCP. Practice the full pipeline end-to-end. This dashboard should "feed" and/or "manage" the Final Product.

### Deliverables
- Dashboard generated via Claude MCP
- Figma design linked with Code Connect
- At least 1 Framer Motion animation
- Deployed on a public Vercel URL

---

## Project Phases

### Phase 1 — General Setup
- Creating the project's folders ✓
- Setting up Claude Code, Framer Motion, icons, packages, etc. ✓
- Set up GitHub and Vercel

### Phase 2 — Understanding the Project ✓
- Laid out the briefs on a thinking space on Figma ✓
- Parsed the information to determine the project's steps ✓
- Created `CLAUDE.md` based on the brief `[Claude Code — Terminal]` ✓

### Phase 3 — Discovery
- Define the brand and its products `[Claude Sonnet]` ✓
- Generate and refine user personas `[Claude Sonnet]` ✓
- Generate and refine the conceptual elements of the PDP affected by user personas `[Claude Sonnet]` ✓
- Define how the layouts should be affected `[Claude Sonnet]` ✓
- Generate PDP wireframes based on personas `[Claude Code — Terminal]` ✓
- Refine alternative PDP wireframes

### Phase 4 — Design System
- Define the main PDP's look & feel
- Generate DS foundations out of it
- Create a `design-system.md` file based on those foundations
- Generate list of components based on the definitive PDP wireframes `[Claude Code — Terminal]` ✓

### Phase 5 — Final Design
- Create the final designs for each layout using the generated DS
- Generate a working prototype for the PDP
- (Optional) Use at least 1 Framer Motion animation

### Phase 6 — Technical Dashboard
- Generate a technical dashboard to feed the PDP using an existing library and the generated DS
- Start with wireframes, then move to mockups once functionality is defined
- Use at least 1 Framer Motion animation

### Phase 7 — Publish
- Publish the project
- Document the process and present

---

## Brand & Product Brief

### Brand — KOVA

KOVA is a performance running brand built around the idea that every runner has a method. Not a lifestyle, not a vibe — a method. The brand sits between the clinical world of biomechanics labs and the emotional world of personal records. It's precise without being cold, aspirational without being vague.

**Brand voice:** Confident, minimal, evidence-led. No fluff. Every claim is backed by something.

**Tagline:** Run with reason.

### Visual Identity

**Color palette:**
| Role | Value |
|---|---|
| Primary background | Black `#000000` |
| Primary foreground | White `#FFFFFF` |
| Accent (used sparingly) | Deep violet `#1C004B` |

Color load is carried almost entirely by product photography and people imagery.

**Typography:** Raleway. Bold or heavier for titles, all-caps. Square, geometric feel.

**Shapes & layout language:** Minimalistic. Square forms. Generous white space used deliberately to contrast and breathe against dark sections.

**Web application:**
- Main navigation and promo ribbons → dark backgrounds
- Product and content sections → white/light backgrounds with generous spacing
- Color accents appear rarely — used for moments of emphasis only
- Photography and graphics do the heavy visual lifting

**References:** Saucony's web layout and editorial style. Hoka's information architecture. Neither brand's logo or legacy aesthetic.

---

### Product — KOVA NIMBVX PRO

A carbon-plated daily trainer engineered for runners who log serious mileage without sacrificing race-day performance.

**The pitch:** Most carbon-plated shoes are built for race day only — they break down fast and punish slow paces. The NIMBVX PRO was designed to flip that. A dual-density midsole cushions easy days while the full-length carbon plate activates at race pace, giving it a wider use window than any competitor in its class.

#### Key Specs
| Spec | Value |
|---|---|
| Stack height | 38mm heel / 30mm forefoot |
| Heel-to-toe drop | 8mm |
| Weight | 218g (Men's US 9) |
| Plate | Full-length unidirectional carbon fiber |
| Midsole | Dual-density REACTFOAM+ (soft top layer / firm base) |
| Upper | Single-layer engineered mesh with welded overlays |
| Outsole | Zoned rubber patches (heel strike + forefoot) |
| Recommended use | Daily training, tempo, half marathon, marathon |

#### Key Benefits
- Longer shoe lifespan than single-use racers (~700km rated)
- Energy return optimized for 4:30–6:30 min/km pace range
- Reduced leg fatigue on back-to-back training days
- Fits true to size with a slightly roomy toe box

#### Pricing & Bundles
| Option | Price |
|---|---|
| Base price | $229 USD |
| Training Pack — Shoe + no-show socks (×2) + mesh laundry bag | $259 |
| Race Ready — Shoe + race laces + foam roller + digital training plan | $289 |

#### Social Proof
- 4.7 / 5 from 2,340 reviews
- Featured in Runner's World 2025 Gear Guide
- Used by 3 athletes at the 2025 Chicago Marathon podium

---

## User Personas — KOVA NIMBVX PRO

### Persona 1 — The Expert
*Knows What They Want*

| | |
|---|---|
| **Age** | 32–46 |
| **Archetype** | The Optimizer |
| **Core motivation** | Precision. Data. Marginal gains. |
| **Annual mileage** | 1,200+ km |
| **Typical pace** | 4:30–5:30 min/km |
| **Training style** | Structured programs (Strava, TrainingPeaks) |
| **Purchase frequency** | Every 800–1,000 km (~yearly) |
| **Income** | High, disposable |

**Mindset:** "If I can measure it, I can optimize it, I can gain out of it."

**Community:** Running forums, Strava leaderboards, track clubs.

**Values:** Performance, durability, evidence over hype.

**Pain point:** Tired of marketing fluff. Wants real specs.

**PDP behavior:**
- Entry point: Tech specs — stack height, drop, weight, plate material
- Primary CTA: Compare specs / Add to cart
- Content priority: 1. Specs → 2. Reviews → 3. Use cases → 4. Price
- Design signals: Diagrams, close-ups of materials, durability claims backed by data

**Layout implication:** Specs-first. Hero shows stack height, drop, weight, and material. Immediately exposes detailed specs, technical comparisons, and durability data. Minimal lifestyle imagery. Reviews grouped by verified purchase. CTA is "Add to Cart" — they've already decided. No fluff.

---

### Persona 2 — The Explorer
*Browsing & Discovering*

| | |
|---|---|
| **Age** | 22–32 |
| **Archetype** | The Discoverer |
| **Core motivation** | Story. Inspiration. Community. |
| **Annual mileage** | 300–700 km |
| **Typical pace** | 6:00–8:00 min/km |
| **Training style** | Flexible, app-guided (Nike Run Club, Runkeeper) |
| **Purchase frequency** | Every 1–2 years (casual) |
| **Income** | Good |

**Mindset:** "Running is part of my lifestyle, not my obsession."

**Community:** Instagram, TikTok, local running groups.

**Values:** Aesthetics, sustainability, brand story.

**Pain point:** Too much jargon. Just tell me the vibe.

**PDP behavior:**
- Entry point: Lifestyle imagery, reviews from "people like me", brand story
- Primary CTA: Share / Learn more / Add to cart
- Content priority: 1. Imagery & lifestyle → 2. Social proof → 3. Benefits (readable) → 4. Specs
- Design signals: Movement, color through photos, user-generated content, bundles that make sense

**Layout implication:** Story-first. Hero is lifestyle imagery and brand narrative. Benefits come before specs. Minimal specs. Heavy on user-generated content and community reviews. Bundles are prominently displayed. Secondary CTA is "Learn More" — they need to feel the product. Smooth scroll with visual momentum.

---

### Persona 3 — The Price-Conscious
*Primarily Motivated by Cost*

| | |
|---|---|
| **Age** | 25–50 |
| **Archetype** | The Analyzer |
| **Core motivation** | Value. Longevity. ROI. |
| **Annual mileage** | 400–900 km |
| **Typical pace** | 5:30–7:30 min/km |
| **Training style** | Mixed (casual to semi-structured) |
| **Purchase frequency** | Every 1.5–2 years (budget-conscious) |
| **Income** | Budget-conscious — maximizes value |

**Mindset:** "Is this worth $229? What else could I get for that money?"

**Community:** Reddit (r/running), comparison forums.

**Values:** Cost-per-mile, longevity, proven durability.

**Pain point:** Premium shoes feel like a luxury I can't justify.

**PDP behavior:**
- Entry point: Price, competitor comparison, cost-per-mile calculation
- Primary CTA: View bundles / Compare prices / See reviews
- Content priority: 1. Price & bundles → 2. Cost-per-mile → 3. Longevity claims → 4. Reviews
- Design signals: Value indicators, bundle savings, durability data, long-term user testimonials

**Layout implication:** Value-first. Price and bundles above the fold. Cost-per-mile calculator is prominent. Comparison table shows NIMBVX PRO vs. competitors. Durability data (700km rated) emphasized. Reviews filtered to long-term users. CTA emphasizes bundles and savings.

---

### Key Insight

Same product, three different information hierarchies. Each persona enters the PDP with a different question in mind — the layout answers that question first before revealing everything else.

| Persona | First question | Layout priority |
|---|---|---|
| The Expert | "Does it perform?" | Specs → Reviews → Price |
| The Explorer | "Does it fit my life?" | Story → Benefits → Social proof |
| The Price-Conscious | "Is it worth it?" | Price → Value proof → Durability |
