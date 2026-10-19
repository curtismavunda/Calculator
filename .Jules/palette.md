## 2025-07-01 - Table-based Button Keyboard Navigation & Outline Stacking
**Learning:** Legacy table cell (`<td>`) buttons require explicit `role="button"`, `tabindex="0"`, `position: relative` and `z-index: 1` on focus, as well as `event.stopPropagation()` on keydown to prevent focused button activations from triggering global physical keyboard mappings.
**Action:** When making custom table cell elements accessible, always set proper ARIA attributes, event cancellation on keypress, and z-index positioning for focus rings.
