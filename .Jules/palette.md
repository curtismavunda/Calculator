## 2025-07-01 - Table Cell Button Accessibility Pattern
**Learning:** Table cells (`<td>`) used as buttons require `role="button"`, `tabindex="0"`, explicit `aria-label`s, and a `keydown` handler (`Enter`/`Space`) with `e.preventDefault()` and `e.stopPropagation()` to enable full keyboard navigation and screen reader support without page scrolling or event bubbling.
**Action:** Always add semantic button ARIA attributes and keyboard listener bindings when refactoring custom clickable non-button elements.
