## 2026-03-11 - Focus Ring Visibility in Table Layouts
**Learning:** In table-based layouts with collapsed borders, focus outlines on `<td>` elements can be clipped or obscured by adjacent cells.
**Action:** Apply `position: relative` and `z-index: 1` to `td:focus-visible` to ensure the focus indicator is rendered above neighboring elements.
