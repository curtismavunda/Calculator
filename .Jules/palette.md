## 2026-06-18 - [Fix display bug and improve accessibility]
**Learning:** Simple JavaScript calculators without state guards can leak 'undefined' or 'NaN' into the UI if operators are skipped.
**Action:** Implement guard clauses in calculation functions to ensure all necessary operands and operators are present before updating the display.
