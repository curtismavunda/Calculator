## 2025-05-15 - Retrofitting Accessibility to Legacy Table UI
**Learning:** For legacy UIs using non-semantic elements (like `<td>`) as buttons, a centralized `DOMContentLoaded` script can efficiently retrofit `role`, `tabindex`, and keyboard listeners without extensive HTML refactoring.
**Action:** Use a mapping object for ARIA labels and a global `keydown` listener to handle both physical keyboard shortcuts and focused element activation (Space/Enter). Ensure `readonly` on displays to prevent invalid manual input.
