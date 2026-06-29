## 2025-05-14 - Keyboard accessibility for custom buttons
**Learning:** When retrofitting keyboard support (Enter/Space) to custom button elements (like <td>) while also having a global keydown listener for physical keyboard shortcuts, use `event.stopPropagation()` on the button-specific listener to prevent the event from bubbling up and triggering the action twice.
**Action:** Always include `stopPropagation()` in element-level keyboard listeners if a global shortcut listener is also present.
