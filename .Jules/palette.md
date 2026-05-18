## 2025-05-14 - Focus indicators on table cells
**Learning:** Custom focus outlines on table cells (<td>) can be obscured by the borders of adjacent cells.
**Action:** Use 'position: relative' and 'z-index: 1' on 'td:focus-visible' to ensure the focus indicator is rendered above neighboring borders.
