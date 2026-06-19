## 2025-05-14 - Retrofitting Accessibility to Table-based UI
**Learning:** Legacy table-based layouts can be made keyboard and screen-reader accessible without major HTML refactoring by programmatically injecting roles, tabindex, and listeners via a centralized `DOMContentLoaded` script.
**Action:** Use a mapping object for ARIA labels and a loop to apply `role="button"` and `tabindex="0"` to interactive `<td>` elements, while ensuring `event.stopPropagation()` prevents double-triggering when global keyboard listeners are also present.
