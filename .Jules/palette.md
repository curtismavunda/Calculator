## 2026-05-12 - Enhanced Focus Indicators for Table-based UI
**Learning:** In table-based layouts with collapsed borders, standard focus outlines on '<td>' elements can be partially obscured by the borders of adjacent cells.
**Action:** Apply 'position: relative' and 'z-index: 1' (or higher) to 'td:focus-visible' to ensure the focus indicator is drawn on top of all neighboring elements.
