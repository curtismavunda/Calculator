## 2025-07-01 - Retrofitting Table-based Buttons with Keyboard Accessibility & Focus Outlines

**Learning:** When retrofitting legacy `<td>` elements as accessible buttons (`role="button"`, `tabindex="0"`), keyboard event handlers on individual cells must call `e.stopPropagation()` to prevent double execution when global `window` keyboard listeners are active. Additionally, in `border-collapse: collapse` tables, focus indicators on cells require `position: relative` and `z-index: 1` to prevent adjacent cell borders from overlapping the focus ring.

**Action:** Always stop event propagation on element-level keyboard listeners when global shortcuts exist, and set `position: relative` with `z-index: 1` for focused table cells.
