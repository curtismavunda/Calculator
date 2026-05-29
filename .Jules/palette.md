## 2026-05-29 - Keyboard Navigation for Table-based UI
**Learning:** For legacy table-based layouts, adding 'role="button"' and 'tabindex="0"' via JavaScript allows for micro-UX improvements without major HTML restructuring. Descriptive 'aria-label's for symbols (e.g., "multiply" instead of "x") significantly improve screen reader clarity.
**Action:** Always map operator symbols to descriptive labels and ensure keyboard listeners (Enter/Space) include 'preventDefault' to avoid page scroll or other default behaviors.
