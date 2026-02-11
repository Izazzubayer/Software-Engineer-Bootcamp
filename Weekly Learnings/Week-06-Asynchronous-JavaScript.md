# Week 6 — Asynchronous JavaScript

**Theme:** JavaScript Fundamentals  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Callbacks vs Promises vs async/await
- Promise chaining and error handling
- Event loop (basic mental model)
- `setTimeout`, `setInterval`
- Avoiding race conditions in async code

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| JavaScript.info | [Promises, async/await](https://javascript.info/async) | Core |
| MDN | [Asynchronous JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous) | Reference |
| Traversy Media | [Async JS Crash Course](https://www.youtube.com/watch?v=PoRJizFvM7s) | Overview |
| Web Dev Simplified | [JavaScript Promises](https://www.youtube.com/watch?v=DHvZLI7Db8E) | Promises |
| Fireship | [Async/Await](https://www.youtube.com/watch?v=vn3tm0quoqE) | Short |

---

## Practice

- [ ] Callbacks: pass a function that runs after a delay
- [ ] Promises: create a Promise, `.then` / `.catch`, chain multiple
- [ ] Async/await: convert a promise chain to async/await; use try/catch
- [ ] Combine: fetch something (e.g. API), handle loading and errors

---

## What to focus on

- **Event loop:** JS is single-threaded; async callbacks run after sync code
- **When to use what:** callbacks (legacy/APIs), Promises (built-in APIs), async/await (readable flow)
- **Error handling:** `.catch` vs try/catch with async/await; don’t leave promises unhandled
- **Race conditions:** e.g. multiple fetches; use single “in-flight” request or abort

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Async tutorials | 4–5 |
| Promise/async exercises | 3–4 |
| Small async project (e.g. timer + fake API) | 4–7 |

---

## Checklist

- [ ] Can explain the event loop in simple terms
- [ ] Write async code with async/await and try/catch
- [ ] Chained promises and handled errors
- [ ] Ready for real APIs (Week 7)
