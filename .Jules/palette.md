## 2025-05-14 - Retrofitting Keyboard Accessibility to Legacy Table UI
**Learning:** When adding both global physical keyboard listeners and button-specific focus listeners (to handle Space/Enter), use `event.stopPropagation()` on the button listeners. This prevents a focused button from triggering the logic twice (once via its own listener and once via the global listener) when the key matches both (e.g., Enter on an '=' button).
**Action:** Always include event propagation control when implementing overlapping keyboard interaction layers.
