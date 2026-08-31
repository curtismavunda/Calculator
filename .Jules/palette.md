## 2025-05-18 - Retrofitting Accessibility & Physical Keyboard Support to Legacy Table Buttons

**Learning:** Legacy HTML table-based buttons (`<td onclick="...">`) lack built-in accessibility features (focusability, button semantics, keyboard listeners). Retrofitting `role="button"`, `tabindex="0"`, and keydown listeners via JavaScript along with clear `:focus-visible` CSS rules creates an accessible, screen-reader friendly keyboard navigation experience without requiring a full HTML structural overhaul.

**Action:** When working with table-based or non-semantic interactive UI elements, dynamically attach `role="button"`, `tabindex="0"`, and `Enter`/`Space` listeners with `event.stopPropagation()` to support keyboard navigation while avoiding bubbling conflicts with global shortcuts.
