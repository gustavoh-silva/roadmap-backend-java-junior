# AGENTS.md — roadmap-backend-java-junior

Single-file static site. `index.html` is the app (markup + CSS + JS in one file). No build, no dependencies, no test suite. `DESIGN.md` is the visual source of truth (Nocturne Gallery). Deploy: push to `main` → GitHub Pages serves the repo root (`.github/workflows/Pages.yml`).

## Verify (no test runner exists)

- Syntax: extract the inline `<script>` and run `node --check` on it.
- Serve: `python -m http.server 8000` → `http://localhost:8000`.
- After UI changes: zero horizontal overflow at 390px and 1280px, no console errors, toggles update all counters.

## index.html conventions (will bite you)

- Code is minified single-line style. Use exact-string `Edit` with nearby anchors; never retype accented text (UTF-8: ã, ç, é, →) — copy it verbatim.
- All logic is hoisted `function` declarations inside one IIFE — call order is safe, definition order is cosmetic.
- Rendering is full re-render from `localStorage` (`renderGates(); renderFront(); ... updateDash();`). New panels: render from inside `updateDash()` (single call-site pattern), never add parallel render chains.
- Event handling is delegated on `document` (`data-*` attributes). New controls reuse this; never attach per-element listeners in render output.
- `esc()` escapes only `&` and `<` — never interpolate into `"..."` attributes without `.replace(/"/g,"&quot;")`.
- State lives in `localStorage` under the `K` const. Never add keys casually. Any path that replaces all state (reset, import) must also seal migration flags (`K.mig/mig3/mig42`), or old migrations will clobber the data on next load.
- `recordStudyEvent` dedupes same `(id,status)` within 2 min — rapid toggles collapse; OFF-style statuses end with `_OFF` and are excluded from IA buckets.
- History is capped (`STUDY_HISTORY_LIMIT=80`); any new event type must respect the cap.

## Design (DESIGN.md wins over taste)

- Tokens only: canvas `#07080a`, ladder `tile-1/2/3`, Action Sky `#2997ff` (text/links/glow only), CTA fill `#0071e3`, hairlines, 18px cards, pill actions, Inter + `ss03`.
- State is always text + color, never color alone; focus-visible outlines required.
- Honest metrics only: show real counts/percentages, never invented projections. Changing a metric's unit (e.g. project-based → criterion-based) needs a user-visible note, not silent blending.

## Shell (Windows, PowerShell 7)

- No `head`/`grep`: use `Select-Object -First N` and `Select-String -Path index.html -Pattern ...`.
- Feature work happens on `vX.Y-name` branches, merged with `git merge --no-ff` into `main`. Never commit directly to `main` without being asked.
