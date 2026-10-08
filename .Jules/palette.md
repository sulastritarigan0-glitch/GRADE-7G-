# Palette's Journal - Critical Learnings

## 2025-10-08 - Accessible Form Controls and Navigation ARIA
**Learning:** Vanilla HTML/JS web pages often lack explicit `for` attributes connecting `<label>` elements to form controls (`<input>`, `<select>`, `<textarea>`), breaking screen reader usability and click-to-focus behavior. Additionally, single-page tab navigation requires updating `aria-current="page"` alongside visual `.active` classes so assistive technology accurately communicates the current section.
**Action:** Always link form labels to control IDs using `for="..."` and synchronize `aria-current="page"` state when managing tab navigation via JS.
