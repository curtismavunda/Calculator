## 2025-08-01 - Interactive Keyboard Mapping & Focus Highlight

**Learning:** Retrofitting physical and navigation keyboard listeners directly to legacy markup (`td`) requires precise propagation stopping (`e.stopPropagation()`) so global window shortcuts don't double-trigger keydowns. Using outline-offset with a custom `:focus-visible` ensures clean styling without shifting layout flows.

**Action:** Map physical/tab buttons using clear JS listeners, block event bubbling specifically on elements, and leverage `outline-offset` to contain indicators within adjacent borders.
