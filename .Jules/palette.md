## 2025-05-14 - Accessible Focus Indicators in Table Layouts
**Learning:** In table layouts with `border-collapse: collapse`, focus outlines on `<td>` elements are often clipped by the borders of adjacent cells.
**Action:** Apply `position: relative` and `z-index: 1` to `td:focus-visible` to ensure the focus indicator is rendered above neighboring cells and remains fully visible.
