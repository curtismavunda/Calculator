# Palette's Journal - Critical Learnings Only

## 2025-08-08 - Table-based Element Accessibility Retrofitting
**Learning:** Legacy table-based layouts elements like `<td>` lack semantic button roles, focus capability, and keyboard event bindings out of the box, leading to a complete block for assistive technologies and keyboard users. Programmatically retrofitting these cells with `tabindex="0"`, `role="button"`, and mapping labels ensures modern accessibility compliance without massive HTML restructures.
**Action:** Always map legacy tabular trigger cells to accessible roles, explicit screen-reader labels, and custom click-simulating handlers for keydown (`Enter` / `Space`) to elevate keyboard navigation seamlessly.
