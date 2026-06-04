# CAMACHO TRAINING MANUAL — PROJECT STATE (Updated 2026-06-04)

## WHAT THIS PROJECT IS
Plug-and-play pipeline for the camacho USA (commercial foodservice + laundry design firm) sales/proposal training manual. Each section is a self-contained interactive HTML file with sidebar nav, quiz, flashcards, video/audio from Drive, and a cut-card printout.

---

## THE WEBSITE — LIVE ON NETLIFY

| Item | Value |
|---|---|
| Netlify project | willowy-horse-ed9122 |
| Live URL | https://willowy-horse-ed9122.netlify.app |
| GitHub repo | https://github.com/DreamCasterProductions/camacho-training-manual |
| Deploy method | GitHub push auto-deploys to Netlify |

---

## V3 FORMAT — THE STANDARD (match this for all rebuilds)

Reference file: `camacho_Section_L_Master_Glossary.html`

Every section must have:
- Fixed topbar with camacho logo + section title + quick links
- Fixed left sidebar with group labels and section navigation
- Cover page (navy background, large letter, subtitle, nav cards grid)
- Media page (Drive video iframe + Drive audio iframe + infographic + mindmap images)
- Subsection pages (crumb + subsec-tag + subsec-title + subsec-lede + content)
- Callout types: expert (navy/gold), rule (cream/navy), files (blue-tint), best (green-tint), warn (red-tint)
- Quiz page (15 questions, 4 options, letter circles)
- Answer Legend pages (navy background, 2 parts)
- Flashcard Grid page (2-col grid, navy front, white back)
- Interactive Flip Cards page (single card with prev/next + dots)
- Cut Cards page (2-col dashed-border grid, printable)
- JavaScript: flip card logic + sidebar scroll tracking

Brand tokens: navy #0a1628, gold #C5A76F, brass #B8893B, cream #F4EFE4, cream-light #FAF7F1, camacho-blue #266889
Fonts: Playfair Display (headings), Montserrat (UI), Cormorant Garamond (ledes/quotes)

---

## HOUSE RULES (NON-NEGOTIABLE)

- "camacho" always in `<span class="camacho">camacho</span>` — bold, #266889, lowercase
- NEVER render "Misty" or "Misty Klein" in any HTML (grep before committing)
- NO em dashes (U+2014) — use commas, colons, or semicolons
- Callout attributions ONLY to "Anja Kuechenmeister, VP Business Development"
- US state abbreviations only (GA, NC — never Georgia, North Carolina)
- Remove "Created by DreamCaster Productions" from any footer
- Anja quote attribution format: `&middot; Anja Kuechenmeister, VP Business Development`

---

## SECTION STATUS (as of 2026-06-04 session)

| Section | Title | HTML Status | Notes |
|---|---|---|---|
| A | Role Overview & Orientation | LIVE — needs v3 rebuild | Currently 21.7MB with embedded video; user says it has a Drive link issue |
| B | Industry Terminology | LIVE — v3 REBUILT 2026-06-04 | Full content, 15 flashcards, Drive iframes |
| C | Sales & Marketing Concepts | LIVE — v3 REBUILT 2026-06-04 | 16 flashcards, Misty attribution stripped |
| D | Psychology of Client Conversation | LIVE — v3 REBUILT 2026-06-04 | 15 flashcards |
| E | Information Gathering & Discovery | LIVE — v3 REBUILT 2026-06-04 | 15 flashcards, Anja attribution fixed |
| F | The Procurement Documents (RFP vs RFQ) | LIVE — v3 REBUILT 2026-06-04 | 15 flashcards |
| G | Proposal Writing Mastery | LIVE — already v3, complete | Do not touch |
| H | Fee Calculation & Pricing | LIVE — v3 REBUILT 2026-06-04 | 12 flashcards, replaces Drive-iframe partial |
| I | Code, Compliance & Health Department | LIVE — v3 REBUILT 2026-06-04 | Built from PDF/PNG content (Drive doc was K duplicate), 12 flashcards |
| J | Meeting Evaluation & SWOT | LIVE — v3 REBUILT 2026-06-04 | 12 flashcards |
| K | File Naming, Organization & Systems | LIVE — v3 BUILT 2026-06-04 | Was missing; built fresh from Drive content doc |
| L | Master Glossary | LIVE — complete, do not touch | Reference template for v3 style |
| M | Reference Section | LIVE — complete, do not touch | |
| N | Calculation Tools | LIVE — complete, do not touch | |

---

## WHAT STILL NEEDS TO BE DONE

### Priority 1: Section A rebuild
- Current camacho_Section_A.html is 21.7MB with embedded video (old format)
- User reports it has a Drive link issue and does not have full section content
- Drive content doc ID: `10_a48yZ2UZQgm3oWHiAJ_91eT-acFQcxWyrr4QuvcYM`
- Drive video (NEW — use this one): `1dJn-myiseTrndvxDNrQOb__Tu1hr5QV1`
- Drive audio: `1rkQs2nJenYCPxS-IOpbg3N1I9ylmMWya`
- Infographic: `1NL1O4WbChoJomYa_C4BtXlAgFE3zRmn_`
- Mindmap: `1Z5cszL7llfH2492WKtRcZOGweCr4J-fD`
- Build in v3 format with Drive iframes (NOT embedded video) — this will drop file from 21.7MB to ~100KB

### Priority 2: Update index.html
- All sections A-K are now live in v3 format
- Update progress stats and section descriptions to reflect current state
- The index.html at repo root is the homepage/nav page

### Priority 3: "O — Goals and Tracking" (clarify with user)
- User mentioned this as "complete" but it doesn't exist in the A-N training manual
- May be from a different project (DreamCaster OS) — need clarification

---

## KEY DRIVE IDs (AI - Master build all Sections folder)

| Section | Content Doc | Video | Audio | Infographic | Mindmap |
|---|---|---|---|---|---|
| A | 10_a48yZ2UZQgm3oWHiAJ_91eT-acFQcxWyrr4QuvcYM | 1dJn-myiseTrndvxDNrQOb__Tu1hr5QV1 | 1rkQs2nJenYCPxS-IOpbg3N1I9ylmMWya | 1NL1O4WbChoJomYa_C4BtXlAgFE3zRmn_ | 1Z5cszL7llfH2492WKtRcZOGweCr4J-fD |
| B | 1aTIHdwi5xcoN-QrC0bxhFE8dfTXoN5wkBRmWAhfvUqU | 1FA6Ev-Hn9bAZjZKJXtswC9XGcCT9GDPH | 1emoUp0CTSfKiQ4wpmFvV5S0q7JXVgZER | 18CRV5C5hWpv5q0cPUlOrd-o9hee1ABWC | 1J4yFCCzlrDVTMdd5lW64KEeS1tQfKoWm |
| C | 1r4kgmBQVOwlFk-1myJU9wn-d2Oj4pKUBu_8TBxBaERk | 1PhNddoQOP34RkMnMwbKNIt1I-KufRrrt | 1Y_K-HLUlOh0S7gCT_u32doDGSp8OB_Bn | 1rc_dpI_-ZluBTvwUizfkljb6H1pTepSq | 14piiFnqFNSAHauWcUes2o9_njLGbqY4w |
| D | 1Fy2zZ9CEHkziem-FH-1IjpyuHjHSy9e8qSHp2ZleHiA | 1sCTEr7eOhrswNOJQ7QJTrBi3Fz1gfQri | 1kvnNyhrf3visjSRA6VQwVGNdyZ1jfC3k | 147vmzb3ZgmxLuECQskL-5QssKqoYIPr0 | 15vaS-vadyv_48ATZUpvL_SZBuqilpzCR |
| E | 1C2gI7V15LcdOw3zI48-txnYy3fj3nlrLNpZo4z0xVOQ | 15Las1B6kKeLwvYByh0UdMmehPSgfoNJi | 1EmzY3qHUHYOCehHTYRJn9sreLuIfP_Bx | (none separate) | 1UeYaypbSRIeQBvL4E9NfvXRsoMLTt8jO |
| F | 1ylgMfyMw_qgcKOJ7ArFXGNShvJPTZNc-yiBp1ScraIA | 1ypBixgBCbSSQqfHSbYY5ftZifTSusxoY | 145JJa4B765o_ora0qkV5nhzayx2G1iIJ | 1FVUZeIK-b_gi91CA4Osp93DGNgqjy_He | 1ujUO_L5gfMxkRdmdcSjIdxsEw1i2gwH- |
| H | 1whvaksnJfKYXdn3vWwfVoGB02_zVyFQIMZsGsbJunMQ | 1LAWmX9z0_jM-B8YC6Wet-Ip-EZ3tevlT | 1egFSx4u3hIv7so9O2Q0O7eJv3WURKY_e | 1l9QJaLMGtBPjycZpQo8TbC4rJuZtEXeD | 16d79pt1XI5lbkzB1hvrUzKu3XgDQfYCW |
| I | (Drive doc is K duplicate — built from PDF/PNG) | 1wbzBfRkDBxwm8rbVM_mdHuMVJIxmnLkH | 18IV0iI0MJ2JnZkCJacA8okWK5l2ESYin | 1eBRiJ_rv9-NsGrjK61CDIHEZOyN5vuDT | 1QFo5pQbi8Lr0zGsAJNUKU4t3KvrGrTyG |
| J | 1QIbW9Tkf5yg8D3eXKYupcw_uvd4BGU2IW4TbBOBWQ-8 | 13xzA0T53kIOJmDw66CMD0T_eRWId1-jf | 19IHal09v8WUM3xFjMr1nt3umcONstolF | 1wvqK4QYE1otxBv-swS8NpeBsyGlSLr_6 | 1H_cSRb5-LmxmCGFXDxEnr5wzZFyjJWmQ |
| K | 1x7XVvXP7GmLmxN7yzJawU1T4RUdieD-LGEU01BoiGN0 | 11GvHyfnHmdGyQ1qF-92EuedhJREB2z2t | 1emRWx0PW2nRT_V2B4wyIEutKcFry-gep | 1o2rhR6fF4rSwYE8-w45hgH1XJBWgb4Ps | 1ylFhjeSJnZa41_rOi0c_AwtkO8lzBAOJ |

---

## OUTPUT OWNER
Google account: dream.caster.productions@gmail.com
