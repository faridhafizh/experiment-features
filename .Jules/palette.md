## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2026-05-17 - Centralized Focus States
**Learning:** Adding a global `:focus-visible` pseudo-class for common interactive elements (`.btn`, `a`, `button`) ensures keyboard users have a consistent and obvious visual indicator of focus across the entire application, which is crucial for accessibility.
**Action:** When working on accessibility, always ensure that a global focus state strategy is implemented and respected by all new interactive elements.
