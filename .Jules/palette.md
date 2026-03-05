## 2025-03-05 - Table-based UI Accessibility
**Learning:** In table-based layouts with `border-collapse: collapse`, focus outlines on `td` elements can be clipped by the borders of adjacent cells.
**Action:** Apply `z-index: 1` and `position: relative` to `td:focus-visible` to ensure the focus indicator remains fully visible above neighboring elements.
