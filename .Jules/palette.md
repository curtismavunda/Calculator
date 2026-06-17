## 2025-05-14 - Retrofitting accessibility to table-based UI
**Learning:** Legacy table-based layouts for interactive components like calculators often lack semantic roles and keyboard support. A centralized DOMContentLoaded script can efficiently inject ARIA roles, tabindex, and keyboard listeners without requiring a complete markup rewrite.
**Action:** When working with legacy table UIs, use a script to map button text to descriptive ARIA labels and ensure 'z-index: 1' and 'position: relative' are used on focus states to prevent borders from masking the focus indicator.
