## 2026-06-21 - Retrofitting Keyboard Accessibility to Table UI
**Learning:** When adding keyboard support to a table-based UI using role="button", global keydown listeners can conflict with focused button actions (e.g., 'Enter' triggering both the focused button and a global shortcut).
**Action:** Use event.stopPropagation() in the button-specific keydown handler and event.preventDefault() for keys like Space to ensure clean interaction and prevent double-triggering.
