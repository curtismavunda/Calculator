## 2025-10-06 - Focus Indicators on Table Cell Buttons
**Learning:** Table cells (`<td>`) used as custom buttons do not exhibit focus indicators properly if border-collapse is enabled, because adjacent borders obscure default outlines. Adding `position: relative` and `z-index: 1` to `td:focus-visible` ensures focus rings render cleanly on top of cell borders.
**Action:** Always include `position: relative` and `z-index: 1` on custom focus states for table-based interactive elements.
