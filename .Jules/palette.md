# Palette Journal - UX & Accessibility Learnings

## 2025-09-15 - Calculator Accessibility & Focus Management
**Learning:** Legacy table-based calculator buttons (td elements) lack screen reader roles, aria-labels, and focus states by default. Retrofitting them via DOMContentLoaded script with `role="button"`, `tabindex="0"`, and custom `focus-visible` styling provides full keyboard accessibility without breaking layout or needing heavy HTML restructuring.
**Action:** Always add semantic roles, keyboard event handlers (`Enter`/`Space`), and visible focus rings to custom interactive elements.
