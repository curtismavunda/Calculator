## 2025-05-14 - Stacking focus indicators in table layouts
**Learning:** In table-based UIs with `border-collapse: collapse`, focus outlines on `<td>` elements can be clipped or obscured by the borders of adjacent cells.
**Action:** Apply `position: relative` and `z-index: 1` to `td:focus-visible` (or any focused table cell) to lift the element into a new stacking context, ensuring the entire focus indicator is visible and not clipped by neighboring elements.
