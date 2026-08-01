# Contradiction Log
**Version:** 0.1  
**Status:** Accepted (process document)  
**Last Reviewed:** 2026-08-02

---

## Purpose

Track conflicts between canon claims so inconsistencies are resolved deliberately rather than papered over.

---

## Assumptions

1. Contradictions are inevitable during early worldbuilding; hiding them is worse than logging them.
2. Only one resolution may restore both claims to Accepted/Locked status.
3. Deprecated claims move to `99_ARCHIVE/` with a pointer here.

---

## Known Facts

### Log Format

| ID | Date Opened | Claim A | Claim B | Severity | Status | Resolution |
|----|-------------|---------|---------|----------|--------|------------|
| — | — | — | — | — | — | — |

**Severity:** `Low` (flavor) · `Medium` (continuity risk) · `High` (identity/timeline fracture)  
**Status:** `Open` · `Investigating` · `Resolved` · `WontFix-Intentional` (only if paradox is designed and flagged)

### Current Entries

None. Universe is pre-lore; no contradictions yet.

---

## Unknown Questions

1. Who may mark a contradiction `Resolved`?
2. Should intentional mysteries (reader-facing unknowns) be logged here or in a separate Mystery Ledger?

---

## Possible Improvements

1. Split process contradictions (meta) from in-universe apparent contradictions (mystery design).
2. Add link fields to PR/commit or chat decision records.

---

## Connections to Existing Canon

- Enforces internal consistency duty from `00_CANON/00_PROJECT_CHARTER.md`.
- Used whenever Accepted documents in any folder conflict.

---

## Future Story Opportunities

- Doyle-style mystery construction can use *apparent* contradictions as designed clue structures — logged as `WontFix-Intentional` only when the eventual reveal is already seeded in `11_STORY_SEEDS/`.
