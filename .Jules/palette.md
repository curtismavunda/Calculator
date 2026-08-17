## 2025-08-17 - Keyboard navigation on table-based UI elements

**Learning:** Adding `tabindex="0"`, `role="button"`, and `aria-label` to table cell (`<td>`) elements allows screen readers and keyboard users to navigate non-standard button structures. Calling `e.stopPropagation()` in element-level `keydown` handlers prevents bubbling up to global window listeners.

**Action:** Ensure custom interactive non-button elements have explicit ARIA roles, tabindex, and scoped keydown handlers to prevent shortcut conflicts.
