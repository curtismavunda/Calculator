## 2025-05-14 - Accessible Table-based Interactive Elements
**Learning:** When using `<td>` elements as interactive buttons in a table with `border-collapse: collapse`, focus outlines can be obscured by the borders of adjacent cells. Using `position: relative` and `z-index: 1` on the focused element ensures the outline remains fully visible.
**Action:** Always apply relative positioning and a higher z-index to focused table cells when implementing custom focus indicators in legacy table layouts.
