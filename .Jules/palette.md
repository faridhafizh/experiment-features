## 2024-05-15 - Explicit Form Labels and Feedback
**Learning:** Auth forms often lack basic a11y scaffolding. Implicitly associating labels isn't enough; explicit `for`/`id` linking improves screen reader reliability, and visual required indicators combined with submit button loading states reduce user friction significantly.
**Action:** When auditing forms, check for explicit label associations, clear required field indicators, and immediate feedback on form submission to prevent double-clicks.

## 2024-05-17 - Avoid Intrusive Alerts for Background Tasks
**Learning:** Polling functions or repeated background fetches that use `alert()` aggressively disrupt the user experience by blocking the UI completely.
**Action:** Replace browser alerts with subtle, non-blocking UI state changes, such as disabling buttons and showing "Loading..." / "Memuat..." text, then restoring them when the task is complete.
