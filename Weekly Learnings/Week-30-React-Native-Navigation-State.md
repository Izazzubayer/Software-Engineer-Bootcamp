# Week 30 — React Native Navigation & State

**Theme:** Mobile Development (React Native)  
**Suggested time:** 12–16 hours total

---

## Learning goals

- React Navigation: Stack, Tab, Drawer
- Stack Navigator: push, pop, params
- Tab Navigator: bottom or top tabs
- Passing data between screens (params, context)
- Deep linking (optional)
- Auth flow in navigation (e.g. switch stack when logged in)

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| React Navigation | [Getting Started](https://reactnavigation.org/docs/getting-started) | Official |
| Redux Toolkit | [React Native](https://redux-toolkit.js.org/) | If using Redux |
| Codevolution | [React Navigation v6](https://www.youtube.com/playlist?list=PLC3y8-rFHvwh6vGhZFOkwewmM_8QJTJog) | Video |
| Net Ninja | [React Native Navigation](https://www.youtube.com/playlist?list=PL4cUxeGkcC9ixPU-QkScoRBVxtPPzVjrQ) | Playlist |

---

## Practice

- [ ] Stack: 2–3 screens; navigate with params; back button
- [ ] Tab Navigator: Home, Profile, Settings (or similar)
- [ ] Optional: Drawer for menu
- [ ] Pass data: screen A → screen B (params); optional Context for shared state
- [ ] Auth: show Auth stack when logged out, Main stack when logged in

---

## What to focus on

- **Stack:** one stack per flow; push/pop; pass object as params
- **Tabs:** persistent tabs; good for main sections
- **Nesting:** e.g. tabs with stack inside each tab
- **Screen lifecycle:** focus/blur; useFocusEffect for refetch on focus

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| React Navigation tutorials | 3–4 |
| Stack + Tabs in your app | 4–5 |
| Params + auth flow | 3–4 |
| Optional: Redux or Context for app state | 2–3 |

---

## Checklist

- [ ] App has Stack and Tab navigation
- [ ] Data passed between screens; optional auth-based stacks
- [ ] Ready for Native Features (Week 31)
