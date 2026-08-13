## 2025-08-13 - Preserving Table Cell Focus Outlines
**Learning:** When applying custom `:focus-visible` outline indicators to HTML table-based buttons (`<td>`), the outline can be partially cut off or completely obscured by adjacent cells' borders. This occurs because tables share border lines.
**Action:** Always include `position: relative` and `z-index: 1` alongside custom focus outline definitions on table cells to elevate the focused cell above adjacent layers, ensuring the complete focus ring remains visible to keyboard navigators.
