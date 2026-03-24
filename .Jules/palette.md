## 2025-05-15 - Enhancing Table-Based Button Focus Visibility
**Learning:** In table-based layouts, focus outlines on `<td>` elements can be clipped by adjacent cell borders. Applying `z-index: 1` and `position: relative` to the `:focus-visible` state ensures the outline is drawn above neighboring elements.
**Action:** Always use `position: relative` and `z-index` when adding focus indicators to elements within restrictive parent containers like tables or flex/grid items with tight spacing.
