# Documentation Architecture
**Version:** 0.1  
**Status:** Provisional  
**Canon Authority:** Derived from Project Charter v0.1

---

## Purpose

Establish a studio-grade filing system so the Gumma Universe bible remains navigable, cross-referenced, and resistant to contradiction as it scales.

---

## Assumptions

1. Documentation volume will grow into hundreds of files; folder discipline matters more than clever naming.
2. Markdown is the working format for v0.1.
3. Maps, family trees, and diagrams may later include image/SVG assets stored beside their parent documents.
4. No deep lore is Accepted until foundational questions are resolved.

---

## Known Facts

### Directory Map

```text
00_CANON/                 Project rules, architecture, status taxonomy, contradiction log
01_FOUNDATIONS/           Open questions, core premises, naming, tone, medium
02_UNIVERSE_BIBLE/        Master overview and pillar summaries
03_TIMELINE/              Eras, chronologies, divergence notes
04_HISTORY/               Historical integration, hidden history, period dossiers
05_ORGANIZATION/          Hierarchy, traditions, moral code, philosophy, influence
06_HOUSES_AND_LINEAGES/   Houses, family trees, inheritance rules
07_PLACES/                Surface architecture, underground infrastructure, maps
08_PEOPLE/                Character database and dossiers
09_CULTURE/               Languages, symbols, rituals, daily praxis
10_CRAFT/                 Training, weapons, technologies, methods
11_STORY_SEEDS/           Long-term seeds, mystery ledgers, franchise arcs
99_ARCHIVE/               Deprecated, superseded, or rejected concepts (never delete silently)
```

### Document Header Convention

```markdown
# [Title]
**Version:** x.y
**Status:** Proposed | Provisional | Accepted | Locked | Deprecated
**Last Reviewed:** YYYY-MM-DD
```

### Mandatory Body Sections

Purpose · Assumptions · Known Facts · Unknown Questions · Possible Improvements · Connections to Existing Canon · Future Story Opportunities

### Cross-Reference Rule

When Document A depends on a fact from Document B, cite B by path. Do not restate contested facts as if settled.

### Contradiction Rule

If two Accepted documents conflict, open an entry in `00_CANON/02_CONTRADICTION_LOG.md` and downgrade the weaker claim to Provisional until resolved.

---

## Unknown Questions

1. Should character dossiers use a fixed template ID system (e.g., `GUM-PER-0001`)?
2. Do we need a separate `LEGAL_AND_ETHICS/` folder for real-history portrayal guidelines?
3. Will bilingual source terms (Sanskrit, regional languages, Persian, English) require a controlled glossary file from day one?
4. Should maps be textual first (node maps) or visual-first?

---

## Possible Improvements

1. Add an auto-generated index once file count exceeds ~30.
2. Introduce a `CANON_INDEX.md` with one-line summaries per Accepted document.
3. Add tags for era, region, house, and secrecy level.

---

## Connections to Existing Canon

- Implements filing needs implied by `00_CANON/00_PROJECT_CHARTER.md`.
- Gates invention behind `01_FOUNDATIONS/01_OPEN_QUESTIONS.md`.

---

## Future Story Opportunities

- A clean architecture allows later “in-universe” documents (manuals, ledgers, coded letters) to sit beside out-of-universe bible entries without confusing authority levels — if we later add an `IN_UNIVERSE/` vs `OUT_OF_UNIVERSE/` distinction.
