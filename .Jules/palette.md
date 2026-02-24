## 2026-02-24 - Calculator Accessibility Patterns
**Learning:** Table cells used as buttons require `role="button"` and `tabindex="0"`. Global keyboard listeners (for 0-9, operators) must be complemented by button-specific listeners (for Enter/Space) that use `event.stopPropagation()` to avoid double-triggering. Additionally, `td:focus { outline: none; }` must precede `:focus-visible` in CSS to ensure focus rings aren't accidentally suppressed.
**Action:** Apply dynamic attribute injection for accessibility and careful event propagation management in similar static component projects.
