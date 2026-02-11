# Week 23 — Advanced Hooks & State (React)

**Theme:** Modern Front-End (React)  
**Suggested time:** 12–16 hours total

---

## Learning goals

- useContext for global state (theme, user, etc.)
- useReducer for complex state (multiple sub-values, transitions)
- useMemo and useCallback for optimization
- Custom hooks (e.g. useFetch, useLocalStorage)
- useRef for DOM access and mutable refs
- When to use each hook; avoiding unnecessary re-renders

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| React | [Hooks API Reference](https://react.dev/reference/react) | Official |
| Kent C. Dodds | [React patterns](https://kentcdodds.com/blog) | Best practices |
| Web Dev Simplified | [React Hooks](https://www.youtube.com/playlist?list=PLZlA0Gpn_vH8EtggFGERCwMY5u5hOjf-h) | Hooks |
| Codevolution | [useReducer](https://www.youtube.com/watch?v=cVYp4u1m6iA), [Custom Hooks](https://www.youtube.com/watch?v=dpw9EHDh2bM) | Deep dives |

---

## Practice

- [ ] Add a ThemeContext (dark/light) with useContext
- [ ] Convert a component with multiple useStates to useReducer (e.g. form or todo state)
- [ ] useMemo: expensive computation based on props/state
- [ ] useCallback: pass stable callback to child (e.g. list item handler)
- [ ] Custom hook: e.g. useFetch(url), useLocalStorage(key)
- [ ] useRef: focus an input; hold previous value or interval ID

---

## What to focus on

- **Context:** avoid putting everything in one context; split by domain (auth, theme)
- **useReducer:** state + action → new state; good for multi-step or complex updates
- **Optimization:** only when you measure; useMemo/useCallback for expensive or referential equality
- **Custom hooks:** reuse stateful logic; name with “use”

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Hooks tutorials | 3–4 |
| Context + useReducer in your app | 3–4 |
| Custom hooks + useRef | 2–3 |
| useMemo/useCallback where needed | 2–3 |
| Add TypeScript to React (optional start) | 2 |

---

## Checklist

- [ ] Used Context and useReducer in a real component
- [ ] Created at least one custom hook
- [ ] Know when to use useMemo/useCallback
- [ ] Ready for Router & Forms (Week 24)
