# Week 14 — Full-Stack Architecture

**Theme:** Full-Stack Integration  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Client–server architecture (frontend + backend)
- Connecting a frontend (e.g. React or vanilla) to Express API
- Proxy and CORS in development
- Environment variables for frontend (API URL)
- Build process and deployment considerations

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| freeCodeCamp | [Full Stack Development Tutorial](https://www.youtube.com/watch?v=nu_pCVPKzTk) | Overview |
| The Odin Project | Full Stack JavaScript path | Structure |
| Web.dev | [Progressive Web Apps](https://web.dev/progressive-web-apps/) | Optional |
| Traversy Media | [MERN Stack Crash Course](https://www.youtube.com/watch?v=7CqJlxBYj-M) | MERN |
| freeCodeCamp | [Full Stack App Tutorial](https://www.youtube.com/watch?v=98BzS5Oz5E4) | Full build |

---

## Practice

- [ ] Create a simple React (or vanilla) app that calls your Task API
- [ ] Configure proxy (Vite/ CRA) or CORS so frontend can hit backend in dev
- [ ] Use env vars for API base URL (e.g. `VITE_API_URL`)
- [ ] Implement: login form → get token → call protected endpoint with token

---

## What to focus on

- **Separation:** frontend (UI, state) vs backend (API, DB); communicate via HTTP/JSON
- **CORS:** browser blocks cross-origin requests unless server sends CORS headers
- **Auth flow:** login → store token (e.g. localStorage or cookie) → send `Authorization: Bearer <token>`
- **Dev vs prod:** different API URLs; build frontend for production (static files or deploy separately)

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Full-stack tutorials | 3–4 |
| Connect frontend to Task API | 5–6 |
| Auth flow end-to-end | 3–4 |
| Read on session vs JWT (prep Week 15) | 1–2 |

---

## Checklist

- [ ] Frontend successfully calls backend and uses auth token
- [ ] CORS/proxy understood and working
- [ ] Ready for session/token strategies (Week 15)
