## 2025-05-14 - Retrofitting Accessibility to Table-Based UI
**Learning:** Legacy table-based layouts for interactive components like calculators often lack semantic roles and keyboard support. Instead of a full HTML refactor, a centralized `DOMContentLoaded` script can dynamically inject `role="button"`, `tabindex="0"`, and keyboard listeners to all interactive `<td>` elements. This ensures screen reader and keyboard compliance with minimal code changes.
**Action:** Use dynamic attribute injection for legacy table/grid-based UIs to quickly achieve accessibility compliance without breaking existing layout logic.

## 2025-05-14 - Physical Keyboard Support for Web Calculators
**Learning:** Users expect web calculators to respond to physical keyboard inputs (numbers, operators, Enter, Escape). A global `keydown` listener with a key mapping object is a low-overhead way to provide this "delightful" UX improvement.
**Action:** Always consider adding global keyboard listeners for single-purpose interactive tools like calculators to improve power-user efficiency.
