# Gumma Universe — Book 1 Revision Log & Continuity Management Standard
**Version:** 0.1  
**Status:** Pre-Prose  
**Last Reviewed:** 2026-08-02  
**Depends on:** Series Bible + Production Manual + Blueprint + Chapter Outline Standard + Scene Outline Standard  
**Authority:** Production / revision-control only. Does not override Canon.

---

## Purpose

Design the complete revision-control system for Book 1.

This document governs **every change** made after the Blueprint is locked.

It is not prose.  
It is not story planning.  
It is the engineering process that prevents continuity drift across a ~90,000-word literary novel.

A competent editor should be able to reconstruct exactly why every structural decision changed.

**Living artifacts (populated during drafting):**

```text
11_STORY_SEEDS/BOOK_01/
  05_REVISION_LOG.md              ← append-only revision entries
  06_LEDGERS/
    CONTINUITY.md
    CHARACTER_STATE.md
    REVEAL.md
    PROMISE.md
    RELATIONSHIP.md
    TIMELINE.md
    LOCATION.md
    OBJECT.md
    KNOWLEDGE.md
```

Templates for those files are in **Part XV — Appendix**. Seed files may exist empty; they become authoritative once Chapter 1 prose begins.

---

# PART I — REVISION PHILOSOPHY

---

## 1.1 What May Change Freely (within gates)

After a chapter is drafted, the following may change **without** Blueprint amendment, provided Production Manual gates still pass and a Level 0–1 Revision Log entry is filed when non-trivial:

- Wording, rhythm, sensory specificity inside locked beat meaning  
- Micro-gestures that do not alter plot, knowledge, or RP  
- Dialogue wording inside Dialogue Constraints  
- Typographical and formatting fixes  

---

## 1.2 What Requires Blueprint Amendment (Level 4)

Any change to locked Blueprint structure, including:

- POV assignment per chapter  
- Story dates / wedding / jatre / travel spine  
- RP spend per chapter or novel total  
- Promise open/close intent  
- Cast membership / ages in-story  
- Act boundaries or chapter purpose  
- Ending / coda ambiguity rule  
- Reveal Map beats (R-IDs)  

**Process:** Draft Blueprint amendment → Creative Director approval → update Blueprint version note → Revision Log Level 4 → cascade updates to affected outlines/ledgers **before** revising prose.

---

## 1.3 What Requires Series Bible Amendment

- Character registry IDs, ages, recurring flags  
- Cumulative reader knowledge / character knowledge matrix  
- Thread status (T-IDs)  
- Location registry first/last appearance after prose  
- Cross-book hooks ranking changes  

Bible updates are **mandatory after every approved chapter** even when no Level 4 change occurs (routine sync). Routine sync = Level 1 documentation minimum (see Part II).

---

## 1.4 What Requires Canon Amendment

Any change that alters Foundations / Canon truth (institution, Covenant, Houses, hard locks, philosophy).

**Process:** Contradiction Log entry + Canon document revision under Canon status rules. **Creative Director + Canon authority required.** Level 5 only. Prose may not lead Canon.

---

## 1.5 What May Never Change Without Creative Director Approval

| Item | Notes |
|------|-------|
| Word “Gumma” on-page in Book 1 | Nuclear; forbidden |
| Novel RP ceiling (18) / plan (14) without formal amend | |
| Invisible layer as protagonist | |
| Supernatural / prophecy / chosen-one / gadgets | Hard locks |
| Emotional completion of Book 1 replaced by pure cliffhanger | |
| Skipping Production Manual five gates | |
| Silent edits to Blueprint / Bible / ledgers | Always log |

---

## 1.6 Hierarchy (Highest → Lowest)

```text
Canon
  ↓
Series Bible
  ↓
Blueprint
  ↓
Chapter Outline
  ↓
Scene Outline
  ↓
Draft
  ↓
Revision
```

**Conflict rule:** Lower layer loses. Revision never “fixes” continuity by quietly contradicting a higher layer; it either conforms downward or amends upward with approval.

---

# PART II — CHANGE CLASSIFICATION

| Level | Name | Examples | Approval | Documentation | Impact | Required updates |
|-------|------|----------|----------|---------------|--------|------------------|
| **0** | Typo / format | Spelling, markdown, whitespace | Drafter | Optional one-line in Revision Log if batch | None | None |
| **1** | Prose only | Sentence rewrite; sensory swap; dialogue rephrase within constraints | Drafter + Pass 4/5 re-check | Revision Log entry | Style/clarity | None structural; optional ledger if emotion wording clarified |
| **2** | Scene adjustment | Beat reorder; duration change; prop swap; exit image change **without** altering turn meaning | Reviewer | Revision Log + Scene Outline update | Local continuity | Scene outline; Continuity/Object ledgers if props/time |
| **3** | Chapter structural change | Scene add/remove; dominant emotion change; chapter purpose shift; POV-internal knowledge change | Reviewer + CD if arc-affecting | Revision Log + Chapter Outline update | Chapter + adjacent residues | Chapter outline; Character/Relationship/Knowledge/Promise/Reveal as touched; Bible sync |
| **4** | Blueprint amendment | See §1.2 | **Creative Director** | Revision Log Level 4 + Blueprint version bump | Multi-chapter / novel | All descendant outlines for affected chapters; all ledgers; Bible |
| **5** | Canon amendment | Foundations/Canon truth | **Creative Director + Canon process** | Revision Log Level 5 + Contradiction Log + Canon doc | Franchise | Canon; Bible; possibly Blueprint; freeze prose until cascade done |

**Stop-work:** Level 4–5 changes freeze drafting of dependent chapters until cascade complete.

---

# PART III — REVISION LOG FORMAT

**File:** `05_REVISION_LOG.md`  
**Mode:** Append-only. Never delete prior entries. Supersede with a new entry referencing the old ID.

### Entry template

```markdown
## REV-B01-XXXX
**Date:** YYYY-MM-DD  
**Editor:**  
**Level:** 0–5  
**Reason:**  

**Files changed:**
- 

**Story effect:**


**Continuity effect:**


**RP impact:** none / +N / −N / reallocate Ch__→Ch__ (detail)


**Promise impact:** none / P-IDs …


**Knowledge impact:** none / who knows what changed …


**Relationship impact:** none / pairs …


**Timeline impact:** none / dates …


**Outline/Bible/Blueprint/Canon updated?** Y/N + paths


**Approved by:**  
**Status:** PROPOSED / APPROVED / REJECTED / SUPERSEDED BY REV-B01-____
```

**ID scheme:** `REV-B01-0001` incrementing.

---

# PART IV — CONTINUITY LEDGER

**File:** `06_LEDGERS/CONTINUITY.md`

Running master checklist state **after each approved chapter**. Not prose.

Track at minimum:

| Domain | What to record per chapter end |
|--------|--------------------------------|
| Weather | Condition; continuity note |
| Dates | Story date(s) covered |
| Travel | Who moved where; mode; duration |
| Phones | Who has whose number; critical unread/sent |
| Injuries | Actor; type; healing state |
| Relationships | Pointer to Relationship Ledger |
| Knowledge | Pointer to Knowledge Ledger |
| Reveals | Pointer to Reveal Ledger |
| Locations | Used this chapter; objects left |
| Money | Exchanged / refused |
| Objects | Pointer to Object Ledger |
| Vehicles | In use / parked |
| Wardrobe | Notable state (mud, formal, travel clothes) |
| Ongoing jokes | Running bits still alive |
| Food / tea | Last significant meal beat if carrying |
| Fatigue / sleep | Who is exhausted / slept |
| Festival timeline | Status vs 10 May jatre |
| Wedding timeline | Status vs 18 Apr wedding |

**Automatic fail flags (must mark FAIL if true):**

- Travel exceeds possible hours for date  
- Injury forgotten  
- Object duplicated in two places  
- Weather contradicts prior day without transition  
- Festival/wedding date mismatch  

---

# PART V — CHARACTER STATE LEDGER

**File:** `06_LEDGERS/CHARACTER_STATE.md`

Update **after every approved chapter** for every major character (POV + essential supporting who appeared or changed offstage).

### Per-character row (after Ch__)

| Field | Content |
|-------|---------|
| Chapter | |
| Emotion | |
| Goal | |
| Fear | |
| Knowledge (delta) | |
| Lies believed | |
| Truth learned (delta) | |
| Relationships (deltas) | |
| Physical condition | |
| Objects carried | |
| Location at chapter end | |
| Next appearance (planned) | |

Characters minimally tracked: Meera, Ramesh, Ananya, Nav, Lakshmi, Saroja, Venki, Karthik Gowda, Shankarappa, Gayatri, Priya, Suresh, Farooq, Asha, Rohan, Prasad (while injury active).

---

# PART VI — REVEAL LEDGER

**File:** `06_LEDGERS/REVEAL.md`

| Field | Rule |
|-------|------|
| Novel RP plan | 14 |
| Novel RP ceiling | 18 |
| Cumulative spent | Running |
| Remaining to plan | 14 − spent |
| Remaining to ceiling | 18 − spent |

### Per RP event

| Ch | RP | Reveal Map ID | Beat summary | Incorrect theories encouraged | Correct (writer-only) | Future payoff | Bible synced? |
|----|-----|---------------|--------------|-------------------------------|-----------------------|---------------|---------------|

**Fail flag:** cumulative > 14 without Level 4 amendment; any nuclear word = stop-work.

---

# PART VII — PROMISE LEDGER

**File:** `06_LEDGERS/PROMISE.md`

Seed from Blueprint Part VII. Status values: `OPEN` · `ADVANCED` · `CLOSED` · `DEFERRED_B2` · `DEFERRED_SERIES` · `BACKGROUND` · **`ORPHAN_FAIL`**.

| P-ID | Type | Promise | Opened Ch | Last advanced Ch | Closed Ch | Status | Notes |
|------|------|---------|-----------|------------------|-----------|--------|-------|

**Automatic failure flags:**

- Promise in Blueprint as CLOSED but still OPEN at manuscript QA → `ORPHAN_FAIL`  
- Promise closed in prose without ledger update → revision required  
- New promise introduced in prose without P-ID → Level 3+ ; assign ID or cut  

---

# PART VIII — RELATIONSHIP LEDGER

**File:** `06_LEDGERS/RELATIONSHIP.md`

### Temperature scale (lock)

| Score | Label |
|-------|-------|
| 1 | Hostile / ice |
| 2 | Cold / hostile polite |
| 3 | Neutral / wary |
| 4 | Warm / cooperative |
| 5 | Close / trusting |

### Pair log (after each chapter that touches the pair)

| Pair | Ch | Temp before | Temp after | Note |
|------|-----|-------------|------------|------|

### Visual matrix (update at Act ends + manuscript QA)

Rows/columns: Meera, Ramesh, Ananya, Nav, Lakshmi, Venki, Shankarappa, Priya (add as needed). Cell = current temp score or `—`.

---

# PART IX — TIMELINE LEDGER

**File:** `06_LEDGERS/TIMELINE.md`

Master calendar seeded from Blueprint Part XI. After each chapter:

| Date | Weather | Travel | Chapters/Scenes | Time elapsed | Impossible travel? Y/N | Notes |
|------|---------|--------|-----------------|--------------|------------------------|-------|

**Automatic expose:** If any character appears in two locations the same day without logged travel window → `FAIL`.

---

# PART X — LOCATION LEDGER

**File:** `06_LEDGERS/LOCATION.md`

Seed from Blueprint Part X (L01–L17).

| Loc ID | Name | First Ch | Last Ch | Purpose | Objects left behind | Emotional association | Future reuse |
|--------|------|----------|---------|---------|---------------------|----------------------|--------------|

Update `Last Ch` and objects after each approved chapter using that location.

---

# PART XI — OBJECT LEDGER

**File:** `06_LEDGERS/OBJECT.md`

Mandatory tracked objects (extend as needed):

| Object ID | Object | First Ch | Current location / holder | State | Symbolic? | Last Ch seen | Notes |
|-----------|--------|----------|---------------------------|-------|-----------|--------------|-------|
| O01 | Fence wire | | | | Y | | |
| O02 | Guest mat | | | | Y | | |
| O03 | Meera’s phone | | | | N | | path photo later |
| O04 | Jasmine (bowl/stems) | | | | Y | | |
| O05 | Tea glasses | | | | N | | |
| O06 | Path photograph (digital) | | | | Y | | |
| O07 | ESOP / settlement papers | | | | Y | | |
| O08 | Priya’s notebook | | | | N | | |
| O09 | Farooq biscuit tin | | | | N | | |
| O10 | Traveler’s bag | | | | N | | |
| O11 | Henna cone | | | | N | | |
| O12 | Broken fence post | | | | Y | | |
| O13 | Wedding jasmine/garlands | | | | N | | |
| O14 | Resignation email (unsent/sent) | | | | Y | | |

**Fail flag:** same Object ID in two holders without transfer beat.

---

# PART XII — KNOWLEDGE LEDGER

**File:** `06_LEDGERS/KNOWLEDGE.md`

After every chapter, update knowledge state for:

Reader · Meera · Ramesh · Ananya · Nav · Lakshmi · Shankarappa · Priya · Suresh · Gayatri · Farooq · Rohan · Others as needed  

### Format

| Ch | Actor | Knows (additive bullets) | Suspects | Wrong belief | Hidden from them |
|----|-------|--------------------------|----------|--------------|------------------|

Must remain consistent with Blueprint Part VIII. Deviations require Level 3–4.

**Writer-only institutional truth** never enters Reader column as confirmed fact in Book 1.

---

# PART XIII — DRAFT QA CHECKLIST

**When:** Before chapter status = continuity-approved (after Passes 1–5).

| # | Check | Pass? |
|---|-------|-------|
| 1 | Timeline ledger updated; no impossible travel | |
| 2 | Dominant emotion matches outline/Blueprint | |
| 3 | RP spent logged; cumulative ≤ plan | |
| 4 | Promises opened/advanced/closed logged | |
| 5 | Relationships temps updated | |
| 6 | Knowledge ledger updated for all affected | |
| 7 | Continuity ledger domains checked | |
| 8 | Dialogue restrictions held | |
| 9 | Single POV per scene; chapter POV correct | |
| 10 | Word count within Manual limits | |
| 11 | Chapter purpose still true | |
| 12 | Each scene purpose still true | |
| 13 | Exit image present and concrete | |
| 14 | Opening human problem by ~word 150 | |
| 15 | Character state ledger rows updated | |
| 16 | Objects/locations ledgers updated | |
| 17 | Revision Log entry filed if any Level ≥1 change during revision | |
| 18 | Series Bible routine sync done | |

Any Fail → chapter not approved.

---

# PART XIV — BOOK QA CHECKLIST

**When:** Before Final Manuscript acceptance.

| # | Check | Pass? |
|---|-------|-------|
| 1 | All Blueprint promises CLOSED or intentionally DEFERRED with rank | |
| 2 | No `ORPHAN_FAIL` promises | |
| 3 | All Reveal Map R-IDs executed or formally cut via Level 4 | |
| 4 | Cumulative RP ≤ 14 (or amended plan); ≤ 18 absolute | |
| 5 | Nuclear vocabulary absent (full-text search) | |
| 6 | Relationship matrix complete at novel end | |
| 7 | All major arcs match Blueprint Part II truths learned | |
| 8 | Timeline continuous; travel possible throughout | |
| 9 | Weather seasonally coherent Mar–Jun 2026 spine | |
| 10 | Character ages consistent | |
| 11 | Hope curve audited vs Part IX | |
| 12 | Ending image + emotional completion present | |
| 13 | Coda ambiguity unresolved (not confirmed network) | |
| 14 | Knowledge ledger matches Blueprint final matrix | |
| 15 | Location first/last appearances sensible | |
| 16 | Object ledger no dual-location fails | |
| 17 | Revision Log reconstructible for all Level ≥2 changes | |
| 18 | Series Bible fully synced | |
| 19 | Book stands alone emotionally | |
| 20 | Creative Director sign-off | |

---

# PART XV — APPENDIX (BLANK TEMPLATES)

---

## A. Blank Revision Entry

```markdown
## REV-B01-XXXX
**Date:** YYYY-MM-DD  
**Editor:**  
**Level:**  
**Reason:**  

**Files changed:**
- 

**Story effect:**


**Continuity effect:**


**RP impact:**


**Promise impact:**


**Knowledge impact:**


**Relationship impact:**


**Timeline impact:**


**Higher-doc updates:**


**Approved by:**  
**Status:** PROPOSED / APPROVED / REJECTED / SUPERSEDED BY REV-B01-____
```

---

## B. Blank Character Ledger Section

```markdown
### Character: _______________

| Ch | Emotion | Goal | Fear | Knowledge Δ | Lies believed | Truth Δ | Rel Δ | Body | Objects | Location | Next |
|----|---------|------|------|-------------|---------------|---------|-------|------|---------|----------|------|
| | | | | | | | | | | | |
```

---

## C. Blank Reveal Ledger

```markdown
**Plan RP:** 14  
**Ceiling RP:** 18  
**Spent:** 0  
**Remaining to plan:** 14  

| Ch | RP | Map ID | Summary | Incorrect theories | Correct (writer) | Payoff | Bible sync |
|----|-----|--------|---------|--------------------|------------------|--------|------------|
| | | | | | | | |
```

---

## D. Blank Timeline Ledger

```markdown
| Date | Weather | Travel | Ch/Scenes | Elapsed | Impossible? | Notes |
|------|---------|--------|-----------|---------|-------------|-------|
| | | | | | Y/N | |
```

---

## E. Blank Relationship Matrix

```markdown
Temps: 1 ice · 2 cold · 3 neutral · 4 warm · 5 close · — n/a

|        | Meera | Ramesh | Ananya | Nav | Lakshmi | Venki | Shankarappa | Priya |
|--------|-------|--------|--------|-----|---------|-------|-------------|-------|
| Meera  | — | | | | | | | |
| Ramesh | | — | | | | | | |
| Ananya | | | — | | | | | |
| Nav    | | | | — | | | | |
| Lakshmi| | | | | — | | | |
| Venki  | | | | | | — | | |
| Shank. | | | | | | | — | |
| Priya  | | | | | | | | — |

**As of chapter:** __
```

---

## F. Blank Object Ledger

```markdown
| ID | Object | First Ch | Holder/Location | State | Symbolic | Last Ch | Notes |
|----|--------|----------|-----------------|-------|----------|---------|-------|
| O01 | Fence wire | | | | Y | | |
```

---

## G. Blank Knowledge Matrix Snapshot

```markdown
### After Chapter __

| Actor | Knows | Suspects | Wrong belief | Hidden from them |
|-------|-------|----------|--------------|------------------|
| Reader | | | | |
| Meera | | | | |
| Ramesh | | | | |
| Ananya | | | | |
| Nav | | | | |
| Lakshmi | | | | |
| Shankarappa | | | | |
| Priya | | | | |
| Others | | | | |
```

---

## H. Blank Continuity Checklist (per chapter)

```markdown
### Continuity — After Ch__

| Domain | State | FAIL? |
|--------|-------|-------|
| Weather | | |
| Dates | | |
| Travel | | |
| Phones | | |
| Injuries | | |
| Money | | |
| Vehicles | | |
| Wardrobe | | |
| Jokes | | |
| Food/tea | | |
| Fatigue/sleep | | |
| Festival clock | | |
| Wedding clock | | |
| Objects pointer | see OBJECT.md | |
| Relationships pointer | see RELATIONSHIP.md | |
| Knowledge pointer | see KNOWLEDGE.md | |
| Reveals pointer | see REVEAL.md | |
```

---

## I. Connections

| Document | Path |
|----------|------|
| Series Bible | `11_STORY_SEEDS/00_SERIES_BIBLE.md` |
| Blueprint | `11_STORY_SEEDS/BOOK_01/00_BLUEPRINT.md` |
| Production Manual | `11_STORY_SEEDS/BOOK_01/01_PRODUCTION_MANUAL.md` |
| Chapter Outline Standard | `11_STORY_SEEDS/BOOK_01/02_CHAPTER_OUTLINE_STANDARD.md` |
| Scene Outline Standard | `11_STORY_SEEDS/BOOK_01/03_SCENE_OUTLINE_STANDARD.md` |
| Revision Log (living) | `11_STORY_SEEDS/BOOK_01/05_REVISION_LOG.md` |
| Ledgers (living) | `11_STORY_SEEDS/BOOK_01/06_LEDGERS/` |
| Contradiction Log | `00_CANON/02_CONTRADICTION_LOG.md` |

---

## Closing

Prose invents sentences.  
This system invents accountability.

No structural change is real until it is classified, logged, approved at the correct level, and cascaded into every ledger it touches.

Continuity is not a final pass. Continuity is the substrate of every approved chapter.
