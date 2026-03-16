## 2025-05-15 - Table Cell Focus Indicators
**Learning:** In table-based layouts, focus outlines on `<td>` elements can be partially clipped by the borders of adjacent cells.
**Action:** Apply `position: relative` and `z-index: 1` to `td:focus-visible` to ensure the outline is rendered above all neighboring elements.
