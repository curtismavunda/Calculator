## 2025-05-14 - Accessible Table-based Buttons
**Learning:** In a project using `<td>` elements for interactivity, accessibility can be significantly improved by dynamically injecting `role="button"`, `tabindex="0"`, and `aria-label` via a JS loop. This keeps HTML source clean while ensuring screen reader support. Adding `td:focus { outline: none; }` before `td:focus-visible` ensures a clean focus experience for keyboard users without affecting mouse users.
**Action:** Use a similar dynamic injection pattern for legacy table-based UI components to enhance a11y with minimal code changes.
