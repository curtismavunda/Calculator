# Palette's Journal

## 2023-11-20 - Retrofitting Keyboard Accessibility to Table Cells
**Learning:** Retrofitting accessibility (role, tabindex, listeners) to legacy table-based UI elements like `<td>` using a centralized DOMContentLoaded script is an efficient UX pattern that avoids heavy HTML refactoring while ensuring keyboard and screen reader support. Using `:focus-visible` ensures that focus rings only show for keyboard navigation, preserving mouse visual style.
**Action:** When working on table-based or non-semantic interactive layouts, use JavaScript on DOMContentLoaded to inject `tabindex="0"`, `role="button"`, proper `aria-label`s, and custom keyboard interaction listeners with `event.preventDefault()` to stop scroll behaviors and `event.stopPropagation()` to handle global shortcuts cleanly. Ensure focus outline utilizes `position: relative` and `z-index` so that outer cell borders do not obscure the keyboard indicator.
