## 2025-05-14 - Accessibility Pattern for Table-Based Buttons
**Learning:** In legacy table-based layouts where `<td>` elements are used as buttons via `onclick`, accessibility can be injected dynamically without a full HTML refactor. Using `role="button"`, `tabindex="0"`, and `aria-label` along with keyboard listeners for Enter/Space provides a high-impact UX improvement with minimal code changes.
**Action:** Use `document.querySelectorAll('td[onclick]')` to identify interactive cells and inject necessary ARIA attributes and keyboard event listeners in a `DOMContentLoaded` event.
