# Sauler89 fork changelog

## 2026-08-23 — Italian integration + New Journal Bestiary compatibility fix

- Added Italian installer language and Italian localization for the 25 Book of Torment-specific UI strings.
- Added `g-bt_it.tpa`, limited to Italian installations and designed to preserve the upstream English fallback behavior.
- Added a fail-fast New Journal Bestiary compatibility guard.
- The guard restores `getBestiaryImage2()` only when Book of Torment's original strict textual patch fails to add it to an already-modified `UI.menu`.
- If the expected New Journal control or safe insertion point is missing, installation aborts instead of leaving a partially working UI.
- No upstream BAM, MOS, PVRZ, CRE, BGEE.lua, TLK, or gameplay resources are modified by the compatibility guard.

Validation:
- Italian localization validated in-game.
- Bestiary repair validated in-game independently.
- Combined build passed static/integrity audits and final integrated runtime validation successfully.
