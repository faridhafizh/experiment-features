## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2026-05-18 - Custom Dropdown Keyboard Interactions and Accessibility
**Learning:** Custom dropdowns (like notification menus) often lack native keyboard interactions and accessibility attributes. Setting `aria-expanded` and `aria-haspopup` on the toggle button helps screen readers, and adding `Escape` key handlers and "click outside" listeners significantly improves keyboard and mouse usability.
**Action:** Always ensure custom dropdowns or modals have click-outside and Escape-key handlers to close them, and verify that the trigger button dynamically updates `aria-expanded` based on visibility.
