# Palette Agent Journal

## 2025-05-10 - Operator Active Visual State
**Learning:** Adding an `.active-operator` state on operator buttons (`+`, `-`, `x`, `/`) gives immediate, continuous visual feedback on pending operations in calculator UIs. Passing `this` directly from inline event handlers (`onclick="operatorBtnPressed(this, '+')"`) avoids deprecated `window.event` usages and ensures clean DOM element targeting across browsers.
**Action:** Always pass `this` or explicit event targets from HTML inline handlers when modifying element classes dynamically.
