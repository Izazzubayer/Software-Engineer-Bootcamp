# Week 25 — React Testing & Build Tools

**Theme:** Modern Front-End (React)  
**Suggested time:** 12–16 hours total

---

## Learning goals

- React Testing Library: render, screen, userEvent
- Unit tests for components (behavior, not implementation)
- Mocking API calls (fetch or MSW)
- Integration test: form submit, navigation
- Vite (or CRA): dev server, build, env vars
- Code splitting and lazy loading (React.lazy, Suspense)
- Bundle size awareness

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| React Testing Library | [Intro](https://testing-library.com/docs/react-testing-library/intro/) | Official |
| Vitest | [Getting Started](https://vitest.dev/guide/) | Test runner |
| Jest | [Getting Started](https://jestjs.io/docs/getting-started) | Alternative |
| Codevolution | [React Testing](https://www.youtube.com/playlist?list=PLC3y8-rFHvwirqe1KHFCHJ0RqNuN61SJd) | RTL |
| Traversy Media | [Vite Crash Course](https://www.youtube.com/watch?v=LQQ3CR2JTX8) | Vite |

---

## Practice

- [ ] Set up Vitest (or Jest) with React Testing Library
- [ ] Test a presentational component (renders, userEvent click)
- [ ] Mock fetch; test component that loads data
- [ ] One integration test: fill form, submit, assert result or navigation
- [ ] Vite: create app, build, check bundle (optional: lazy load a route)
- [ ] Code coverage: aim for >80% on critical paths (optional)

---

## Project 6: Weather Forecast Application

Build a weather app with:

- [ ] Multi-location search
- [ ] 7-day and hourly forecast
- [ ] Optional: maps, geolocation, unit toggle (C/F), dark/light mode, favorites
- [ ] Tests for main flows (>80% coverage goal)
- [ ] Performance: lazy load routes or heavy components

---

## What to focus on

- **Test behavior:** what user sees and does; avoid testing implementation details
- **Queries:** getByRole, getByLabelText; avoid getByTestId when possible
- **Async:** waitFor, findBy; mock API with realistic delay
- **Build:** Vite fast; production build; env vars with VITE_ prefix

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| RTL + Vitest setup and tutorials | 3–4 |
| Write tests for existing components | 3–4 |
| Weather app (features + tests) | 5–8 |

---

## Checklist

- [ ] Wrote at least 5 component/integration tests
- [ ] Weather app built and tested
- [ ] Know how to build and run production bundle
- [ ] Ready for Deployment (Week 26)
