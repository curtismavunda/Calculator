## 2025-06-11 - Retrofitting Accessibility to Table-Based UI
**Learning:** Legacy table-based layouts (using `<td>` as buttons) can be made accessible and keyboard-friendly without a full refactor by using a centralized `DOMContentLoaded` script to inject roles, tabindex, and listeners.
**Action:** Use `querySelectorAll('td[onclick]')` to target interactive cells and apply `role="button"` and `tabindex="0"` dynamically.

## 2025-06-11 - Robust Calculator State Management
**Learning:** In simple calculators, switching from `parseInt` to `parseFloat` is a low-effort, high-impact UX win for accuracy. Additionally, early returns in calculation functions (e.g., when no operator is selected) prevent 'undefined' from leaking into the UI.
**Action:** Always prefer `parseFloat` for numerical input and implement guard clauses for operator state.
