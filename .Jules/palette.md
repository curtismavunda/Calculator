## 2025-05-14 - Retrofitting accessibility to table-based UI
**Learning:** For legacy interfaces using table cells (<td>) as interactive elements, a centralized DOMContentLoaded script can efficiently add roles, tab indices, and keyboard listeners without requiring a complete HTML overhaul.
**Action:** Use a mapping object for ARIA labels and a global keydown listener combined with per-element listeners to ensure both physical keyboard shortcuts and tab-navigation focus interactions work seamlessly.
