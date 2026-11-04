# Palette's Journal

Critical UX and accessibility learnings from working on this codebase.

## 2025-05-18 - Retrofitting Accessibility to Table-Based Calculator Interfaces
**Learning:** Retrofitting legacy table-based UI elements (`<td>`) with `role="button"`, `tabindex="0"`, and custom `:focus-visible` styles requires setting `position: relative` and `z-index: 1` so that table borders do not clip or obscure keyboard focus rings.
**Action:** When adding focus outlines to HTML table cells, always ensure `position: relative` and `z-index: 1` are specified on `:focus-visible`, and separate `:focus { outline: none; }` from `:focus-visible` to prevent visual noise for mouse users while preserving accessibility for keyboard users.
