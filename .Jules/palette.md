## 2025-05-14 - Focus Indicators on Table-based Layouts
**Learning:** In table-based layouts with `border-collapse: collapse`, standard focus outlines on `<td>` elements can be clipped by the borders of adjacent cells.
**Action:** Apply `z-index: 1` and `position: relative` to `:focus-visible` states of table cells to ensure the focus indicator remains fully visible and on top of neighboring borders.
