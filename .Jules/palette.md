# Palette Journal

## 2025-07-01 - Keyboard-accessible Table-based Calculator
**Learning:** Legacy table-based calculator structures (`<table>`/`<tr>`/`<td>`) are inherently inaccessible to screen readers and keyboard users as standard HTML table cells do not support tab focus or standard interaction states. Retrofitting `tabindex="0"`, `role="button"`, and explicit `aria-label` attributes to the cells dynamically via JS enables accessible navigation without modifying the legacy table-based structure. In addition, suppressing scrolling for the `Space` key using `preventDefault()` is essential when converting interactive elements to keyboard-focusable buttons.
**Action:** Use a dynamic script during page loading (`DOMContentLoaded`) to map interactive `td` elements to buttons and focus states, and handle element-level versus global key listeners appropriately.
