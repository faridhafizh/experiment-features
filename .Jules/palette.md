## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2026-05-17 - Passive Auto-Refresh Indication
**Learning:** Using `alert()` or blocking UI for background data refreshes severely interrupts user workflow. Passive visual indicators (like "Last updated" timestamps) are much better for recurrent background fetching.
**Action:** Always use non-blocking text updates (e.g. inline timestamps or subtle toast notifications) to inform users of automated background activity.
