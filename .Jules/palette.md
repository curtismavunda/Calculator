## 2023-11-20 - Legacy Table Button Accessibility
**Learning:** Legacy tabular layouts using `<td>` for buttons need a centralized accessibility initialization. Adding `tabindex="0"`, `role="button"`, and mapping `Enter`/`Space` with `event.preventDefault()` and `event.stopPropagation()` provides robust keyboard accessibility without major HTML refactoring.
**Action:** Always use a centralized DOMContentLoaded script to inject standard a11y attributes and listeners to elements functioning as buttons.
