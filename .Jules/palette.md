## 2025-05-18 - Active State Indication for Single-Selection Operator Buttons
**Learning:** In simple calculator interfaces, users often lose track of which operator (+, -, *, /) was selected prior to entering the second operand. Highlighting the active operator button using a distinct background color and inset box-shadow provides clear, persistent visual feedback without cluttering the UI.
**Action:** Always maintain an active state CSS class on selected toggle/operator controls and clear it on operation completion (=) or reset (AC).
