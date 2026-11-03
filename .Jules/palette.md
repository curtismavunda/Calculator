# Palette's Journal

Critical UX and accessibility learnings from design and implementation work.

## 2025-05-18 - Retrofitting Accessibility to Table-Based UI Elements
**Learning:** Legacy calculator interfaces built using `<table>` and `<td>` elements with inline `onclick` handlers completely exclude keyboard users and screen readers unless ARIA roles, tabindex, and key listeners are systematically applied. Using a lightweight centralized script on `DOMContentLoaded` provides instant full keyboard and screen reader accessibility without massive markup refactoring.
**Action:** When working with table-based interactive UIs, map accessible ARIA labels, add `role="button"`, assign `tabindex="0"`, and wire up `Enter`/`Space` listeners alongside high-contrast focus rings.
