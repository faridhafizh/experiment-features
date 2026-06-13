## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2025-02-12 - Handling Empty Tables in Server-Rendered Views
**Learning:** For tables dynamically populated by server-side templates (like EJS), leaving a `<tbody>` completely empty when there's no data results in a jarring UX. Instead, conditionally rendering a full-width row (`<td colspan="X">`) with a friendly empty state message (e.g., "Belum ada data campaign...") provides clear feedback that the system is working but currently lacks content.
**Action:** Always wrap `<tbody>` content in an `if/else` block and provide a graceful `colspan` message when implementing data tables.
