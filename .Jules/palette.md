## 2025-05-14 - [Accessible Table-based Buttons]
**Learning:** In a table layout using 'border-collapse: collapse', focus outlines on '<td>' elements can be obscured by the borders of adjacent cells.
**Action:** Use 'position: relative' and 'z-index: 1' (or higher) on ':focus-visible' states for table cells to ensure the focus indicator is rendered above neighboring borders.
