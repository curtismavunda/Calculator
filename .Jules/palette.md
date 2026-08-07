# Palette's Journal

## 2023-11-20 - Retrofitting Keyboard Accessibility to Legacy Tables
**Learning:** Legacy table-based calculator grids can be dynamically retrofitted with keyboard navigation (`tabindex="0"`, `role="button"`) and standard ARIA labels without rewriting the entire layout, ensuring seamless screen reader and keyboard support with minimal code.
**Action:** Use a centralized DOMContentLoaded event listener to add accessibility attributes and keyboard event handlers (Enter/Space) to non-interactive elements that have `onclick` attributes.
