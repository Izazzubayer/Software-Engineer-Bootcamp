# Week 13 — Security & Authentication

**Theme:** Back-End Development  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Password hashing (bcrypt) and salting
- JWT: create and verify tokens
- Protected routes (middleware)
- OWASP Top 10 awareness
- Input validation and sanitization
- Environment variables for secrets

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| OWASP | [Top 10 Web Application Security Risks](https://owasp.org/www-project-top-ten/) | Awareness |
| Auth0 | [Authentication concepts](https://auth0.com/docs/get-started/authentication-and-authorization) | Concepts |
| JWT.io | [Introduction to JWT](https://jwt.io/introduction) | JWT explained |
| Web Dev Simplified | [User Authentication](https://www.youtube.com/watch?v=Ud5xKCYQTjM) | Full flow |
| Net Ninja | [JWT Tutorial](https://www.youtube.com/watch?v=mbsmsi7l3r4) | Implementation |
| Fireship | [Node.js Security Best Practices](https://www.youtube.com/watch?v=f2EqECiTBL8) | Short |

---

## Practice

- [ ] User registration: hash password with bcrypt, save user
- [ ] Login: verify password, sign JWT, return token
- [ ] Auth middleware: verify JWT, attach user to `req`, reject if invalid
- [ ] Protected routes: only allow access with valid token
- [ ] Basic input validation (e.g. express-validator or manual)

---

## Project 3: Task Management API

Build a RESTful API with:

- [ ] User auth (register, login, logout)
- [ ] CRUD for tasks (categories/tags optional)
- [ ] User-specific data (users only see their tasks)
- [ ] Search/filter
- [ ] Error handling and validation
- [ ] MongoDB + Mongoose
- [ ] API documentation (README or Postman collection)

---

## What to focus on

- **Passwords:** never store plain text; bcrypt with salt; compare with `bcrypt.compare`
- **JWT:** sign with secret (in env); verify on each protected request; expiry
- **Middleware:** decode JWT → attach user → next() or 401
- **Security:** HTTPS, secure headers (helmet), validation, no secrets in code

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Auth tutorials + OWASP skim | 4–5 |
| Auth implementation | 4–5 |
| Task Management API | 4–6 |

---

## Checklist

- [ ] Registration and login with JWT working
- [ ] Protected routes implemented
- [ ] Task API with user-scoped data and validation
- [ ] Ready for Full-Stack (Week 14)
