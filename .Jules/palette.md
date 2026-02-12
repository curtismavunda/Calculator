## 2025-05-14 - [Accessibility injection for legacy tables]
**Learning:** For legacy UIs with many interactive elements (like a table-based calculator), injecting ARIA attributes (role, tabindex, labels) and keyboard listeners via a small JavaScript block is more line-efficient and maintainable than manual HTML edits. It ensures consistency across all elements without cluttering the markup.
**Action:** Use script-based accessibility enhancement when dealing with repetitive legacy components to keep changes scoped and readable.

## 2025-05-14 - [Keyboard shortcut double-triggering]
**Learning:** Adding global keyboard shortcuts (e.g., Enter for 'equals') while also supporting focused button activation (e.g., Space/Enter on a digit) can cause double-triggering.
**Action:** Use `event.stopPropagation()` in button-specific keyboard listeners to prevent events from bubbling up to the global document listener.
