## 2025-05-14 - Ensuring visible focus in table-based layouts
**Learning:** In table-based layouts with `border-collapse: collapse`, focus outlines on `<td>` elements can be clipped by the borders of adjacent cells.
**Action:** Apply `z-index: 1` and `position: relative` to `td:focus-visible` to ensure the focus indicator is fully rendered above surrounding borders.

## 2025-05-14 - Keyboard activation for non-semantic buttons
**Learning:** When using `<td>` or other non-interactive elements as buttons, adding `role="button"` and `tabindex="0"` is only the first step.
**Action:** Always attach a `keydown` listener for 'Enter' and ' ' (Space) that triggers the element's `click()` method to maintain parity with native button behavior.
