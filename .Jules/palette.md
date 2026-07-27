# Palette's Journal - Critical UX/Accessibility Learnings

This journal tracks critical UX and accessibility insights discovered during development.

## 2025-07-27 - Retrofitting Keyboard Accessibility on Legacy Table-Based UIs
**Learning:** Table cells (`<td>`) lack semantic keyboard support, focusability, and tactile feedback. Directly retrofitting them dynamically via a centralized `DOMContentLoaded` script with `tabindex="0"`, `role="button"`, and key event interception offers a robust, low-footprint way to make legacy designs fully accessible without breaking the existing structural layout or styling rules.
**Action:** Always add `tabindex="0"`, `role="button"`, appropriate ARIA labels, and keydown handlers (listening for 'Enter' and 'Space') to table cells when they function as interactive elements. Use `event.preventDefault()` to stop page scrolling and `event.stopPropagation()` to prevent global listener conflicts.
