# Gumma Universe — Book 1 Chapter Outline Standard
**Version:** 0.1  
**Status:** Locked before Chapter Outlines  
**Last Reviewed:** 2026-08-02  
**Depends on:** Book Blueprint + Production Manual + Series Bible  
**Authority:** Production schema only. Does not override Blueprint, Manual, Bible, or Canon.

---

## Purpose

Define the mandatory structure every chapter outline must follow.

This document is **not** Chapter 1.  
It is **not** prose.  
It is **not** brainstorming.

It is the reusable engineering schema for Chapters 1–30 + Coda.

When an outline is complete, a drafter should be able to write the chapter without inventing major decisions. Continuity failures should be almost impossible if every field is filled honestly.

**Hierarchy:** Blueprint row for the chapter → this outline → scene outlines (Manual §2.3) → draft prose.

**Rule:** No chapter draft begins until that chapter’s outline exists, is complete, and passes §11 Success Criteria + §9 Canon Validation.

---

## Assumptions

1. One outline file per chapter: `02_CHAPTER_OUTLINES/ChXX.md` (Coda = `ChCoda.md`).
2. Blank fields are failures. “N/A” is allowed only where marked optional.
3. Reveal Points and promises must match Blueprint Part V / VI / VII unless a formal Blueprint amendment exists.
4. Emotional value and hope score must match Blueprint Part IX unless amended.
5. This standard applies to all future books with book-number substitution unless a later Locked standard replaces it.

---

# 1. HOW TO USE THIS STANDARD

1. Copy **Appendix A — Blank Chapter Outline Template** into `02_CHAPTER_OUTLINES/ChXX.md`.
2. Fill every required field from the Blueprint chapter row first (POV, location, conflict, emotion, RP, promises).
3. Expand into scenes using the scene block schema (mirrors Production Manual §2.3 with chapter-level extras).
4. Run Continuity Checklist + Canon Validation before marking `OUTLINE STATUS: READY FOR SCENE OUTLINES`.
5. After prose is approved, do not alter the outline silently — log amendments in `05_REVISION_LOG.md`.

---

# 2. FIELD DEFINITIONS

---

## 2.1 Metadata (Required)

| Field | Definition | Source of truth |
|-------|------------|-----------------|
| Chapter number | `1`–`30` or `Coda` | Blueprint Part V |
| Working title | Short functional title (not published) | Invented here; keep dull and accurate |
| Act | I / II / III / Coda | Blueprint Part IV |
| POV | Single primary POV character | Blueprint; Manual §1.1 |
| Story date | Calendar date | Blueprint Part XI |
| Time of day span | e.g. morning→dusk | Outline decision; must fit timeline |
| Weather | Concrete, continuous with prior day | Blueprint Part XI + prior outline |
| Location(s) | Ordered list of L-IDs / names | Blueprint Part X |
| Timeline references | Prior chapter end state; clocks (wedding, police, AGM) | Blueprint + Bible |
| Estimated word count | Target for draft | Manual default 2,200–3,200 unless noted |
| Reveal Point spend | Integer; must match Blueprint lock | Blueprint Part V revised RP |
| Cumulative RP after chapter | Running total | Series Bible reveal ledger |
| Emotional value start | Entering dominant residue | Prior chapter Part IX residue |
| Emotional value end | Declared dominant emotion of this chapter | Blueprint Part IX |
| Hope score | 1–5 | Blueprint Part IX |
| Series threads touched | T-IDs | Blueprint / Bible |
| Promises opened / advanced / closed | P-IDs | Blueprint Part VII |
| Canon references | Foundations docs relevant as **writer constraints only** (not for prose) | e.g. Trust, Legitimacy |
| Outline status | DRAFT / READY FOR SCENE OUTLINES / LOCKED FOR PROSE | Production state |
| Drafter / reviewer | Names or roles | Ops |

---

## 2.2 Chapter Purpose (Required)

Must answer in complete sentences:

1. **Why this chapter exists** (one paragraph, human-stakes first).
2. **Removal test:** What breaks in the novel if this chapter is deleted?
3. **Promise job:** Which P-ID(s) are opened, advanced, or closed?
4. **Emotional job:** What single dominant impression must remain?
5. **Institutional job:** RP spend and why it is allowed (or explicit “0 — civilian only”).

If the honest answer to (1) is “to show the Gumma,” the chapter fails and must be redesigned at Blueprint level.

---

## 2.3 Opening State (Required)

| Subfield | Requirement |
|----------|-------------|
| POV entering emotion | Matches prior residue |
| POV entering knowledge | Matches Bible knowledge matrix |
| Other major characters onstage later this chapter — entering emotion | Brief |
| Unresolved pressure entering | Clocks, fights, messages, travel fatigue |
| Reader assumptions currently true | What careful readers believe now |
| Reader assumptions we will not correct this chapter | Intentional misunderstandings |

---

## 2.4 Scene List (Required — min 2, max 5)

Each scene is a block with:

| Field | Requirement |
|-------|-------------|
| Scene ID | `B01-ChXX-S0Y` |
| Location | Specific |
| Time of day | Within chapter span |
| Characters onstage | Named |
| Offstage pressure | Calls, rumors, clocks |
| Goal (POV want) | Concrete |
| Conflict / obstacle | Concrete |
| Turning point | What changes |
| Exit image | Sensory, non-expository |
| Emotional delta | From → to inside scene |
| Reveal usage | 0 / portion of chapter RP with beat description |
| Continuity dependencies | What must already be true |
| Continuity outputs | What becomes true after |
| Word budget | Scene share of chapter estimate |
| Fail if | Lore-only / head-hop / budget break |

Sum of scene word budgets ≈ chapter estimated word count (±10%).

---

## 2.5 Relationship Tracker (Required)

For every relationship that appears or is materially affected:

| Pair | Temp before (1–5 or label) | Temp after | What changed (one line) |
|------|----------------------------|------------|-------------------------|
| … | | | |

Use Blueprint Part III labels where possible (ice / thaw / warm / hostile polite / etc.).

---

## 2.6 Mystery Tracker (Required)

| Category | Entries |
|----------|---------|
| Questions strengthened | List |
| Questions answered | List (rare in Book 1) |
| Questions intentionally ignored | List |
| Incorrect interpretations encouraged | Reader theories we allow |
| Correct interpretation (writer only) | Canon truth — **never for prose** |
| RP beats this chapter | Map to Reveal Map IDs (R1–R8) if any |

---

## 2.7 Emotional Rhythm (Required)

| Beat | Emotion | Notes |
|------|---------|-------|
| Beginning | | Opening pages |
| Middle | | Around turn |
| Ending | | Must equal declared dominant end emotion |
| Recovery beat | Yes/No + where | Breath after spike |
| Reader breathing space | Where pressure eases without resolving plot | |

---

## 2.8 Continuity Checklist (Required — all rows answered)

Mark Pass / Fail / N/A for:

- Weather continuity with prior chapter  
- Travel feasibility  
- Wardrobe / dust / mud / sweat state  
- Props (fence wire, documents, jasmine, phone, guest mat, etc.)  
- Phone battery / who has whose number / WhatsApp groups  
- Vehicles / buses  
- Food / tea / meals mentioned  
- Time elapsed inside chapter  
- Village activity appropriate to date (wedding prep, jatre, monsoon)  
- City activity if any  
- Outstanding injuries (Prasad bruise, Ramesh thumb, knee, etc.)  
- Objects carried across scenes  
- Conversation memory (who heard what; no telepathy)  
- Sleep / fatigue  
- Money exchanged or refused  

---

## 2.9 Canon Validation (Required — all must Pass)

| Check | Pass/Fail |
|-------|-----------|
| Reveal spend ≤ Blueprint chapter RP | |
| Cumulative RP ≤ novel plan after this chapter | |
| Knowledge matrix respected for POV | |
| Character arc position matches Blueprint Part II/IX | |
| Relationship map inches, not jumps | |
| Timeline / Part XI date honored | |
| Production Manual voice/scene/chapter rules honored in plan | |
| Series Bible threads not wrongly closed | |
| No nuclear vocabulary planned | |
| Invisible layer not protagonist | |
| Human conflict dominates purpose | |

Any Fail → outline not READY.

---

## 2.10 Drafting Constraints (Required)

Explicit lists:

- **Prose must avoid:** …  
- **Forbidden exposition:** …  
- **Forbidden lore:** …  
- **Forbidden vocabulary:** (always include Manual Appendix B set; add chapter-specific)  
- **Invisible layer limits:** max RP; what may be *shown* vs *inferred*  
- **POV restrictions:** no head-hop; no narrator smirk  
- **Dialogue restrictions:** no teacher lines; no oracle vagueness  
- **Allowed ambiguity:** what must remain unclear  

---

## 2.11 Success Criteria (Required gate)

Outline (and later chapter) passes only if all are true:

| # | Criterion | Y/N |
|---|-----------|-----|
| 1 | Human conflict dominates | |
| 2 | Mystery remains background (except Blueprint Reveal chapters, still human-led) | |
| 3 | Characters move emotionally | |
| 4 | Every scene earns existence (removal test per scene) | |
| 5 | No lore dump planned | |
| 6 | Reveal budget preserved | |
| 7 | Ending image memorable and concrete | |
| 8 | Reader want-next earned without thriller bait | |
| 9 | Opening human problem by word 150 planned | |
| 10 | Matches Blueprint row | |

---

## 2.12 Post-Outline Hooks (Required)

| Field | Content |
|-------|---------|
| Residue into next chapter | Emotion + factual state |
| Open clocks | Wedding / police / AGM / absence / departure |
| Bible updates required after prose | Checklist |

---

# 3. QUALITY BAR FOR OUTLINES

An outline fails if it:

- Reads like brainstorming (“maybe Shankarappa shows up”)
- Uses hedges where Blueprint already locked a beat
- Assigns RP not in Blueprint
- Invents travel that breaks Part XI
- Explains canon in the Purpose section as if it were plot
- Leaves Mystery Tracker empty on a Reveal chapter
- Leaves Mystery Tracker overfull on a civilian chapter (forcing lore)

**Tone of outlines:** clinical, specific, boring in the best way.

---

# 4. FILE NAMING & STATUS

```text
11_STORY_SEEDS/BOOK_01/02_CHAPTER_OUTLINES/
  Ch01.md
  Ch02.md
  ...
  Ch30.md
  ChCoda.md
```

Status lifecycle:

`DRAFT` → `READY FOR SCENE OUTLINES` → `LOCKED FOR PROSE` → `SUPERSEDED` (only with revision log)

---

# APPENDIX A — BLANK CHAPTER OUTLINE TEMPLATE

Copy everything below the line into each `ChXX.md`.

---

```markdown
# Book 1 — Chapter Outline: Ch__
**Working title:**  
**Status:** DRAFT  
**Act:**  
**Outline version:** 0.1  
**Last updated:** YYYY-MM-DD  
**Drafter:**  
**Reviewer:**  

---

## 1. Metadata

| Field | Value |
|-------|-------|
| Chapter number | |
| Working title | |
| Act | |
| POV | |
| Story date | |
| Time of day span | |
| Weather | |
| Location(s) | |
| Timeline references | |
| Estimated word count | |
| Reveal Point spend | |
| Cumulative RP after this chapter | |
| Emotional value — start (entering residue) | |
| Emotional value — end (dominant) | |
| Hope score (1–5) | |
| Series threads touched | |
| Promises opened | |
| Promises advanced | |
| Promises closed | |
| Canon references (writer-only) | |
| Blueprint Part V row confirmed? | Y/N |

---

## 2. Chapter Purpose

**Why this chapter exists:**


**Removal test (what breaks if deleted):**


**Promise job:**


**Emotional job:**


**Institutional / RP job:**


---

## 3. Opening State

**POV entering emotion:**  
**POV entering knowledge:**  

**Other characters — entering emotions:**
- 

**Unresolved pressure entering:**


**Reader assumptions currently true:**


**Reader assumptions we will not correct this chapter:**


---

## 4. Scene List

### Scene B01-Ch__-S01

| Field | Value |
|-------|-------|
| Location | |
| Time of day | |
| Characters onstage | |
| Offstage pressure | |
| Goal (POV want) | |
| Conflict / obstacle | |
| Turning point | |
| Exit image | |
| Emotional delta | → |
| Reveal usage | 0 / beat: |
| Continuity dependencies | |
| Continuity outputs | |
| Word budget | |
| Fail if | |

### Scene B01-Ch__-S02

| Field | Value |
|-------|-------|
| Location | |
| Time of day | |
| Characters onstage | |
| Offstage pressure | |
| Goal (POV want) | |
| Conflict / obstacle | |
| Turning point | |
| Exit image | |
| Emotional delta | → |
| Reveal usage | 0 / beat: |
| Continuity dependencies | |
| Continuity outputs | |
| Word budget | |
| Fail if | |

### Scene B01-Ch__-S03 (optional)

| Field | Value |
|-------|-------|
| Location | |
| Time of day | |
| Characters onstage | |
| Offstage pressure | |
| Goal (POV want) | |
| Conflict / obstacle | |
| Turning point | |
| Exit image | |
| Emotional delta | → |
| Reveal usage | 0 / beat: |
| Continuity dependencies | |
| Continuity outputs | |
| Word budget | |
| Fail if | |

### Scene B01-Ch__-S04 (optional)

*(same fields)*

### Scene B01-Ch__-S05 (optional — max)

*(same fields)*

**Scene word budget sum:** ____ (must be ≈ chapter estimate)

---

## 5. Relationship Tracker

| Pair | Temp before | Temp after | What changed |
|------|-------------|------------|--------------|
| | | | |
| | | | |
| | | | |

---

## 6. Mystery Tracker

**Questions strengthened:**
- 

**Questions answered:**
- 

**Questions intentionally ignored:**
- 

**Incorrect interpretations encouraged:**
- 

**Correct interpretation (writer only — not for prose):**


**RP beats (Reveal Map IDs):**


---

## 7. Emotional Rhythm

| Beat | Emotion | Notes |
|------|---------|-------|
| Beginning | | |
| Middle | | |
| Ending (dominant) | | |
| Recovery beat | Y/N — | |
| Reader breathing space | | |

---

## 8. Continuity Checklist

| Item | State / note | Pass? |
|------|--------------|-------|
| Weather vs prior chapter | | |
| Travel feasibility | | |
| Wardrobe / body state | | |
| Props | | |
| Phone states | | |
| Vehicles | | |
| Food / tea / meals | | |
| Time elapsed in chapter | | |
| Village activity fit to date | | |
| City activity fit to date | | |
| Outstanding injuries | | |
| Objects carried | | |
| Conversation memory | | |
| Sleep / fatigue | | |
| Money / refusal of money | | |

---

## 9. Canon Validation

| Check | Pass/Fail |
|-------|-----------|
| Reveal spend matches Blueprint | |
| Cumulative RP safe | |
| Knowledge matrix respected | |
| Character arc position correct | |
| Relationship map inches only | |
| Timeline / Part XI honored | |
| Production Manual plan-compliant | |
| Series Bible threads safe | |
| No nuclear vocabulary planned | |
| Invisible layer not protagonist | |
| Human conflict dominates | |

---

## 10. Drafting Constraints

**Prose must avoid:**


**Forbidden exposition:**


**Forbidden lore:**


**Forbidden vocabulary (include Manual Appendix B):**
ancient order · chosen · destiny · for centuries · secret society · the Order · Holder · Verifier · Connector · Walker · Transmitter · Covenant · Article · Gumma · civilizational memory · mystical · supernatural · initiation · the mission ·
+ chapter-specific:


**Invisible layer limits:**


**POV restrictions:**


**Dialogue restrictions:**


**Allowed ambiguity:**


---

## 11. Success Criteria

| # | Criterion | Y/N |
|---|-----------|-----|
| 1 | Human conflict dominates | |
| 2 | Mystery remains background (unless Blueprint Reveal chapter, still human-led) | |
| 3 | Characters move emotionally | |
| 4 | Every scene earns existence | |
| 5 | No lore dump planned | |
| 6 | Reveal budget preserved | |
| 7 | Ending image memorable | |
| 8 | Reader wants next chapter | |
| 9 | Human problem by word 150 planned | |
| 10 | Matches Blueprint row | |

---

## 12. Post-Outline Hooks

**Residue into next chapter:**


**Open clocks:**


**Bible updates required after prose approval:**
- [ ] Reveal ledger
- [ ] Promise ledger
- [ ] Knowledge notes
- [ ] Relationship temps
- [ ] Location last-appearance

---

## Sign-off

OUTLINE STATUS: DRAFT / READY FOR SCENE OUTLINES / LOCKED FOR PROSE  

Signed: _______________ Date: _______________
```

---

# APPENDIX B — ONE-LINE COMPLETENESS AUDIT

Before status upgrade, answer yes to all:

1. Metadata matches Blueprint Part V + IX + XI?  
2. Purpose survives removal test without lore?  
3. ≥2 scenes, each with want/conflict/turn/exit image?  
4. RP exact?  
5. Continuity checklist all Pass/N/A?  
6. Canon validation all Pass?  
7. Drafting constraints filled (not blank)?  
8. Success criteria all Y?  
9. Residue into next chapter specified?  
10. No prose snuck into the outline?

---

# APPENDIX C — CONNECTIONS

- Blueprint: `11_STORY_SEEDS/BOOK_01/00_BLUEPRINT.md`  
- Production Manual: `11_STORY_SEEDS/BOOK_01/01_PRODUCTION_MANUAL.md`  
- Series Bible: `11_STORY_SEEDS/00_SERIES_BIBLE.md`  
- Chapter outline folder: `11_STORY_SEEDS/BOOK_01/02_CHAPTER_OUTLINES/`  
- Scene outlines: `11_STORY_SEEDS/BOOK_01/03_SCENE_OUTLINES/` (use Manual §2.3; chapter outline Scene List is the parent)

---

## Closing

Creative decisions live in the Blueprint.  
Disciplinary decisions live in the Production Manual.  
**Execution packets** live in chapter outlines built from this standard.

Do not generate chapter outlines in this file.  
Do not generate prose in this file.

When Chapter Outlines begin, they begin by copying Appendix A — nothing freer, nothing vaguer.
