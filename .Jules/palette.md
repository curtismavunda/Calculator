## 2025-05-15 - Accessible Focus Indicators in Table-Based Layouts
**Learning:** In table-based layouts where cells have borders and background colors, standard focus outlines can be clipped or obscured by the borders of adjacent cells.
**Action:** Apply `position: relative` and `z-index: 1` to `td:focus-visible` elements to ensure the focus indicator is rendered above all neighboring elements and remains fully visible. Using a negative `outline-offset` (e.g., `-3px`) also helps keep the indicator within the cell's boundaries.
