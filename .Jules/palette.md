## 2025-05-14 - Interactive Table Cells for Calculator
**Learning:** Using `<td>` elements as buttons without `role="button"` and `tabindex="0"` makes them invisible to screen readers and unreachable via keyboard. Adding these attributes along with a `keydown` listener significantly improves accessibility.
**Action:** Always ensure non-button interactive elements have appropriate ARIA roles, are focusable, and handle keyboard events (Enter/Space).
