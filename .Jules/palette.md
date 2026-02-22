## 2025-05-15 - Double-triggering prevention in keyboard navigation
**Learning:** In applications with both global `keydown` listeners and element-specific `keydown` listeners (e.g., for Enter/Space), `event.stopPropagation()` is essential in the element-specific listener to prevent the action from being executed twice if both listeners handle the same key.
**Action:** Always include `event.stopPropagation()` in button-specific keyboard listeners when a global listener for the same keys exists.
