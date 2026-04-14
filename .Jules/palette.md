## 2025-05-15 - Enhancing Table-Based Interactive Elements
**Learning:** For table-based layouts where `<td>` elements serve as buttons, default browser focus outlines are often clipped by adjacent cell borders. Applying `z-index: 1` and `position: relative` to `td:focus-visible` ensures the focus indicator is fully visible without altering the layout.
**Action:** Always use `z-index` and `position: relative` when styling focus indicators for elements within a table or grid with collapsed borders.
