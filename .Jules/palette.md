## 2025-05-15 - Improving Focus Visibility in Table Layouts
**Learning:** In table-based layouts where cells share borders, standard focus outlines can be clipped by adjacent cells. Applying `z-index: 1` and `position: relative` to the focused element ensures the outline is rendered above neighboring cells.
**Action:** Always use `z-index: 1` and `position: relative` for `td:focus-visible` in table-heavy UIs to maintain clear focus indicators.
