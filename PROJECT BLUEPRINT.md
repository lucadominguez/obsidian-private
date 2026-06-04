# Skool Empire — Project Blueprint

**Last updated:** June 4, 2026
**Status:** Content production phase (Month 1 in progress)

---

## 1. GOALS

### Primary
Build 5 paid subscription communities that generate $75K-$500K+/month combined revenue by creating premium content that justifies $99-$997/month pricing.

### Secondary
- Create a content generation system that produces non-AI-sounding, information-dense articles indistinguishable from top-tier Substack writers
- Build a reusable voice taxonomy from 24 analyzed elite writers
- Establish programmatic quality standards (matplotlib charts, verified citations, audit framework)
- Create a multi-platform funnel (YouTube → Substack → email → paywall) that maximizes content ROI

### The Bet
People will pay $149-$997/month for content that is:
1. Information-dense (every paragraph contains a specific number, mechanism, or citation)
2. Voice-authentic (reads like Scott Alexander, not ChatGPT)
3. Data-backed (charts generated programmatically from real data, not AI-hallucinated)
4. Question-driven (answers interesting questions, doesn't give broad overviews)

---

## 2. THE 5 COMMUNITIES

| # | Community | Price/Mo | Persona | Status |
|---|---|---|---|---|
| 1 | The Research Collective | $149-$997 | Dr. Elias Voss | 4 articles written |
| 2 | Claims Warfare | $149-$599 | Tom Barrett | 1 article written |
| 3 | Chronic Illness Hacking | $99-$399 | Lauren Mitchell | 1 article written |
| 4 | Credential Engineering | $99-$499 | Sarah Chen | 1 article written |
| 5 | Debt Elimination | $99-$399 | Alex Rivera | 1 article written |

### Revenue Math
| Scenario | Members/Community | Avg Revenue | Per Community/Mo | 5 Communities/Mo |
|---|---|---|---|---|
| Conservative | 100 | $149 | $14,900 | $74,500 |
| Moderate | 300 | $199 | $59,700 | $298,500 |
| Optimistic | 500 | $249 | $124,500 | $622,500 |

---

## 3. PERSONAS (Voice DNA)

Each persona has a complete backstory, physical description, voice DNA breakdown, and signature phrases.

| Persona | Voice DNA | Key Moves |
|---|---|---|
| **Dr. Elias Voss** — Biochemist, self-experimenter | 30% Scott Alexander + 20% Import AI + 20% SemiAnalysis + 15% Dwarkesh + 15% pure Elias | Footnotes with jokes, mechanism obsession, self-deprecation, "I'm not a doctor but here's the data" |
| **Tom Barrett** — Former insurance adjuster | 40% Tom's own + 25% SemiAnalysis + 20% Scott Alexander + 15% Shkreli | "I used to write that denial letter," insider confession, Midwestern directness |
| **Lauren Mitchell** — ME/CFS survivor | 35% Lauren's own + 25% Scott Alexander + 20% Import AI + 20% pure empathy | "You're not crazy. You're not alone," patient-as-expert, gentle determination |
| **Sarah Chen** — Immigrant engineer | 40% Sarah's own + 25% Chamath + 20% Balaji + 15% a16z | "Your skills matter. Your paperwork shouldn't," framework-driven, precise |
| **Alex Rivera** — Debt survivor | 40% Alex's own + 25% Investing Comp. + 20% Scott Alexander + 15% Shkreli | "They're counting on you not knowing your rights," numbers-as-weapons, working-class directness |

Full profiles with backstories, physical descriptions, and Midjourney prompts in `Persona Profiles.md`.

---

## 4. THE VOICE SYSTEM

### Substack Voice Taxonomy
24 elite writers analyzed across 4 scraping batches. Each writer analyzed for: opening style, sentence rhythm, data handling, unmistakable voice, verbal tics, personal/research balance, transition style, and signature move.

| Batch | Writers | Archetypes |
|---|---|---|
| Batch 1 (Tech) | Dwarkesh, SemiAnalysis, Latent.Space, The Generalist, Balaji | Socratic Autodidact, Insider Who Knows, Enthusiastic Curator, Polished Interviewer, Prophet-Technologist |
| Batch 2 (VC/AI) | a16z, Import AI, NewLimit, AI Futures Project | Curated Platform, Moral Analyst, Builder-Scientist, Artist-Critic |
| Batch 3 (Finance) | Shkreli, Cummings, Chamath, Predictive History, Investing Comp., Rogue Funds, Seabrick, Library of Alexandria, Sean Cai | Performative Contrarian, Systems Theorist, Framework Builder, Esoteric Analyst, Enthusiastic Retail Investor |
| Batch 4 (Rationalist) | Scott Alexander, Robin Hanson, Jason Crawford, Vitalik, cdixon | Self-Deprecating Intellectual, Alien Anthropologist, Warm Optimist, Polymath, VC-as-Historian |

### Voice Spectrum Map
```
PERSONAL ────────────────────────────── INSTITUTIONAL
Kate Armstrong     Scott Alexander    a16z
Martin Shkreli     Import AI          Chamath
Balaji             Dwarkesh           NewLimit

ESSAYISTIC ──────────────────────────── BRIEFING-STYLE
Cummings           Scott Alexander    SemiAnalysis
Kate Armstrong     Dwarkesh           Chamath
Predictive Hist.   Balaji             NewLimit
```

### Cross-Cutting Patterns (All 24 Writers)
**What NONE do (AI tells):** generic openings, hedging every claim, signposting, filler phrases, uniform paragraph length, generic conclusions

**What ALL do (human patterns):** confidence without hedging, the zoom-out move (specific → structural → civilizational), insider signaling, self-referential ecosystem, varied paragraph length, opinions not just reporting, specificity, the "I" is present

### 29 Anti-AI Patterns
Full detection list covering: content patterns (6), language patterns (7), style patterns (6), communication patterns (3), filler patterns (7). Source: Wikipedia WikiProject AI Cleanup + humanizer skill.

---

## 5. CONTENT PIPELINE

### Article Pipeline
```
Research → Plan → Write → Humanize → Illustrate → Format → Publish
```

### Video Pipeline (NEW)
```
Script → Slides (HTML+Playwright) → Voiceover (TTS) → Assembly (ffmpeg) → YouTube
                                                                              ↓
                                                                  Clips: Shorts/TikTok/Reels
```

### Multi-Platform Funnel
```
YouTube (weekly) → Substack article (Wed) → X thread (Thu) → clips (daily)
                                                         ↓
                                               Email capture → nurture → paywall
```

One script produces: video + article + thread + 3-5 social clips.

### Article Structure Rules
- Question-driven, not topic-driven (Chamath-style)
- Each section answers a specific interesting question
- Never the same section shape twice
- Paragraph length varies wildly

### Quality Standards
- Every paragraph: specific number, mechanism, or citation
- Charts: matplotlib, 200 DPI, dark theme, real data arrays
- Citations: verified DOIs/PMIDs, no AI-hallucinated references
- Tables: HTML-styled, not vanilla markdown
- Voice: passes anti-AI audit (29 patterns)

---

## 6. CONTENT PRODUCED

### Research Collective (4 articles)
| # | Title | Type | Charts | Words |
|---|---|---|---|---|
| 01 | "What Your Bloodwork Is Actually Telling You" | Flagship | Forest plot, homocysteine comparison | ~5K |
| 02 | "The Protocol That Fixed My Depression" | Origin story | SHAPS timeline, biomarker transformation | ~3.5K |
| 03 | "BPC-157: Five Questions Nobody Is Asking" | Bridge to paid | Dosing table, mechanism citations | ~2.5K |
| 04 | "I Analyzed 200 Blood Panels" | Data reveal | 4 aggregate charts | ~2K |

### Paid Content
- BPC-157 Protocol Guide (17KB, 3 verified DOIs)

### Other Communities (1 article each)
- Claims Warfare: "What Your Adjuster Knows That You Don't"
- Chronic Illness Hacking: "You're Not Crazy. You're Not Alone"
- Credential Engineering: "Your Skills Matter. Your Paperwork Shouldn't"
- Debt Elimination: "They're Counting On You Not Knowing Your Rights"

---

## 7. VISUAL SYSTEM

### Three-Tier Visual Architecture

| Tier | Method | Risk | Use Case |
|---|---|---|---|
| **Scientific charts** | matplotlib + real data arrays | Zero — fully deterministic | Data visualization, before/after, timelines |
| **Rendered infographics** | HTML/CSS/Chart.js → Playwright PNG | Zero — code-generated | Dashboards, playbook cards, decision trees |
| **Research figures** | PubMed-indexed papers with verified DOIs | Low — peer-reviewed | Supporting evidence, credibility signals |

### Chart Types Available
- Before/after forest plots (horizontal bar per marker)
- Grouped bar charts (comparison by category)
- Time series with milestone annotations
- Horizontal bar with error bars (IQR)
- Pie/donut charts (composition)
- Radar/spider charts (z-score transformation)

### Design System
- Dark theme: #0f172a background, #34d399 (good), #f59e0b (threshold), #f87171 (bad)
- Fonts: JetBrains Mono + Inter
- Resolution: 200 DPI minimum
- All axes labeled, units on axes, source attribution

---

## 8. SKILLS BUILT

| Skill | What It Does | Trigger |
|---|---|---|
| `paid-content-voice-toolkit` | 24-writer voice taxonomy + 29 anti-AI patterns + 8 advanced humanization techniques | "write paid content", "humanize" |
| `scientific-charts` | matplotlib chart generation with dark theme design system | "generate chart", "data visualization" |
| `content-quality-audit` | 25-point accuracy/coherence/visual/citation audit | "audit article", "verify citations" |
| `substack-publishing` | Email-to-Substack (Himalaya) + Playwright browser automation | "publish to substack" |
| `video-slideshow-pipeline` | Script → slides → TTS → ffmpeg → MP4 → YouTube | "generate video", "slideshow" |

### Skills Available (External)
| Skill | Value |
|---|---|
| `professional-writer` | Full pipeline: research → plan → write → humanize → illustrate → format → publish |
| `business-model-design` | 5 reasons people pay, funnel architecture, pricing psychology |
| `comfyui` | Image generation via Stable Diffusion (needs GPU/Cloud install) |
| `baoyu-article-illustrator` | Article illustrations with type×style×palette |
| `himalaya` | IMAP/SMTP email (for Substack post-by-email) |
| `humanizer` | 29 anti-AI patterns + voice injection |

---

## 9. QUALITY SYSTEM

### Audit Framework
25-point checklist across 4 dimensions:
1. **Accuracy** (8 checks): numbers, citations, claims, units, mechanisms, contradictions, disclaimers, chart data
2. **Coherence** (6 checks): narrative arc, section flow, voice consistency, audience fit, CTA, information density
3. **Visual** (6 checks): data accuracy, readability, density, quality, attribution, anti-AI
4. **Citations** (5 checks): real papers, correct context, open access preferred, recency, no fabrication

### Review Cadence
- Pre-publication: full audit
- 30 days post: re-audit with new data
- Quarterly: playbook accuracy review
- 6 months: citation refresh

---

## 10. RESEARCH DATABASE

15 verified papers across 5 topics, all PubMed-indexed with DOIs:
- BPC-157: Seiwerth 2018, Chang 2011, Sikiric 2016
- ME/CFS: Baraniuk 2024 (meta-analysis), Kerr 2020, Eckey 2025
- Homocysteine: Rai 2017 (meta-analysis), Liew 2015, Wang 2022
- Cardiovascular: Ridker 2007 (Reynolds landmark), Cook 2012, Lee 2020
- LDN: Toljan 2018 (mechanism), Patten 2018 (clinical), Tamariz 2024

---

## 11. VAULT STRUCTURE

```
work/ (obsidian-private on GitHub)
├── Skool Empire Hub.md              ← Master index
├── Persona Profiles.md              ← All 5 persona backstories
├── Quality Audit Framework.md       ← 25-point checklist
│
├── Research Collective/
│   ├── Publication Hub.md
│   ├── Content Pipeline.md          ← Upgraded with video funnel
│   ├── Free vs Paid Strategy.md
│   ├── Editorial Calendar.md
│   ├── Research Papers Database.md  ← 15 verified papers
│   ├── Substack Analysis - Batch 1-4.md  ← 24 writer analyses
│   ├── Articles/
│   │   ├── 01 - The 12 Markers.md
│   │   ├── 02 - The Protocol That Fixed My Depression.md
│   │   ├── 03 - Five Questions About BPC-157.md
│   │   └── 04 - I Analyzed 200 Blood Panels.md
│   ├── Playbooks/
│   │   └── BPC-157 Protocol Guide.md
│   └── Visuals/
│       ├── fig1-before-after-forest.png
│       ├── fig2-homocysteine-comparison.png
│       ├── fig-depression-timeline.png
│       ├── fig-depression-biomarkers.png
│       ├── fig-normal-vs-optimal.png
│       ├── fig-biomarker-predictors.png
│       ├── fig-time-to-optimal.png
│       ├── fig-missed-patterns.png
│       ├── 12-markers-dashboard.html
│       └── Dashboard Infographic.md
│
├── Claims Warfare/
│   ├── Publication Hub.md
│   ├── Content Pipeline.md
│   ├── Editorial Calendar.md
│   ├── Free vs Paid Strategy.md
│   ├── Persona - Tom Barrett.md
│   ├── Seeding Content - First 14 Days.md
│   ├── Articles/
│   │   └── 01 - What Your Adjuster Knows.md
│   └── Visuals/
│       ├── fig-claims-first-offer.png
│       ├── adjuster-playbook.html
│       └── Adjuster Playbook Infographic.md
│
├── Chronic Illness Hacking/
│   ├── Publication Hub.md
│   ├── Content Pipeline.md
│   ├── Editorial Calendar.md
│   ├── Free vs Paid Strategy.md
│   └── Articles/
│       └── 01 - You're Not Crazy.md
│
├── Credential Engineering/
│   ├── Publication Hub.md
│   ├── Content Pipeline.md
│   ├── Editorial Calendar.md
│   ├── Free vs Paid Strategy.md
│   └── Articles/
│       └── 01 - Your Skills Matter.md
│
├── Debt Elimination/
│   ├── Publication Hub.md
│   ├── Content Pipeline.md
│   ├── Editorial Calendar.md
│   ├── Free vs Paid Strategy.md
│   ├── Articles/
│   │   └── 01 - They're Counting On You.md
│   └── Visuals/
│       ├── fig-credit-score-recovery.png
│       ├── fig-debt-composition.png
│       ├── debt-decision-tree.html
│       └── Decision Tree Infographic.md
│
└── _assets/
    ├── profile-EV.png (Elias Voss)
    ├── profile-TB.png (Tom Barrett)
    ├── profile-LM.png (Lauren Mitchell)
    ├── profile-SC.png (Sarah Chen)
    ├── profile-AR.png (Alex Rivera)
    └── profile-photo-prompts.md (Midjourney/DALL-E)
```

---

## 12. NEXT PRIORITIES

1. **More articles** — complete Month 1 editorial calendar for Research Collective (1 more article) and start Claims Warfare
2. **Paid playbooks** — Cerebrolysin Protocol Guide, Roof Claim Playbook, LDN Protocol Guide
3. **Video production** — generate the first slideshow video to test the pipeline
4. **Profile photos** — generate real AI photos with Midjourney/DALL-E prompts
5. **Email nurture sequences** — write the 7-day welcome sequences
6. **Lead magnets** — produce the downloadable PDFs
7. **Substack setup** — configure Himalaya for email-to-Substack posting
8. **YouTube channel** — set up channel, upload first video
9. **Social clips** — generate Shorts/TikTok/Reels from video content
10. **Funnel testing** — drive real traffic and measure conversion rates