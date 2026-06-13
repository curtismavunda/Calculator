## 2025-05-15 - Retrofitting Accessibility to Table-Based UI
**Learning:** Legacy interfaces using `<td>` for buttons can be quickly made accessible and keyboard-navigable using a centralized `DOMContentLoaded` script to inject `role`, `tabindex`, and event listeners, avoiding massive HTML refactoring.
**Action:** Use a script-based augmentation pattern for legacy markup to ensure `role="button"`, `tabindex="0"`, and `Enter`/`Space` handlers are consistently applied across all interactive elements.

## 2025-05-15 - Enhancing Calculator Precision
**Learning:** Simple JavaScript calculators often use `parseInt` by default, which silently fails on decimal inputs or results. Switching to `parseFloat` immediately improves the UX for more complex calculations.
**Action:** Always prefer `parseFloat` for calculator-like input parsing unless integer-only behavior is explicitly required.

## 2025-05-15 - Keyboard Listener Conflicts
**Learning:** Global keyboard listeners for calculator shortcuts can conflict with focused buttons (e.g., pressing 'Enter' when a button is focused triggers both the button click and the global 'Enter' handler).
**Action:** Use `e.stopPropagation()` in element-specific keyboard listeners or check `e.target` in global listeners to prevent double-triggering actions.
