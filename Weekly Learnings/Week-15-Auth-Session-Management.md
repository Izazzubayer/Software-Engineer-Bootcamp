# Week 15 — Authentication & Session Management

**Theme:** Full-Stack Integration  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Session vs token (JWT) strategies
- Login/logout flow in the frontend
- Protected routes in the frontend (redirect if not logged in)
- Token storage: localStorage vs cookies (pros/cons)
- Refresh tokens (optional) and “remember me”
- OAuth 2.0 basics (e.g. “Login with Google”)

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| Passport.js | [Official Guide](http://www.passportjs.org/docs/) | Strategies |
| Auth0 | [Authentication guides](https://auth0.com/docs) | OAuth/JWT |
| Web Dev Simplified | [Session vs JWT](https://www.youtube.com/watch?v=UBUNrFtufWo) | Comparison |
| Traversy Media | [Passport.js Authentication](https://www.youtube.com/watch?v=6FOq4cUdH8k) | Implementation |

---

## Practice

- [ ] Implement full login/logout in your full-stack app
- [ ] Protected routes: check token/session before rendering; redirect to login
- [ ] Optional: store token in httpOnly cookie (backend sets it)
- [ ] Optional: refresh token or “remember me” (longer-lived token)
- [ ] Optional: add “Login with Google” (Passport + Google OAuth or Auth0/Clerk)

---

## What to focus on

- **Sessions:** server stores session; cookie with session ID; server-side logout
- **JWT:** stateless; client stores token; expiry and refresh strategy
- **Frontend guard:** on app load and route change, check auth; redirect or show content
- **Security:** XSS (don’t put sensitive data in localStorage if XSS risk); CSRF for cookies

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Session vs JWT + Passport tutorials | 3–4 |
| Protected routes + logout flow | 4–5 |
| Token storage and optional refresh | 2–3 |
| Optional OAuth (Google) | 2–4 |

---

## Checklist

- [ ] Login/logout and protected routes work end-to-end
- [ ] Understand tradeoffs of token vs session
- [ ] Ready for state management (Week 16)
