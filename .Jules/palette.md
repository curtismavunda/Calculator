## 2025-05-18 - Retrofitting accessibility onto legacy table-based UI
**Learning:** Legacy web applications using `<table>` cells with `onclick` handlers are completely inaccessible to screen reader and keyboard users; retrofitting `role="button"`, `tabindex="0"`, dynamic ARIA labels, and keydown handlers in a lightweight script bridges the gap cleanly without risking visual regressions.
**Action:** Inspect interactive custom non-button elements, add keyboard event listeners and ARIA attributes via DOMContentLoaded, and ensure visible `:focus-visible` styling is included.
