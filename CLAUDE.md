# CLAUDE.md — McGregor MOT Centre Website Build

## Purpose

This project has a single objective: **build the McGregor MOT Centre website** (mcgregormotcentre.co.uk). All work in this folder is focused exclusively on creating a modern, trustworthy website for this independent Edinburgh garage. Nothing else.

## Scope

- **What we are doing:** Building the McGregor MOT Centre website from scratch using the content, structure, and assets extracted from the original site.
- **What we are NOT doing:** Anything unrelated to this website. This folder is dedicated solely to this build.

## Source Material

All original site content, structure, and assets are documented in these reference files:

| File | Purpose |
|------|---------|
| [BRIEF.md](BRIEF.md) | Full project brief — business info, brand, services, design direction |
| [original/SITE-INDEX.md](original/SITE-INDEX.md) | Original site map and structure |
| [original/assets/](original/assets/) | Logo and hero image |

## Business Identity

- **Name:** McGregor MOT Centre
- **Type:** Independent car garage / MOT testing centre
- **Location:** 5 Steads Place, Edinburgh EH6 5DY (Leith area)
- **Phone:** 0131 554 3999
- **Email:** mcgregormot1@aol.com
- **Hours:** Mon-Fri 8:30am-5:00pm | Sat 9:00am-1:00pm | Sun closed
- **Established:** 40+ years of service (established 1982)
- **Certifications:** VOSA approved MOT testing centre
- **Character:** Honest, friendly, no-nonsense. Small independent garage known for personal service, trustworthy work, and competitive pricing. Strong local reputation.

## Brand Colors

| Role | Color | Hex |
|------|-------|-----|
| Primary | Dark Blue | #003f70 |
| Accent | Orange | #fd5b2f |
| Dark | Navy | #021c51 |
| Neutral | White | #ffffff |
| Text | Dark Gray | #212121 |

## Services

1. **MOT Testing** — VOSA approved, 40+ point inspection
2. **Vehicle Servicing** — Full and interim services
3. **Diagnostic Service** — Engine diagnostics
4. **Vehicle Repairs** — General mechanical repairs
5. **Tyres** — Supply and fitting

## Site Pages to Build

| Page | Key Elements |
|------|-------------|
| Home | Hero with garage imagery, key services, trust signals (VOSA, 20+ years), CTA to book |
| Services | MOT, servicing, diagnostics, repairs, tyres — clear descriptions |
| MOT Info | What's tested, what to expect, how to book |
| Book Online | Simple booking form |
| About | Business story, why choose us |
| Contact / Find Us | Address, map, phone, hours, directions |

## Design Skill

This project uses the **taste-skill** for frontend design guidance. The skill file is at [taste-skill.md](taste-skill.md).

**Key parameters:**

| Parameter | Value | Meaning |
|-----------|-------|---------|
| DESIGN_VARIANCE | 6 | Offset layouts — asymmetric but functional, not chaotic |
| MOTION_INTENSITY | 5 | Fluid CSS transitions, subtle load-in animations |
| VISUAL_DENSITY | 5 | Balanced — informative but not cluttered |

### Design Considerations for This Garage

- **Tone:** Professional, trustworthy, no-nonsense. This is a small honest garage — the website should build trust immediately. Think: "I trust this place with my car."
- **Palette:** Dark blue (#003f70) and orange (#fd5b2f) — strong automotive palette. Zinc/slate neutrals. No purple, no neon.
- **Typography:** Premium sans-serif (Outfit or Satoshi). Bold, clean, readable.
- **Trust is the hero:** VOSA approved badge, 20+ years, customer review quotes, clear contact info. Trust signals should be prominent and repeated.
- **Mobile-first:** Many people search for garages on mobile. The site must be excellent on phones.
- **Simple navigation:** People visiting a garage site want: services, booking, contact. Make these immediately accessible.

## Instructions for Claude

1. **Stay focused.** Every task relates to building the McGregor MOT Centre website.
2. **Reference BRIEF.md** before building any page — do not invent content.
3. **Use existing assets** from `original/assets/`. Use the real logo and hero image.
4. **Apply the taste-skill** on every frontend component.
5. **Build trust.** This is a garage — people need to feel confident before handing over their car.
6. **Keep it fast.** Garage sites should load instantly. Minimal dependencies.
7. **Single-page build files go in `build/`.**
