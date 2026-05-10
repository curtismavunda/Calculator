## 2025-05-14 - Ensuring focus visibility on table-based layouts
**Learning:** In table-based layouts with collapsed borders, the focus outline of a cell can be clipped or obscured by the borders of adjacent cells.
**Action:** Apply `z-index: 1` and `position: relative` to `td:focus-visible` elements to lift the focused cell above its neighbors, ensuring the entire outline remains visible.
