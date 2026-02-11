# Week 16 — State Management & Advanced Frontend

**Theme:** Full-Stack Integration  
**Suggested time:** 12–16 hours total

---

## Learning goals

- When to use local vs global state
- React Context API for global state
- Redux Toolkit basics (store, slices, useDispatch, useSelector)
- Async actions (e.g. Redux Thunk)
- Form handling and validation (Formik or React Hook Form)
- Optimizing re-renders

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| React | [Context API](https://react.dev/learn/passing-data-deeply-with-context) | Official |
| Redux Toolkit | [Getting Started](https://redux-toolkit.js.org/introduction/getting-started) | Modern Redux |
| Net Ninja | [React Context & Hooks](https://www.youtube.com/playlist?list=PL4cUxeGkcC9hNokByJilPg5g9m2APUePI) | Context |
| Codevolution | [Redux Tutorial](https://www.youtube.com/playlist?list=PLC3y8-rFHvwheJHvseC3I0HuYI2f46oAK) | Redux |

---

## Practice

- [ ] Add Context for theme or user (e.g. auth state) in your app
- [ ] Optional: Redux Toolkit — store, one slice, fetch data with createAsyncThunk
- [ ] Form with validation (e.g. React Hook Form + zod or manual)
- [ ] Identify unnecessary re-renders (React DevTools); use memo/useCallback where it helps

---

## What to focus on

- **Local state:** component-only; useState/useReducer
- **Global state:** many components need it → Context or Redux; Context for simple, Redux for complex/async
- **Forms:** controlled inputs, validation on submit or on blur; use a library to reduce boilerplate
- **Performance:** avoid putting frequently changing data in global state if only one subtree needs it

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Context + Redux tutorials | 4–5 |
| Add Context/Redux to your app | 3–4 |
| Forms and validation | 3–4 |
| Prep for Agile/Git (Week 17) | 2–3 |

---

## Checklist

- [ ] Used Context (or Redux) for at least one global concern
- [ ] Implemented a form with validation
- [ ] Ready for Agile & collaboration (Week 17)
