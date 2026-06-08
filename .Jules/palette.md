## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.
## 2024-06-08 - Table Empty States in Dashboard
**Learning:** This app frequently renders tables via EJS (e.g., `merchants.ejs`). When data is empty, it left a blank header-only table which looks broken.
**Action:** Always wrap `<tbody>` logic in an `if/else` block and provide a friendly `colspan` empty state message to guide the user (e.g., "Belum ada data...").
