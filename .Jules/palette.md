## 2026-03-09 - Event Target Handling with Inline Event Handlers

**Learning:** Inline HTML event handlers (e.g. `onclick="fn()"`) pass execution to standard functions where `window.event.currentTarget` evaluates to `null`. Using `(window.event && window.event.target) || (event && event.target)` ensures reliable element targeting for UI state toggles without requiring HTML attribute refactoring.
**Action:** Always check `window.event.target` when toggling active DOM classes inside legacy inline event handlers.
