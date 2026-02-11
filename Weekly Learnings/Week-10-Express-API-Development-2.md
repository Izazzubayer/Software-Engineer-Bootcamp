# Week 10 — Express.js & API Development (Part 2)

**Theme:** Back-End Development  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Error-handling middleware (centralized)
- RESTful design refinement
- File upload (e.g. multer) — optional
- Environment variables (dotenv)
- Structuring a small API project (routes, controllers)

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| Express.js | [Error handling](https://expressjs.com/en/guide/error-handling.html) | Official |
| Programming with Mosh | [Build REST API](https://www.youtube.com/watch?v=pKd0Rpw7O48) | Full build |
| MDN | Express section | Patterns |

---

## Practice projects

- [ ] Add error-handling middleware to Week 9 API
- [ ] Split routes into separate files (e.g. `routes/books.js`)
- [ ] Use `dotenv` for port and config
- [ ] Optional: file upload endpoint (e.g. image)

---

## What to focus on

- **Error middleware:** 4-arg function `(err, req, res, next)`; call `next(err)` from routes
- **Status codes:** 400 bad request, 404 not found, 500 server error
- **Project structure:** `app.js` or `index.js`, `routes/`, `controllers/` or logic in routes
- **.env:** `process.env.PORT`; add `.env` to `.gitignore`

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Error handling + structure | 3–4 |
| Refactor Week 9 API | 3–4 |
| Optional file upload | 2–3 |
| Prep for MongoDB (read Mongoose intro) | 2–3 |
| Start easy LeetCode (optional) | 2 |

---

## Checklist

- [ ] API has centralized error handling and clear structure
- [ ] Using environment variables for config
- [ ] Ready for MongoDB (Week 11)
