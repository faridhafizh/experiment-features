## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.

## 2024-05-18 - Added Global Focus Visible Styles
**Learning:** Adding `:focus-visible` pseudo-class for `.btn, a, button, input, select, textarea` greatly improves keyboard navigation accessibility by providing a clear, central focus ring that is visible to keyboard users but hidden for mouse users.
**Action:** Consistently ensure that all interactive elements across the application have explicit `:focus-visible` styling to support users who navigate via keyboard.
