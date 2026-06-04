# CAMACHO TRAINING MANUAL — COMPLETE PROJECT STATE
## Saved: 2026-06-03 | Upload this file to Google Drive to replace the old SESSION_HANDOFF

---

## WHAT THIS PROJECT IS
A plug-and-play pipeline for the camacho USA (commercial foodservice + laundry design firm, founded 1962)
sales/proposal training manual. Each section builds into TWO deliverables:
1. Self-contained interactive HTML (embedded video + podcast + quiz + flashcards + nav)
2. Print-ready PDF

AI is used ONLY to draft prose from raw notes. The engine and validator are deterministic code.

---

## THE WEBSITE — LIVE ON NETLIFY

| Item | Value |
|---|---|
| Netlify project | willowy-horse-ed9122 |
| Live URL | https://willowy-horse-ed9122.netlify.app |
| Netlify dashboard | https://app.netlify.com/projects/willowy-horse-ed9122/overview |
| GitHub repo | https://github.com/DreamCasterProductions/camacho-training-manual |
| Deploy method | GitHub push auto-deploys to Netlify |
| Password protection | NONE — site is fully public |
| Supabase (unused) | https://kemcjqotanffydilzzwj.supabase.co |
| Supabase key | sb_publishable_UQWk0ZXleWbgTCNZzNniJQ_jC3taCKi |

NOTE: Supabase was set up for password protection but was NEVER wired in. Site is public.
Supabase credentials saved here in case needed later, but not currently active.

---

## LOCAL PROJECT FILES

Git repo root: C:\Users\Misty\.claude\camacho-manual-engine\camacho-manual-engine\
Claude project root: C:\Users\Misty\.claude\camacho-manual-engine\
CLAUDE.md (auto-loads every session): C:\Users\Misty\.claude\camacho-manual-engine\CLAUDE.md
Session handoff: C:\Users\Misty\.claude\camacho-manual-engine\camacho_SESSION_HANDOFF.md

### Files in GitHub repo (deployed to Netlify):
- index.html — branded nav page, all 14 sections, 13 are live links
- netlify.toml — static deploy config
- .gitignore — excludes raw asset folders
- camacho_Section_A.html — LIVE (video fixed: -map 0:v -map 0:a, CRF 28, faststart)
- camacho_Section_B.html — LIVE
- camacho_Section_C.html — LIVE
- camacho_Section_D.html — LIVE
- camacho_Section_E.html — LIVE
- camacho_Section_F.html — LIVE
- camacho_Section_G.html — LIVE
- camacho_Section_H.html — LIVE (Drive iframes for video/audio — needs embedding)
- camacho_Section_I.html — LIVE (30.8 MB, full embedded media)
- camacho_Section_J.html — LIVE
- camacho_Section_L_Master_Glossary.html — LIVE (alpha-nav anchors fixed 2026-06-04)
- camacho_Section_M_Reference.html — LIVE
- camacho_Section_N.html — LIVE

### Asset folders (local only, NOT in git):
C:\Users\Misty\.claude\camacho-manual-engine\camacho-manual-engine\
  Section A - assets\
  Section B - assets\
  Sections C - assets\
  Sections D - assets\
  Sections G - Assets\
  Sections H - Assets\
  Sections I - assets\
  Sections J - assets\
  Section K - Assets\
  Section L - Assets\
  Section M - Assets\
  Section N - Assets\
  Fee charts\

### Engine files:
C:\Users\Misty\.claude\camacho-manual-engine\engine\
  section_g.html — frozen template (CSS head, first 1181 lines)
  build_web.py, build_chromium.py — builders
  render_check.py, render_full.py — screenshot validators
  media\a\video.mp4 — Section A video (local copy)

---

## SECTION STATUS

| Section | Title | HTML Status | In Repo | Notes |
|---|---|---|---|---|
| A | Role Overview & Orientation | LIVE | YES | Video fixed (audio restored 2026-06-04). camacho_Section_A.html |
| B | Industry Terminology | LIVE | YES | camacho_Section_B.html |
| C | Sales & Marketing | LIVE | YES | camacho_Section_C.html |
| D | Client Psychology | LIVE | YES | camacho_Section_D.html |
| E | Discovery | LIVE | YES | camacho_Section_E.html |
| F | Procurement Documents | LIVE | YES | camacho_Section_F.html |
| G | Proposal Writing Mastery | LIVE | YES | camacho_Section_G.html |
| H | Fee Calculation | LIVE (partial) | YES | camacho_Section_H.html — video/audio use Drive iframes, needs embedding |
| I | Code & Compliance | LIVE | YES | camacho_Section_I.html (30.8 MB, full embedded media) |
| J | Meeting Evaluation & SWOT | LIVE | YES | camacho_Section_J.html |
| K | File Naming & Digital Vault | NOT BUILT | NO | Local HTML is duplicate of I — needs fresh rebuild from assets |
| L | Master Glossary | LIVE | YES | camacho_Section_L_Master_Glossary.html — alpha-nav fixed 2026-06-04 |
| M | Reference Section | LIVE | YES | camacho_Section_M_Reference.html |
| N | Calculation Tools | LIVE | YES | camacho_Section_N.html |

### Sections G–K were built in a cloud code-execution environment (/mnt/user-data/outputs/)
which may reset between sessions. To get them on Netlify, they must be rebuilt using the
build_web_X.py builders and the assets in the local folders above.

---

## KEY GOOGLE DRIVE IDs

| Item | Drive ID |
|---|---|
| Project parent folder | 1JHN7-hSe5l02i_nGWwCjWpGLvZTzgS9F |
| Handoff/spec docs folder | 1vFrmzQYFJbdW47E7x01atdtS7ZAVDNTA |
| SESSION_HANDOFF.md | 14DjB9Zig8zwgFBRzMCt8TrkxKwn7XF1UtonsHnEdKOU |
| camacho_BUILD_RULES.md | 1-VLQe-aVs2SP63g4iImTlnPM-JiOX3nYwAQ_5KOfv1g |
| ENGINE_SPEC.md | 1q1Ic6l2YHS0PgGArt0M6RRxbOzsJ1L9Si3GJKr5vGvk |
| Master source (section list) | 12VnnrIahem83dryBgmQ7kPZzRmqadakS |
| Meeting/Training Notes - Anja 2026 | 1Ztkp27HsWPQDlQ1fmjtHSMnaVZ5R2Uub |
| Final Assembly folder | 1MfJep8XGmjFoTASorrZNNiEd4fhom3z5 |

### Section A assets (folder 1YfFanv1vrgXODR6piyTQM6dUVbClnrpP)
- content doc: 10_a48yZ2UZQgm3oWHiAJ_91eT-acFQcxWyrr4QuvcYM
- slides folder "The_Camacho_Standard": 1GYZkC0JTkMFpXCzrjzz_OqhdOjcKJ96J
- infographic: 1NL1O4WbChoJomYa_C4BtXlAgFE3zRmn_
- mindmap: 1Z5cszL7llfH2492WKtRcZOGweCr4J-fD
- OLD silent video (DROP): 1FXTHA4zL7Vy59p47mb1orSmD4i8m6iek
- NEW video "Anatomy of a Won Deal" (USE THIS): 1dJn-myiseTrndvxDNrQOb__Tu1hr5QV1
- podcast audio (KEEP EMBEDDED): 1rkQs2nJenYCPxS-IOpbg3N1I9ylmMWya
- SLIDE_MAP: {2:'a1',3:'a1',4:'a2',5:'a2',6:'a3',7:'a3',8:'a4',9:'a4',10:'a7',11:'a4',12:'a8',13:'a8',14:'a8',15:'a8'}

### Section B assets (folder 1DMDsbY_wj4sMkuGkiZv2JESGWEoxATBq)
- slide deck: 1WmllllVtmG7Iozm8dGHbK0R0ADjz6rUfs7JwEeUQBhc
- video: 1mB04RGbodwrzsh2XGe-0Wc-czwS7Czl8
- audio: 1NzwDb4KhfsYgXUcbrNlKBP2F7eBAGh27
- infographic: 1BL4v9xhr0Gh8_x3nD9yZjv1RSKoh4r_U
- mindmap: 1daVyAkE-_6Jqdrj3yYNiP88JyHsgBh-b

### Section C assets (folder 1xkPXnM6HQ8PrvmlK8LStF2_69NL5lI6u)
- slide deck "The_Authority_Blueprint": 1KLj2wjTMxjYgP7xuS7wYOKZYG2AMleqzyEGbL-mFQUg
- video: 1mXXAF3PHhzHqaeF0jmDV2RaRQFLLvxFm
- audio: 1GssEwVvlbnCjYKH3tH5HmftrjT9ZqB-5
- guide PDF: 1miYipgjYy7fpPX9SmQ1l-Xp4LBHSvXr4

### Section H assets (folder 1HlKeWWAuEoeeJlrgejaTMCCX62gMhmsq)
- slides: 1Qk4q7qkJ4fdZUcGDkAPxNJjKIFdn3fB7
- methodology: 1eFIv80mJxnCwkewaYEDsO9esHIt1bLYE
- mindmap: 1XRaFbXLlJ0oc5EM2A0tWHFCJMC7mArGQ
- video: 1gSd6BKz9TCVAN_1jANGPsil6w76k_oqP
- audio: 1t1gh8VXFreR6_TG__0ZP1hRG0Ewkwtwn

### Section I assets (folder 1Mul2PZJKUIe_xGBzKqGTg3nxy9LbzY1l)
- slides: 1XkXimmEmRBpK_uq9fiVdpAP5mTA_fxC4
- infographic: 1KynPGOdJ6k4_uPnXnafaLoVV879mfdqw
- mindmap: 1IUgFtOwDpXRIMgEqa6cEJPpHY8YyUVEh
- video: 1F8QN6iyw1AIdSAqPqeYRjV5uJri_u-Bd
- audio: 1wp3KnkDpbOGVO4u0wXfjz6Ks7DfRq-Sk

### Section J assets (folder 1sbYgORGSg3ujoyUggphL5YIdeXFsFpid)
- slides: 1olXuuP0qtOIfr6cUelWReSGwvzz-jg1_
- infographic: 15G2MJ_1wYYg58vKpzoNWYs8KCosNjz3u
- mindmap: 1KqTprDW3PDqQR0JYSxgV_dHSbDydPE8H
- video: 1GpWkX2sF2YsCWGZkTLtN4HjKYaj26xU5
- audio: 1NNBIBzad1pne3iS4Bpg7t5TqS8TTlzE8
- content doc: 1Vys2uTISGyrz5EviSRQOjxxMRXqWDTY3d6BZJyeZKQk

### Section K assets (folder 1IrU7nuyGA0DYhkHwJO5t3_WB75ddTIu-)
- slides: 1wgyT2POYCgEvFd-TMp2OyGiENL9659iC
- infographic: 1jV7nIO4ZgJ_ma34mEAtDblTX_z07QspG
- mindmap: 17tRzs8VoxJcHw9MOOXUix7hKq6uP_pRe
- video: 1sRe7t0jKDISUr-AW_xQk-CQAKQQOvCMB
- audio: 1LAKQS0yDXEs_Dg8qiTFAPn3PsH-gydBh

---

## WORK QUEUE (priority order)

### IMMEDIATE (next session)
1. ~~Connect Netlify to GitHub~~ — DONE. Site: https://willowy-horse-ed9122.netlify.app
2. ~~Add sections B-J, N to repo~~ — DONE 2026-06-04 (13 of 14 live)
3. ~~Fix Section A video~~ — DONE 2026-06-04 (audio restored with -map 0:v -map 0:a)
4. ~~Fix Section L alpha-nav~~ — DONE 2026-06-04

### REMAINING
5. Rebuild Section K HTML from local assets (local file is duplicate of I — unusable)
6. Embed Section H video/audio locally (currently uses Drive iframes: 1gSd6BKz9TCVAN_1jANGPsil6w76k_oqP + 1t1gh8VXFreR6_TG__0ZP1hRG0Ewkwtwn)
7. Apply sidebar padding fix to all sections (validated CSS in CLAUDE.md)
8. Upgrade B, C, D, E, F, G, J to v3 format (add embedded media, quiz, flashcards) if desired
9. Final Assembly — merge all sections to master HTML

### AFTER ALL SECTIONS BUILT
10. Final Assembly — merge all sections to master HTML
11. Future: "Ask this section" conversational tutor (owned, replaces NotebookLM interactive)

---

## HOUSE STYLE — NON-NEGOTIABLE (validate every build)
- "camacho" always lowercase, bold, blue #266889, in <span class="camacho">
- NEVER "Misty" or "Misty Klein" in rendered content
- NO em dashes (U+2014) anywhere
- Callout attributions ONLY to "Anja Kuechenmeister, VP Business Development"
- US state abbreviations only (GA, NC, not Georgia, North Carolina)
- Sidebar: padding on container, not inner elements (see sidebar rule in CLAUDE.md)
- Tone: Forbes-style luxury consulting, no emotional fluff

## BRAND TOKENS
- Navy #0a1628, Gold/Brass #C5A76F, Blue #266889, Cream #FAF7F1, Rule #D6CCB6
- Fonts: Playfair Display (headings), Montserrat (UI), Cormorant Garamond (ledes/captions)
- Callout icons: expert ❝ / rule ▦ / best ✓ / files ☰ / warn ⚠

---

## OUTPUT OWNER
Google account: dream.caster.productions@gmail.com
User preference: Always ask clarification — never guess. Say "I don't know" if unsure. Keep responses concise.
