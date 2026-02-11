# Week 26 — Deployment Fundamentals

**Theme:** Deployment & DevOps  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Static vs dynamic hosting
- Deploy frontend (Vercel, Netlify)
- Deploy backend (Render, Railway)
- Environment variables in production
- Custom domain and SSL (optional)
- Database hosting (e.g. MongoDB Atlas already used)
- API rate limiting (concept)

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| freeCodeCamp | [DevOps Handbook](https://www.freecodecamp.org/news/tag/devops/) | Articles |
| Vercel | [Deployment Guide](https://vercel.com/docs) | Frontend |
| Netlify | [Get Started](https://docs.netlify.com/) | Frontend |
| Traversy Media | [Deploy React App](https://www.youtube.com/watch?v=l134cBAJCuc) | Video |
| Web Dev Simplified | [Full Stack Deployment](https://www.youtube.com/watch?v=JEBkh_vEQ) | Full stack |

---

## Practice

- [ ] Deploy a React/Vite app to Vercel or Netlify (connect GitHub, auto deploy)
- [ ] Deploy Node/Express API to Render or Railway; set env vars
- [ ] Ensure frontend calls correct API URL in production (env)
- [ ] Optional: custom domain, SSL; verify MongoDB Atlas IP/access for production

---

## What to focus on

- **Static:** frontend build → CDN; serverless for API
- **Env:** never commit secrets; set in platform (Vercel/Render) for each env
- **Build:** frontend `npm run build`; backend may need start script and Node version
- **CORS:** if frontend and API different origins, backend must allow frontend origin

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Deployment tutorials | 3–4 |
| Deploy frontend + backend | 4–5 |
| Fix env/CORS/build issues | 2–3 |
| Optional: domain + SSL | 2–4 |

---

## Checklist

- [ ] At least one app (frontend + API) live in production
- [ ] Env vars set on hosting; no secrets in repo
- [ ] Ready for Docker (Week 27)
