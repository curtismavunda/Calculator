## 2025-05-27 - [Custom Table-based Buttons Accessibility]
**Learning:** Table cells (<td>) used as buttons lack inherent accessibility. They require role="button", tabindex="0", and explicit event listeners for 'Enter' and 'Space' to be usable by keyboard and screen reader users.
**Action:** When encountering non-semantic interactive elements, always apply appropriate ARIA roles, ensure they are in the tab order, and provide keyboard parity for click events.
