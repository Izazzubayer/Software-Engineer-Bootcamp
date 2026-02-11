# Week 28 — CI/CD & Automation

**Theme:** Deployment & DevOps  
**Suggested time:** 12–16 hours total

---

## Learning goals

- CI: run tests on every push/PR
- CD: deploy on merge to main (or tag)
- GitHub Actions: workflow, jobs, steps
- Secrets in CI (e.g. API keys for deploy)
- Deployment strategies (blue-green, canary) — concept
- Basic monitoring/error tracking (e.g. Sentry)

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| GitHub Actions | [Quickstart](https://docs.github.com/en/actions/quickstart) | Official |
| GitLab CI/CD | [Tutorial](https://docs.gitlab.com/ee/ci/) | Alternative |
| freeCodeCamp | [GitHub Actions Tutorial](https://www.youtube.com/watch?v=R8_veQiYBjI) | Video |
| TechWorld with Nana | [CI/CD Pipeline](https://www.youtube.com/watch?v=scEDHsr3APg) | Concepts |

---

## Practice

- [ ] GitHub Actions: run tests on push (e.g. npm test for frontend and/or backend)
- [ ] Add deploy step: on push to main, build and deploy to Vercel/Render (use their actions or deploy script)
- [ ] Store secrets in GitHub Secrets; use in workflow
- [ ] Optional: Sentry (or similar) for error tracking; add to one app

---

## Project: Deploy All Previous Projects

- [ ] CI/CD for portfolio (test + deploy)
- [ ] Containerize full-stack app (Week 27); optional deploy with Docker
- [ ] One production deploy with custom domain
- [ ] Monitoring/errors and deployment doc in README

---

## What to focus on

- **CI:** fast feedback; fail PR if tests fail
- **CD:** automate deploy; same build artifact as tested
- **Secrets:** never log or commit; use GitHub Secrets / platform env
- **Rollback:** know how to revert deploy (e.g. redeploy previous commit)

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| GitHub Actions tutorials | 3–4 |
| Add test + deploy workflow | 4–5 |
| Deploy previous projects + docs | 4–7 |

---

## Checklist

- [ ] At least one repo has CI (tests) and CD (deploy) on push
- [ ] Secrets used correctly in Actions
- [ ] Ready for React Native (Week 29)
