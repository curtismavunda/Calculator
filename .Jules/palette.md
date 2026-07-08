## 2025-05-15 - Retrofitting Accessibility to Legacy Table-based UI
**Learning:** Legacy UIs using `<td>` for buttons lack keyboard support and screen reader context. Retrofitting `role="button"`, `tabindex="0"`, and `aria-label` via a centralized `DOMContentLoaded` script is a clean, non-invasive way to achieve accessibility without major HTML refactoring.
**Action:** Use centralized DOM-based enhancement for legacy projects to keep HTML minimal while meeting modern accessibility standards.
