## 2025-05-14 - Interactive Table Cell Accessibility
**Learning:** For legacy projects using `<td>` elements as buttons, dynamic injection of `role="button"`, `tabindex="0"`, and keyboard listeners via a JavaScript loop is a concise way to achieve accessibility without invasive HTML changes.
**Action:** Use a mapping object for ARIA labels and `document.querySelectorAll('td[onclick]')` to apply attributes and listeners systematically.

## 2025-05-14 - Keyboard Event Collision
**Learning:** Global `keydown` listeners for keyboard shortcuts can collide with button-specific `keydown` listeners (e.g., for Enter/Space).
**Action:** Use `event.stopPropagation()` in button-specific listeners to prevent double-triggering when an interactive element is focused.
