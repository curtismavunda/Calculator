## 2025-05-14 - Event Bubbling in Keyboard Listeners
**Learning:** When implementing both global keyboard shortcuts and element-specific keyboard listeners (e.g., for Tab navigation), focused element events will bubble to the global listener. If the global listener has a catch-all for a key like 'Enter', it may trigger a different action than intended for the focused element.
**Action:** Use `event.stopPropagation()` in element-specific keyboard listeners to prevent them from triggering global shortcuts that share the same key.
