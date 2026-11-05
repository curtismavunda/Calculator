# Palette's Journal

## 2026-11-05 - Keyboard navigation & accessible semantics for table-based calculator
**Learning:** Table cells (`<td>`) used as interactive buttons are invisible to keyboard tab navigation and lack accessible roles and labels. Retrofitting them via `DOMContentLoaded` with `role="button"`, `tabindex="0"`, descriptive labels, and Enter/Space handlers provides immediate a11y compliance without breaking table styling.
**Action:** When working with legacy table layouts acting as UI widgets, attach keyboard interaction handlers and `:focus-visible` styles with `position: relative` and `z-index: 1` to ensure outlines render over cell borders.
