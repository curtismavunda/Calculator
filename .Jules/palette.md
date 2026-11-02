# Palette's Journal

## 2025-05-18 - Retrofitting Accessibility on Table-Based Interactive Elements
**Learning:** Table cells (`<td>`) acting as calculator buttons lack semantic roles, keyboard focusability, and ARIA labels. Retrofitting them dynamically via JavaScript with `role="button"`, `tabindex="0"`, keydown handlers for Enter/Space, and CSS `:focus-visible` with `position: relative` / `z-index: 1` provides full keyboard navigation and screen-reader support without disruptive HTML refactoring.
**Action:** When working with legacy non-semantic clickable elements, apply programmatic ARIA retrofits and relative positioning on `:focus-visible` to prevent adjacent cell borders from clipping focus rings.
