## 2026-02-11 - [Accessibility for Table-based UI]
**Learning:** When using non-interactive elements like `<td>` as buttons, it is critical to add `role="button"`, `tabindex="0"`, and a keyboard listener for Enter/Space to ensure the UI is accessible to screen readers and keyboard users.
**Action:** Always check for interactive elements that lack proper semantic roles and keyboard support.
