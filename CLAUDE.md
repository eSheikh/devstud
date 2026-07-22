# CLAUDE.md — dev-студия landing concepts

## What this is
Set of **landing-page concepts** for a small **dev-студия** (RU market, founder based in Dagestan). Purpose: pick a brand + visual direction. The studio is a **young team, no bureaucracy**, and builds **custom** — сайты/лендинги, корп-сайты, телеграм-боты, интеграции, автоматизация, веб-сервисы/SaaS — never on Битрикс/Тильда constructors. Stacks: **Laravel, Django, Go, Vue, React, PostgreSQL**. Positioning: **доступно** (fair pricing, no brand markup), warm and concrete voice — not premium-aloof. Site language is **Russian only**. Positioning term is **"dev-студия"** — never "агентство" or "студия разработки". Team size is intentionally undisclosed. **No AI-slop copy**: no tricolon anaphora, no buzzwords ("масштабируемый", "с запасом на рост", "бесшовный"), max one characterful joke per page, concrete over pathos.

## Structure
- `/index.html` — gallery linking every brand variant.
- `/<brand>/index.html` — one self-contained concept per brand: `ledev`, `skydream`, `svod`, `assadev`, `granit`, `caspian`, `kanat`, `kb05`, `usta`, `watan` (brand **Vatan**).
- Each variant is standalone (inline CSS/JS, web fonts via Google CDN loaded async: preload + media=print/onload + noscript). No build step. Open the file in a browser.

## Design rules (non-negotiable)
Always run the **frontend-design** skill first. Act as Creative Director. Constraints: no template layouts, no repeated cards, no dashboard hero, no fake charts, no AI clichés; every section a new visual idea; editorial type; asymmetric; premium spacing; cinematic scroll; subtle motion; **accessibility first** (keyboard focus, `prefers-reduced-motion`, responsive to mobile). Bar = Awwwards Site of the Day + converts enterprise. References: Linear, Stripe, Raycast, Apple, Vercel, Notion, Warp, Arc.

## Per-brand structural system (each page = its own metaphor, NOT a re-skin)
- **ledev** — page as a terminal session: typewriter commands, `ls услуги/`, git diff "почему мы", tmux status bar footer. "я ле" (Avar) easter egg.
- **skydream** — altitude ascent: full-viewport chapters 0м→орбита, fixed altimeter rail, sky gradient crossfades per chapter.
- **svod** — normative document ("свод правил"): title page, TOC with dot leaders, §-clauses, appendix table, CTA = форма заявки №1. Swiss typography, klein blue.
- **assadev** — zine/poster wall: rotated scraps on tape, stamps, setlist process, ticket-stub CTA. Zero uniform cards.
- **granit** — architectural elevation: engraved stele hero, services = 4 fluted columns (vertical text) under architrave, masonry-course process (reads bottom-up), cornerstone CTA.
- **caspian** — light nautical chart: coordinate grid, compass rose, services = ports of call with Caspian coords, ship's log process, radiogram CTA.
- **kanat** — tightrope walkers (Цовкра-1): walker figure walks a rope across page top on scroll, rope axis through page, services alternate sides, balance scales, footstep process.
- **kb05** — конструкторское бюро ("05" = Dagestan region code): blueprint cyanotype, millimeter grid, dimension lines on hero, spec table services, маршрутная карта Оп.005–020, GOST title-block footer.
- **usta** — Kubachi silversmiths: blackened silver + gold, rotating hallmark "проба 925", ledger price-list services, craft stages (эскиз→форма→гравировка→чернение), self-drawing ornament.
- **watan/ (brand «Vatan»)** — real geographic map of Dagestan as fixed full-page background, light cartographic style (hand-drawn SVG: Caspian, rivers Terek/Sulak/Samur, graticule, mountain relief, compass). Scroll moves a "camera" over regions (степь → Махачкала → Гуниб → Дербент), city pins activate per section, finale draws the traveled route. Content in translucent blur plates, left column. Brand shown as latin **Vatan** (accent on `a`) everywhere visible; lowercase «ватан» (= родина) kept only where it means the word, not the brand. Contact: **Telegram only** `t.me/vatandev` (email removed by decision), domain `vatandev.com`. Geo-captions per section: plain descriptive, NOT jokes. NOTE: first version (41-cell mosaic) was rejected as ugly/not-a-real-map — real geography, light and beautiful. **Vatan is the chosen brand**; production lives in `~/HomeProjects/landings/vatan/` (identity: тамга-знак V+линия земли, терракота на бумаге; brandbook in `vatan/brand/`), `watan/` here mirrors its deploy files. No «Битрикс»-jabs in copy — neutral «разработка под вашу задачу».
