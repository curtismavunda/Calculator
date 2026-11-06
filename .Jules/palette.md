# Palette's Journal

## 2025-07-01 - Accessible Retrofitting for Table-Based UI
**Learning:** Retrofitting accessibility (role="button", tabindex="0", and Enter/Space key listeners) onto legacy non-semantic elements like `<td>` via a lightweight centralized script ensures screen reader and keyboard accessibility without needing destructive HTML structure overhauls.
**Action:** When working with legacy table or div-based interfaces, dynamically apply accessible button semantics and focus management while styling `:focus-visible` with `position: relative` and `z-index: 1` so table borders don't clip focus rings.
