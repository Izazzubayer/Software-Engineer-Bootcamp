# Week 24 — React Router & Forms

**Theme:** Modern Front-End (React)  
**Suggested time:** 12–16 hours total

---

## Learning goals

- React Router: Routes, Route, Link, useNavigate, useParams
- Nested routes and layouts
- Protected routes (redirect if not authenticated)
- Form state: controlled vs uncontrolled
- Validation (client-side) and submission
- File upload UI (optional)

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| React Router | [Tutorial](https://reactrouter.com/en/main/start/tutorial) | v6 |
| React Hook Form | [Get Started](https://react-hook-form.com/get-started) | Forms |
| Web Dev Simplified | [React Router v6](https://www.youtube.com/watch?v=Ul3y1LXxzdU) | Video |
| Codevolution | [React Forms](https://www.youtube.com/playlist?list=PLC3y8-rFHvwiPmFbtzEWjESkqBVDbdgGu) | Forms |

---

## Practice

- [ ] Multi-page app: Home, About, Dashboard; shared layout (navbar/footer)
- [ ] Dynamic route: e.g. `/post/:id`; useParams to load post
- [ ] Protected route: wrapper component that checks auth and redirects to login
- [ ] Form with React Hook Form (or Formik): validation, submit, error messages
- [ ] Optional: file input; preview; send as FormData to API

---

## What to focus on

- **Declarative routing:** Route components and path; Link for navigation
- **URL params:** useParams(); useSearchParams() for query string
- **Programmatic nav:** useNavigate() after login or submit
- **Forms:** controlled = value + onChange; use a library for validation and DX
- **Validation:** on submit and/or on blur; show errors next to fields

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| React Router tutorial + practice | 3–4 |
| Nested + protected routes | 2–3 |
| Forms with validation | 4–5 |
| Integrate into your app | 3–4 |

---

## Checklist

- [ ] App has multiple routes and at least one protected route
- [ ] Form with validation and submit handling
- [ ] Ready for Testing & Build (Week 25)
