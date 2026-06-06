## 2026-05-16 - Improved PJP Dashboard Empty State
**Learning:** Replaced a simple text empty state with an engaging UI block including an icon and call-to-action button, successfully improving the visual guidance for first-time users without adding any new CSS classes.
**Action:** When adding empty states, always consider adding an actionable button and a visual icon using existing utilities to guide users.
## 2024-06-06 - Safe inline form submission loading state
**Learning:** Adding `onsubmit` inline handlers for loading states is effective but must account for buttons without an explicit `type="submit"` attribute (e.g., using `|| this.querySelector("button")`) to avoid `TypeError: Cannot set properties of null (setting "disabled")` if the `submit` selector fails.
**Action:** Always use a safe selector fallback (`if(btn) { btn.disabled = true; }`) for inline submit loading states.
