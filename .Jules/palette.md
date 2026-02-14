## 2025-05-22 - Accessibility mapping and focus styles
**Learning:** For interactive elements like table cells (`<td>`) used as buttons, it's critical to add `role="button"` and `tabindex="0"`. Additionally, mapping physical keyboard keys (0-9, operators) to calculator functions significantly improves micro-UX for desktop users.
**Action:** Always ensure that custom interactive components have appropriate ARIA roles, labels, and keyboard support, and maintain visible focus indicators (using `:focus-visible` while resetting default `:focus` when necessary).
