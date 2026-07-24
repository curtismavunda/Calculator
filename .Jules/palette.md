# Palette's Journal - Critical Learnings

## 2023-11-20 - Retrofitting Keyboard Accessibility onto Legacy Tables
**Learning:** Retrofitting keyboard accessibility onto legacy table-based button UI elements (like `<td>`) using a dynamic dynamic listener script, custom focus visibility indicators, and standard ARIA attributes provides an efficient, low-overhead UX improvement that is highly accessible and perfectly preserves existing layouts.
**Action:** Always map standard buttons to proper screen reader and keyboard roles, and use a centralized `DOMContentLoaded` script or reactive hooks to keep HTML clean while ensuring 100% standard compliance.
