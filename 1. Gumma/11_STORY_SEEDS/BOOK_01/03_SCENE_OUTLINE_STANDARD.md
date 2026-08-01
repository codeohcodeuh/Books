# Gumma Universe — Book 1 Scene Outline Standard
**Version:** 0.1  
**Status:** Locked before Scene Outlines  
**Last Reviewed:** 2026-08-02  
**Working file:** `11_STORY_SEEDS/BOOK_01/03_SCENE_OUTLINE_STANDARD.md`  
**Depends on:** Book Blueprint + Production Manual + Chapter Outline Standard + Series Bible  
**Authority:** Production schema only. Does not override higher documents.

---

# PART I — PURPOSE

---

## Why Scene Outlines Exist

A **chapter outline** says what the chapter does.

A **scene outline** says how one scene accomplishes one specific piece of that work.

After a scene outline exists, a writer should be able to draft the scene without inventing:

- emotional beats  
- conflict  
- pacing  
- reveals  
- continuity  
- sensory anchors  

…while remaining free to write beautiful prose inside those constraints.

Scene outlines are engineering packets. They are not brainstorming. They are not draft prose.

---

## Relationship to Chapter Outline

| Layer | Job |
|-------|-----|
| Blueprint Part V row | Chapter’s locked job in the novel |
| Chapter Outline | Expands chapter into purpose, scenes list, trackers |
| **Scene Outline** | Fully specifies one scene from that list |
| Draft prose | Executes the scene outline in language |

**Rule:** Every scene listed in a chapter outline must have a corresponding scene outline file before that scene is drafted.

**Rule:** Scene outline fields may refine chapter-outline scene blocks; they may not contradict Blueprint locks (RP, date, POV, promise closures) without formal amendment.

---

## One File Per Scene

```text
11_STORY_SEEDS/BOOK_01/03_SCENE_OUTLINES/
  B01-Ch01-S01.md
  B01-Ch01-S02.md
  ...
  B01-ChCoda-S01.md
```

**Scene ID format:** `B01-Ch{NN|Coda}-S{0Y}`  
Example: `B01-Ch16-S02`

---

## No Prose

Forbidden inside scene outlines:

- Quotation marks as drafted dialogue  
- Narrative paragraphs in novel voice  
- Metaphor exploration  
- “Maybe” branching that reopens locked Blueprint decisions  

Allowed:

- Beat labels  
- Constraint lists  
- Continuity states  
- Writer-only correct interpretations marked as such  

---

# PART II — SCENE METADATA

All fields required unless marked optional.

| Field | Definition |
|-------|------------|
| **Scene ID** | `B01-ChXX-S0Y` |
| **Parent Chapter** | `ChXX` / `Coda` |
| **Sequence** | Order within chapter (1 = first) |
| **Estimated words** | Scene word budget (from chapter outline) |
| **Story date** | Calendar date (Blueprint Part XI) |
| **Time** | Clock / phase (e.g. 7:40 a.m.; dusk) |
| **Duration** | Real-time length of scene (e.g. 12 minutes; 40 minutes) |
| **POV** | Single POV; must match chapter POV unless Blueprint exception |
| **Weather** | Must continue chapter weather |
| **Location** | Specific place + Location ID if registered |
| **Onstage characters** | Who can speak/act/be perceived |
| **Offstage pressure** | Calls, rumors, clocks, people nearby but silent |
| **Reveal spend** | 0 or fractional/full chapter RP assigned to this scene |
| **Promise IDs** | P-IDs opened / advanced / closed in this scene |
| **Thread IDs** | T-IDs touched |
| **Reveal Map IDs** | R1–R8 if applicable; else none |
| **Status** | DRAFT / READY FOR PROSE / LOCKED / SUPERSEDED |

---

# PART III — ENTRY STATE

Exactly what is true **entering** the scene. No aspirational state.

### POV

| Field | Required content |
|-------|------------------|
| Emotion | Entering emotion (from prior exit or chapter opening state) |
| Knowledge | What they know/believe relevant to this scene |
| Immediate objective | Concrete want for the next minutes |

### Other onstage characters (each)

| Field | Required content |
|-------|------------------|
| Visible emotion | What POV can observe |
| Hidden objective | Writer-only; may not be narrated as omniscient fact |

### Reader

| Field | Required content |
|-------|------------------|
| Reader currently believes | Careful-reader state at scene entry |
| Incorrect beliefs we preserve | Optional but recommended |

---

# PART IV — SCENE PURPOSE

Answer in short, clinical sentences:

1. **Why does this scene exist?**  
2. **Removal test:** If deleted, what later scene/chapter breaks?  
3. **Promise work:** Which P-IDs move?  
4. **Relationship work:** Which pairs change temperature?  
5. **Emotional work:** What micro-shift must occur?  
6. **Institutional work:** RP spend justification — or explicit `0 — civilian only`.  

If (1) is “show the institution,” fail and redesign under the parent chapter’s human conflict.

---

# PART V — BEAT SHEET

---

## Rules

- **8–15 beats** per scene (short scenes may use 8; long scenes max 15).  
- Every beat includes all four columns: **action · conflict · emotional shift · information movement**.  
- **No dialogue** (no quoted lines).  
- **No narration** (no novelistic sentences).  
- **No paragraphs** — table or numbered one-liners only.  
- Beats must be draftable into prose without adding new plot decisions.

### Beat row schema

| Beat # | Action | Conflict | Emotional shift | Information movement |
|--------|--------|----------|-----------------|----------------------|
| 1 | What physically/socially happens | What resists | POV emotion from→to (micro) | What is learned, hidden, or misunderstood |

**Information movement** includes: none / rumor / partial fact / false inference / RP beat (named).

---

# PART VI — SCENE TURNING POINT

Explicitly define:

| Field | Content |
|-------|---------|
| **Irreversible change** | One sentence: what cannot be undone after this scene |
| **Type** | Relationship / knowledge / object / decision / injury / social exposure / absence |
| **Later breakage** | If this turn is removed, which later chapter/scene fails? |
| **Is this the chapter’s quiet turn?** | Y/N (Manual §3.1) |

A scene without a turning point is almost always illegal. Exception: pure recovery/breathing scenes must still change **temperature or fatigue state** and be marked `TURN TYPE: residual/recovery` with Blueprint permission via chapter outline.

---

# PART VII — EXIT STATE

Exactly what is true **leaving** the scene.

| Domain | Record |
|--------|--------|
| Knowledge | POV new know/believe; what still unknown |
| Emotion | Exit emotion (feeds next entry) |
| Relationships | Pair temps after |
| Objects | Gained/lost/moved |
| Weather | Unchanged / shifted how |
| Time | Clock out |
| Body | Fatigue, mud, injury, hunger |
| Reader | New belief / strengthened question |

---

# PART VIII — DIALOGUE CONSTRAINTS

Not dialogue text — constraints only.

| Field | Content |
|-------|---------|
| **Allowed topics** | What may be spoken |
| **Forbidden exposition** | System/lore teaching lines |
| **Forbidden speeches** | Mentor monologue, villain reveal, theme statements |
| **Subtext goals** | What each key speaker is really doing |
| **Power balance** | Who holds social power; does it shift? |
| **Interruptions** | Who cuts whom; logistics interrupts |
| **Silence** | Where silence is mandatory; what it must not be translated as in narration |
| **Language mix** | English / Kannada-dominant / code-switch notes |

---

# PART IX — SENSORY REGISTER

Required anchors (concrete, place-true). Minimum: **one per sense category used**; prefer 5+ total objects/sensations.

| Sense | Anchors (list) |
|-------|----------------|
| Sight | |
| Sound | |
| Touch | |
| Temperature | |
| Smell | |
| Motion | |
| Concrete objects | Named props that must appear |

**Rule:** At least one sensory anchor must appear in the planned exit image.

---

# PART X — CONTINUITY

| Item | Entering state | Exiting state | Pass? |
|------|----------------|---------------|-------|
| Wardrobe | | | |
| Mud / dust / sweat | | | |
| Phones | | | |
| Vehicles | | | |
| Food / tea | | | |
| Money / refusal | | | |
| Time | | | |
| Travel | | | |
| Weather | | | |
| Objects | | | |
| Injuries | | | |
| Who heard what | | | |
| Who does NOT know what | | | |

---

# PART XI — CANON VALIDATION

All must Pass before `READY FOR PROSE`:

| Check | Pass/Fail |
|-------|-----------|
| Reveal spend ≤ assignment from chapter outline | |
| Knowledge matrix respected for POV | |
| Promise ledger movement matches Blueprint intent | |
| Relationship temperatures inch, not jump | |
| Timeline / duration / travel possible | |
| Invisible layer limits respected | |
| No nuclear words planned | |
| Human problem first in beat 1–2 | |
| Matches parent chapter outline scene block | |
| Production Manual scene legality (not lore-only) | |

---

# PART XII — DRAFTING CONSTRAINTS

Prose for this scene may **NOT**:

1. Explain institutional meaning.  
2. Use omniscient narrator beyond POV perception.  
3. Use institutional language / nuclear vocabulary (Manual Appendix B).  
4. Foreshadow beyond what this outline and Blueprint allow.  
5. Use cinematic cheats (sudden omniscient overhead map; “little did they know”; slow-mo destiny; unexplained martial competence).  
6. Invent new plot turns not in the beat sheet.  
7. Translate silence into doctrine.  
8. Correct reader misinterpretations in narration.  
9. Spend RP not budgeted to this scene.  
10. Head-hop.

Prose **may**:

- Choose specific word-level imagery within Sensory Register  
- Invent micro-gestures that do not change plot  
- Shape dialogue wording inside Dialogue Constraints  

---

# PART XIII — SUCCESS GATE

Scene outline (and later drafted scene) passes only if:

| # | Gate | Y/N |
|---|------|-----|
| 1 | Character changes emotionally (including micro-shift) | |
| 2 | Conflict exists | |
| 3 | Reader can state POV objective | |
| 4 | Exit image memorable + sensory | |
| 5 | Scene cannot be moved elsewhere without damage (placement earned) | |
| 6 | Reveal budget respected | |
| 7 | No lore dump planned | |
| 8 | Human problem first | |
| 9 | Turning point defined | |
| 10 | Continuity table complete | |
| 11 | Beat sheet 8–15, four columns, no prose | |
| 12 | Canon validation all Pass | |

Any N → not READY FOR PROSE.

---

# APPENDIX A — BLANK SCENE OUTLINE TEMPLATE

Copy into `03_SCENE_OUTLINES/B01-ChXX-S0Y.md`.

---

```markdown
# Scene Outline — B01-Ch__-S__
**Status:** DRAFT  
**Version:** 0.1  
**Last updated:** YYYY-MM-DD  
**Drafter:**  
**Reviewer:**  

---

## II. Metadata

| Field | Value |
|-------|-------|
| Scene ID | B01-Ch__-S__ |
| Parent Chapter | |
| Sequence | |
| Estimated words | |
| Story date | |
| Time | |
| Duration | |
| POV | |
| Weather | |
| Location | |
| Onstage characters | |
| Offstage pressure | |
| Reveal spend | |
| Promise IDs | |
| Thread IDs | |
| Reveal Map IDs | none / |
| Parent chapter outline scene block confirmed? | Y/N |

---

## III. Entry State

### POV
- Emotion:
- Knowledge:
- Immediate objective:

### Other characters
| Character | Visible emotion | Hidden objective (writer-only) |
|-----------|-----------------|--------------------------------|
| | | |

### Reader
- Currently believes:
- Incorrect beliefs preserved:

---

## IV. Scene Purpose

**Why this scene exists:**


**Removal test:**


**Promise work:**


**Relationship work:**


**Emotional work:**


**Institutional / RP work:**


---

## V. Beat Sheet

| # | Action | Conflict | Emotional shift | Information movement |
|---|--------|----------|-----------------|----------------------|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |
| 5 | | | | |
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |
| 11 | | | | |
| 12 | | | | |
| 13 | | | | |
| 14 | | | | |
| 15 | | | | |

*(Delete unused beat rows; keep 8–15.)*

---

## VI. Scene Turning Point

**Irreversible change:**


**Type:**


**Later breakage if removed:**


**Is chapter quiet turn?** Y/N

---

## VII. Exit State

| Domain | State |
|--------|-------|
| Knowledge | |
| Emotion | |
| Relationships | |
| Objects | |
| Weather | |
| Time | |
| Body | |
| Reader | |

**Planned exit image (concrete):**


---

## VIII. Dialogue Constraints

**Allowed topics:**


**Forbidden exposition:**


**Forbidden speeches:**


**Subtext goals:**


**Power balance:**


**Interruptions:**


**Silence:**


**Language mix:**


---

## IX. Sensory Register

| Sense | Anchors |
|-------|---------|
| Sight | |
| Sound | |
| Touch | |
| Temperature | |
| Smell | |
| Motion | |
| Concrete objects | |

---

## X. Continuity

| Item | Entering | Exiting | Pass? |
|------|----------|---------|-------|
| Wardrobe | | | |
| Mud / dust / sweat | | | |
| Phones | | | |
| Vehicles | | | |
| Food / tea | | | |
| Money / refusal | | | |
| Time | | | |
| Travel | | | |
| Weather | | | |
| Objects | | | |
| Injuries | | | |
| Who heard what | | | |
| Who does NOT know what | | | |

---

## XI. Canon Validation

| Check | Pass/Fail |
|-------|-----------|
| Reveal spend OK | |
| Knowledge matrix OK | |
| Promise ledger OK | |
| Relationship temps OK | |
| Timeline OK | |
| Invisible layer limits OK | |
| No nuclear words | |
| Human problem first | |
| Matches chapter outline | |
| Manual scene legality | |

---

## XII. Drafting Constraints (scene-specific addons)

**Additional prose bans for this scene:**


**Allowed micro-inventions (gestures only):**


---

## XIII. Success Gate

| # | Gate | Y/N |
|---|------|-----|
| 1 | Emotional change | |
| 2 | Conflict exists | |
| 3 | Objective clear | |
| 4 | Exit image memorable | |
| 5 | Placement earned | |
| 6 | Reveal budget OK | |
| 7 | No lore dump | |
| 8 | Human problem first | |
| 9 | Turning point defined | |
| 10 | Continuity complete | |
| 11 | Beat sheet valid | |
| 12 | Canon validation Pass | |

---

## Sign-off

STATUS: DRAFT / READY FOR PROSE / LOCKED  

Signed: _______________ Date: _______________
```

---

# APPENDIX B — SCENE AUDIT CHECKLIST

Before upgrading status, answer **Yes** to all:

1. Scene ID matches parent chapter outline?  
2. Metadata complete (no blanks)?  
3. Entry state matches prior scene exit (or chapter opening)?  
4. Purpose survives removal test without lore?  
5. Beat sheet has 8–15 beats, four columns, zero prose/dialogue?  
6. Turning point irreversible and later-breakage named?  
7. Exit state fully specified?  
8. Dialogue constraints prevent teacher/oracle lines?  
9. Sensory register has concrete anchors; exit image uses one?  
10. Continuity table all Pass?  
11. Canon validation all Pass?  
12. Success gate all Y?  
13. RP does not exceed scene assignment?  
14. No nuclear vocabulary anywhere in plan?  
15. Writer could draft without inventing plot — only prose?

---

# APPENDIX C — CONNECTIONS

| Document | Path |
|----------|------|
| Blueprint | `11_STORY_SEEDS/BOOK_01/00_BLUEPRINT.md` |
| Production Manual | `11_STORY_SEEDS/BOOK_01/01_PRODUCTION_MANUAL.md` |
| Chapter Outline Standard | `11_STORY_SEEDS/BOOK_01/02_CHAPTER_OUTLINE_STANDARD.md` |
| Series Bible | `11_STORY_SEEDS/00_SERIES_BIBLE.md` |
| Chapter outlines | `11_STORY_SEEDS/BOOK_01/02_CHAPTER_OUTLINES/` |
| Scene outlines | `11_STORY_SEEDS/BOOK_01/03_SCENE_OUTLINES/` |
| Drafts | `11_STORY_SEEDS/BOOK_01/04_DRAFTS/` |

---

## Full Production Pipeline (Locked Sequence)

```text
Canon
  ↓
Series Bible
  ↓
Production Manual
  ↓
Book Blueprint
  ↓
Chapter Outline Standard
  ↓
Scene Outline Standard   ← this document
  ↓
Chapter Outlines
  ↓
Scene Outlines
  ↓
Draft Prose
  ↓
Development Edit
  ↓
Line Edit
  ↓
Continuity Pass
  ↓
Final Manuscript
```

No layer may be skipped.  
No prose may precede its scene outline.  
No scene outline may precede its parent chapter outline.

---

## Closing

Chapter outlines allocate the work.  
Scene outlines instrument the work.  
Prose performs the work — without renegotiating it.

Beauty remains free.  
Structure does not.
