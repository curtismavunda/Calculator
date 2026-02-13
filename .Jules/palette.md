## 2026-02-13 - Accessibility and Keyboard Navigation for Table-based UI
**Learning:** Using <td> elements as buttons requires explicit ARIA roles (role="button") and tabindex="0" to be accessible. A global keydown listener combined with event.stopPropagation() on focused elements prevents double-triggering while allowing a "type-anywhere" experience.
**Action:** Always pair role="button" with keyboard listeners for Enter/Space, and use :focus-visible for clear focus indicators that don't clutter the UI for mouse users.
