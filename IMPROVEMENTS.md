# Improvements (2026-09-09)

Unofficial ICC RC Special Inspector study guide upgrade summary.

## Content
- **Deepened** `quality`, `rebar`, and `formwork` modules: JTA-style angles, before/during/after pour sequences, common non-conformances, edge cases, documentation instincts.
- Lightly enriched **Critical Numbers** sheet with batch tickets, initial curing, form removal, embeds, statement of SI themes (still soft / verify-in-refs).
- Kept GR / codes / plans solid without bloating them to the same depth.

## Quiz
- Replaced 4 static HTML items with a **JS question bank (~28 original MC questions)**.
- Topics: GR duties, continuous vs periodic, cover timing, batch tickets, rebar/splices/cover, embeds, curing/hot-cold, NCR reporting, plans-reading traps.
- Shuffle, per-topic filter, check/score with highlight, "verify in official refs" note.
- Answers live in JS (not `data-correct` in static HTML).

## UX / polish
- **Mobile drawer:** hamburger, overlay, sidebar slide-in (<900px), body scroll lock, close on nav/overlay; desktop unchanged.
- Theme persisted in `localStorage` (`iccTheme`).
- **Mark reviewed** is toggleable (undo).
- Progress shows **count and %**.
- Footer / README last-updated: **September 9, 2026**.
- Remains a **single-file offline HTML**.

## Legal fence
- No ICC exam dumps, no verbatim Concrete Manual / ACI 318 / IBC / CRSI text or copyrighted tables.
- Soft numbers with verify-in-current-official-references language throughout.
