## 2026-07-06 - [Accessible Table-Based Calculator]
**Learning:** Legacy table-based UIs can be retrofitted for accessibility without massive refactoring by using a centralized DOMContentLoaded script to inject roles, tabindex, and ARIA labels. Additionally, custom focus outlines on <td> elements require 'position: relative' and 'z-index: 1' to prevent adjacent cell borders from obscuring the focus indicator.
**Action:** Use centralized attribute injection for legacy components and ensure proper stacking context for focus indicators on grid/table layouts.
