# Pokémon Scarlet Academy — Claude Code Project Memory

> This file is the persistent project memory for Claude Code. Read it at the start of every session. It contains everything needed to work on this project without re-explanation.

---

## About Cole

Cole is a 14-year-old autistic homeschooler with a PDA (Pathological Demand Avoidance) profile. He lives in Wisconsin (Sun Prairie). He is approximately 8th grade level:
- **Reading:** at grade level
- **Writing:** middle school range (claim-and-evidence writing is an identified gap)
- **Math:** approximately 5th–6th grade level (math resistance addressed separately by a weekly 1:1 tutor — not a focus here)

**Strengths:** science curiosity, deep interest learning, systems thinking, research skills, hands-on engagement. Engages deeply once started.

**Challenges:** autistic inertia, task initiation, sensitivity to perceived demands, prefers working independently.

Cole benefits from a slow start to mornings and engages best between 9 AM and 2 PM. A typical learning day includes 2–4 activities totaling roughly 2–3 hours, in 30–60 minute increments, around a schedule of appointments (physical therapy, movement therapy, mental health therapy, and experiential therapy at Heartland Farm Sanctuary).

**Career aspiration:** Paleontologist. This is a serious, curriculum-shaping vocational direction — not a childhood interest. It should be centered in learning design wherever possible.

---

## Educational Philosophy — NON-NEGOTIABLE

All learning design must:
- **Prioritize autonomy and emotional safety above all else**
- Use **declarative and invitational language** — never demands. Example: "I wonder what you'd notice..." not "Look at this and tell me..."
- Allow **flexible output formats** — drawing, speaking, voice memo, models, slides, writing are all equally valid
- Avoid compliance-based systems or reward/punishment framing
- Focus on real-world, interest-based, project learning
- Keep tasks manageable and low-pressure — small wins matter enormously

**PDA-friendly design principles:**
- Choice architecture at task launch is intentional and important (Cole chooses which Gym to do)
- "Cole's choice" decision points within activities give genuine ownership
- Never frame activities as requirements
- Independent work windows must be truly self-directed

---

## The Pokémon Scarlet Academy Framework

Learning is organized into **Gyms**, each containing:
- **Trial 1** — introductory activity
- **Trial 2** — building activity
- **Main Challenge** — culminating project or demonstration

All student-facing language uses Pokémon-style quest framing. Cole chooses which Gym to work on — this choice architecture is what makes the system work (approximately 90% success rate).

### Dual-Audience Structure
Every Gym document has two audiences:
- **Cole-facing content** — quest language, declarative tone, flexible output options
- **Parent Guide sections** — collapsible, collapsed by default, containing: time estimates, anticipated difficulties, facilitation tips, standards alignment notes

---

## Completed Gyms (Badges Earned)

| Gym | Badge | Status |
|-----|-------|--------|
| 🕐 Rotom Clock Gym | Analog Time Badge | ✅ Complete — all Trials and Main Challenge done |
| 🦅 Archen's Field Report Gym | Taphonomy Badge | ✅ Complete — all Trials and Main Challenge done |

---

## Active Gyms (In Progress)

| Gym | File | Status |
|-----|------|--------|
| ⚡ Rotom-Dex Research Gym | `gyms/rotom-dex-research.html` | Trial 1 complete |
| 🦴 Professor Sada's Fossil Math Gym | `gyms/fossil-math.html` | Not yet started |
| 🦖 Burpee Fossil Lab Gym | `gyms/burpee-fossil-lab.html` | Ongoing — visit log, portfolio tracker |
| 🎮 Scratch Brachiosaurus Game | `gyms/scratch-game.html` | Trials 2–12 planned; Trials 2–3 complete |

---

## Burpee Museum of Natural History

Cole volunteers **every Wednesday** at the Burpee Museum of Natural History in Rockford, IL (~1.5 hours each way). He:
- Cleans real fossils excavated from dig sites in Utah and Montana
- Assists with reptile care and feeding
- Logs hours and activities toward a formal high school transcript

This is a cornerstone of his education and identity. The goal is a **4-year high school pathway** anchored in this work. All Burpee hours are tracked for transcript purposes.

**Transcript language:** Applied Paleontology Practicum — hands-on fossil preparation and specimen documentation at a working natural history museum.

---

## Active Projects

### Scratch — Brachiosaurus Survival Game
Cole is building a dinosaur survival game in Scratch. Completed so far:
- Movement with arrow keys
- Fixed sprite rotation (left/right)
- Trial 2: Hunger variable + decay
- Trial 3: Food sprite + feeding mechanic

Planned trials (4–12):
- Trial 4: Hunger cap + danger state
- Trial 5: Movement upgrade
- Trial 6: Thirst system
- Trial 7: Water zones on the map
- Trial 8: Wading effect (JWE-inspired — speed reduction + color tint in water)
- Trial 9: Roaming hazard (Cole's choice of type)
- Trial 10: Score counter
- Trial 11: Game Over screen with score display
- Trial 12: Restart button / replayability

**Design notes:** Cole loves Jurassic World Evolution (1, 2, 3). The wading effect was directly inspired by JWE's large sauropod animations. Cole's long-term vision is an AAA-style game — Scratch is the starting point.

### Burpee Fossil Lab Portfolio
An interactive HTML field log (localStorage) where Cole documents each Burpee visit. Includes visit-by-visit entries, badge progress tracker, and transcript-ready language.

---

## Current Learning Tools

- **Journeys with PDA** — biweekly bespoke learning boxes (10 activities, interest-led, Wisconsin standards-aligned)
- **Mia Academy** — digital learning platform
- **Night Zookeeper** — digital learning platform
- **ABCya** — supplementary digital activities
- **Weekly 1:1 math tutor** — handles math resistance separately; not a focus here
- **Canva** — all Gym visual design (cards, weekly schedules)
- **Scratch** — game development project
- **toytheater.com/clock** — analog time learning

---

## Identified Learning Gaps (Living Document)

These are known gaps. New gaps should be flagged proactively as they emerge.

| Gap | Gym Addressing It | Status |
|-----|------------------|--------|
| Field Report Writing (claim + evidence) | Archen's Field Report Gym | ✅ Gym complete |
| Analog time telling | Rotom Clock Gym | ✅ Gym complete |
| Research process skills | Rotom-Dex Research Gym | In progress |
| Math integration into science | Fossil Math Gym | Built, not started |
| Computer science / computational thinking | Scratch game project | In progress |
| Long-form writing stamina | Future gym — not yet built | Flagged |
| Capstone research project | Future gym — not yet built | On horizon |

---

## Standards Alignment

All work aligns with **Wisconsin DPI middle and high school standards**. Primary standard sets in use:
- **ELA:** RI.8.1, RI.8.6, W.8.2, W.8.7, W.8.8 (research, evidence, argument)
- **Science:** NGSS MS-LS, MS-ESS (life science, earth science)
- **Social Studies:** SS.Hist, SS.Geog (integrated where relevant)
- **Computer Science:** CS standards via Scratch project

Track completed standards in the Excel spreadsheet (separate from this repo).

---

## Repository File Structure

```
scarlet-academy/
├── CLAUDE.md                    ← this file
├── index.html                   ← hub/home page
├── gyms/
│   ├── burpee-fossil-lab.html
│   ├── archen-field-report.html
│   ├── rotom-dex-research.html
│   ├── fossil-math.html
│   └── scratch-game.html
└── schedules/
    └── week-may-4-2026.html
```

---

## HTML File Design Conventions

All Gym HTML files follow these conventions:

**Fonts:**
- Headers/badges: `Press Start 2P` (Google Fonts) — pixel/retro feel
- Body text: `Nunito` (Google Fonts) — warm, rounded, readable

**Color palette (Scarlet Academy):**
- Scarlet: `#C1391B` / Dark: `#8B2010`
- Gold: `#F5C842` / Dark: `#C9A020`
- Cream background: `#FFF8ED`
- Parchment: `#F2E8D0`
- Ink/dark: `#1A1008`
- Forest green: `#2E6B3E`
- Sky blue: `#2563A8`
- Purple: `#6B3FA0`

**Day/subject color coding:**
- Monday/Thursday (scarlet): `#C1391B`
- Tuesday (forest green): `#2E6B3E`
- Wednesday/Burpee (purple): `#6B3FA0`
- Friday (blue): `#2563A8`

**Structure:**
- Dark ink background (`#1A1008`) with colored card elements
- Gold (`#F5C842`) text on dark headers
- Collapsible Parent Guide sections (collapsed by default)
- Progress bars and completion banners
- Checkboxes / interactive elements where appropriate
- localStorage for data that should persist (Burpee field log)

**Language rules (student-facing):**
- Always declarative and invitational — never imperative demands
- Pokémon quest framing throughout
- Pokémon characters used as guides (Archen, Rotom-Dex, Professor Sada, etc.)
- "Cole's choice" decision points built into activities
- Flexible output options always listed

---

## Standing Instructions for Claude Code

1. **Always use declarative, invitational language** in all student-facing content — this is non-negotiable
2. **Ask before assuming** — if anything about a task is unclear, ask rather than guess
3. **Reputable sources only** — PBS, Smithsonian, National Geographic, museum sites, universities. No random blogs or unverified sites
4. **Proactively flag new learning gaps** aligned to Wisconsin middle/high school standards
5. **Treat paleontology as a serious vocational goal** — center it in design wherever possible
6. **Match existing design conventions** — fonts, colors, and structure defined above
7. **Dual-audience structure always** — Cole-facing content + collapsed Parent Guide
8. **Small wins matter** — scaffold to meet Cole where he is today, with a clear eye toward post-secondary readiness over time
9. **Cole is a systems thinker** — "how things work" framing resonates strongly
10. **When building Scratch trials** — step-by-step, parent-friendly, with anticipated stumbling points noted in Parent Guide

---

## Weekly Planning Notes

Weekly planning now happens here. When Dawn provides a week's time windows and constraints, ask clarifying questions before building the plan — specifically about: Gym readiness (what Cole has recently completed or is mid-stream on), Cole's current interests and energy, and any recent momentum to build on.

---
## Resource Verification Policy

# Standing Instruction — Resource Verification

## The Problem This Solves
Claude sometimes suggests specific videos, articles, tools, or resources with confident details (title, platform, length, URL) that turn out not to exist or not to match the description. This wastes time and erodes trust. This instruction eliminates that.

---

## The Rule

**Before recommending any specific resource — video, article, tool, website, book, or platform feature — Claude must be certain it exists as described.**

This applies to:
- YouTube videos (specific titles, channels, lengths)
- TED / TED-Ed lessons
- Museum or institution web pages
- Specific articles from named publications
- App features or platform capabilities
- Any named resource with specific details attached

---

## What Claude Should Do Instead

### If Claude is certain the resource exists:
Recommend it with the URL or enough detail to find it easily.

### If Claude is not certain:
Use one of these approaches:

**Option 1 — Search first**
Use web search to verify the resource exists before recommending it. Then provide the confirmed title and URL.

**Option 2 — Describe the type, not the specific item**
Instead of: *"Watch the TED-Ed video on Animal Farm (~5 min)"*
Say: *"A short explainer video on Animal Farm's political allegory — I can search for a verified option if you'd like"*

**Option 3 — Flag uncertainty explicitly**
If suggesting something Claude isn't sure about, say so clearly:
*"There may be a TED-Ed lesson on this — worth searching, but I haven't confirmed it exists."*

---

## What Claude Should Never Do
- Name a specific video, article, or resource with confident details without having verified it
- Include approximate lengths, publication dates, or descriptions for unverified resources
- Present a suggested resource as though it has been previewed or confirmed when it hasn't

---

## The Standard
If Dawn or Cole can't find it in under 60 seconds, the suggestion wasn't good enough.

---

*Add this instruction to: CLAUDE.md (VS Code project) and Claude.ai project instructions*

*Last updated: May 2026*
*Maintained by: Dawn (Cole's mom and homeschool lead)*