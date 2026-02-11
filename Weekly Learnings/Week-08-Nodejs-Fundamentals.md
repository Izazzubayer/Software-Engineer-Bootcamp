# Week 8 — Node.js Fundamentals

**Theme:** Back-End Development  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Node.js runtime and npm
- CommonJS vs ES Modules
- File system (fs) basics
- Simple HTTP server without a framework
- Environment setup and package.json

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| freeCodeCamp | [Backend Development and APIs](https://www.freecodecamp.org/learn/back-end-development-and-apis/) | Path |
| Node.js | [Getting Started Guide](https://nodejs.org/en/docs/guides/getting-started-guide/) | Official |
| The Odin Project | [NodeJS Course](https://www.theodinproject.com/paths/full-stack-javascript/courses/nodejs) | Structured |
| Programming with Mosh | [Node.js Tutorial](https://www.youtube.com/watch?v=TlB_eWDSMt4) | ~1 hr |
| Traversy Media | [Node.js Crash Course](https://www.youtube.com/watch?v=fBNz5xF-Kac) | Practical |

---

## Practice

- [ ] Install Node, create a project with `npm init`
- [ ] Use `require` vs `import`/`export` (CommonJS vs ESM)
- [ ] Read/write files with `fs` (sync and async)
- [ ] Create a minimal HTTP server with `http` module (respond with “Hello”)
- [ ] Use nodemon for auto-restart in development

---

## What to focus on

- **Runtime:** Node = V8 + APIs (no browser DOM); run with `node script.js`
- **Modules:** `module.exports` / `require` vs `export` / `import`; `"type": "module"` in package.json
- **package.json:** dependencies, scripts (`"start"`, `"dev"`), semver
- **PATH and env:** where Node is installed; using `.env` later

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Node tutorials + docs | 4–5 |
| File and HTTP exercises | 4–5 |
| Small CLI or server script | 4–6 |

---

## Checklist

- [ ] Can create a Node project and run it
- [ ] Understand module systems and package.json
- [ ] Built a minimal HTTP server
- [ ] Ready for Express (Week 9)
