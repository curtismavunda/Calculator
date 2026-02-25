## 2025-05-15 - Improving Accessibility for Table-Based Interactive Elements
**Learning:** In applications using non-semantic elements like '<td>' for buttons, focus management and keyboard interaction are entirely absent. Dynamic injection of 'role="button"', 'tabindex="0"', and descriptive ARIA labels is a concise way to fix this without bloating the HTML.
**Action:** Always use a loop to inject these attributes and add 'keydown' listeners (with stopPropagation) when encountering table-cell interactive patterns.
