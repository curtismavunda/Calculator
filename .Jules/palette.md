## 2025-05-14 - Accessible Focus Indicators in Border-Collapsed Tables
**Learning:** In a table with 'border-collapse: collapse', custom focus outlines on '<td>' elements are often clipped or obscured by adjacent cell borders.
**Action:** Always apply 'position: relative' and 'z-index: 1' (or higher) to the focused element in CSS to ensure the focus indicator is fully visible and rendered above neighboring cells.
