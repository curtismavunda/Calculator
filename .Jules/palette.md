## 2025-05-18 - Retrofitting accessibility to table-cell buttons
**Learning:** Legacy table-based calculator buttons (`<td>` with `onclick`) lack focusability and screen reader semantics. Adding `role="button"`, `tabindex="0"`, explicit ARIA labels for symbols, and `Enter`/`Space` handlers restores keyboard/screen-reader accessibility without changing layout markup.
**Action:** Use dynamic DOM retrofitting for legacy tabular layouts when direct HTML refactoring is constrained.
