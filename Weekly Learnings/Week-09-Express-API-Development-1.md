# Week 9 — Express.js & API Development (Part 1)

**Theme:** Back-End Development  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Express app setup and routing
- Route parameters and query strings
- Middleware (built-in and custom)
- Request and response objects
- RESTful design (resources, HTTP methods)
- Postman (or Thunder Client) for testing

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| Express.js | [Getting Started](https://expressjs.com/en/starter/installing.html) | Official |
| freeCodeCamp | Express section in Backend course | Practice |
| MDN | [Express web framework](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs) | Context |
| Traversy Media | [Express JS Crash Course](https://www.youtube.com/watch?v=L72fhGm1tfE) | Full app |
| Web Dev Simplified | [REST API with Node.js](https://www.youtube.com/watch?v=fgTGADljAeg) | API focus |

---

## Practice projects

- [ ] Simple REST API for a blog (get posts, get one post, create post)
- [ ] CRUD for a book library (Create, Read, Update, Delete)
- [ ] User management API (list users, get user, add user)

---

## What to focus on

- **Routing:** `app.get`, `app.post`, `app.put`, `app.delete`; `:id` params
- **Middleware:** `express.json()`, `express.static`; custom middleware with `next()`
- **req/res:** `req.body`, `req.params`, `req.query`, `res.status()`, `res.json()`
- **REST:** URLs as resources, HTTP methods as actions; status codes (200, 201, 400, 404, 500)

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Express tutorials | 4–5 |
| Blog or library API | 4–5 |
| Postman/Thunder Client testing | 2–3 |
| Error-handling middleware | 2–3 |

---

## Checklist

- [ ] Built at least one CRUD API with Express
- [ ] Used middleware and route params
- [ ] Tested all routes with Postman/Thunder Client
- [ ] Continue API design and DB next (Week 10)
