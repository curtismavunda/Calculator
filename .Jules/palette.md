## 2025-05-15 - Retrofitting Accessibility to Table-Based UIs
**Learning:** Legacy interfaces using non-semantic elements (like <td> for buttons) can be made accessible without a full HTML rewrite by using a centralized script to inject roles, tabindex, and keyboard listeners.
**Action:** Use a DOMContentLoaded listener to query and enhance interactive elements dynamically, ensuring both screen reader and keyboard-only users are supported while keeping HTML changes minimal.
