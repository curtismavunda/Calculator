# Palette's Journal - Critical Learnings Only

## 2025-07-01 - Table-Based Calculator Keyboard Accessibility & Active Feedback
**Learning:** Legacy table-based UIs (`<td>` buttons) lack keyboard accessibility and ARIA semantics by default. Dynamically decorating `td[onclick]` elements with `role="button"`, `tabindex="0"`, `aria-label`, and keyboard event handlers transforms static tables into fully accessible interactive UI components without heavy HTML rewrites.
**Action:** When retrofitting legacy table or `div`-based interactive elements, apply `role="button"`, `tabindex="0"`, descriptive `aria-label`s, and `Enter`/`Space` keydown handlers with `preventDefault()` and `stopPropagation()`.
