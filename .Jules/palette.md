## 2026-06-01 - Keyboard Accessibility for Table-based UI
**Learning:** In legacy table-based layouts, interactive cells (<td>) are often used as buttons but are inaccessible to keyboard and screen reader users. Adding role="button", tabindex="0", and a global keyboard listener (Enter/Space) via a script is an efficient way to retrofit accessibility without major HTML restructuring.
**Action:** Always check for interactive non-button elements and ensure they have appropriate roles, focus states, and keyboard listeners.
