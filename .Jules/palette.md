## 2025-05-18 - Highlight Active Operator in Calculator UI
**Learning:** Adding visual (`.active-operator`) and ARIA (`aria-pressed="true"`) feedback to pending state buttons (like selected math operators) reduces cognitive load by clearly reminding users of the current mode/operation in progress.
**Action:** When implementing multi-step or stateful controls (e.g. operators, toggle filters), ensure active states toggle dynamic ARIA attributes and clear when the operation concludes or resets.
