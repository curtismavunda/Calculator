# Palette Journal

## 2023-11-20 - Retrofitting Accessibility to Table-Based UI
**Learning:** Legacy table-based calculator buttons (<td> with onclick) are completely inaccessible to screen readers and keyboard users. Retrofitting them with 'role="button"' and 'tabindex="0"' via standard JS/CSS focus rules makes them accessible without breaking the layout.
**Action:** Always add tabindex, role, and focus-visible handlers to interactable non-semantic elements.
