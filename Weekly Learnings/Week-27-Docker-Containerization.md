# Week 27 — Docker & Containerization

**Theme:** Deployment & DevOps  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Containers vs VMs (concept)
- Dockerfile: FROM, WORKDIR, COPY, RUN, CMD, EXPOSE
- Build and run a Node app in a container
- Docker Compose: multi-container app (app + DB or app + frontend)
- Volumes for persistence
- Multi-stage builds (optional)

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| Docker | [Get Started](https://docs.docker.com/get-started/) | Official |
| Play with Docker | [Interactive Tutorial](https://www.docker.com/play-with-docker/) | Hands-on |
| TechWorld with Nana | [Docker Tutorial](https://www.youtube.com/watch?v=3c-iBn73dDE) | Thorough |
| Traversy Media | [Docker Crash Course](https://www.youtube.com/watch?v=pTFZFxd4hOI) | Quick |
| freeCodeCamp | [Docker Compose](https://www.youtube.com/watch?v=DM65_JyGxCo) | Compose |

---

## Practice

- [ ] Write Dockerfile for your Node/Express API; build image, run container, test
- [ ] Docker Compose: API + MongoDB (or use Atlas and just API container)
- [ ] Volume: persist MongoDB data or uploads (if local DB)
- [ ] Optional: multi-stage build to reduce image size

---

## What to focus on

- **Image vs container:** image = blueprint; container = running instance
- **Dockerfile:** base image (node:alpine), copy app, install deps, expose port, CMD
- **Compose:** define services (api, db); networks; env; depends_on
- **.dockerignore:** exclude node_modules, .env, .git to speed build and reduce size

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Docker + Dockerfile tutorials | 4–5 |
| Containerize your API | 3–4 |
| Docker Compose setup | 3–4 |
| Optional: deploy container (Railway/Render support Docker) | 2–3 |

---

## Checklist

- [ ] API runs in Docker; Docker Compose runs app (and optional DB)
- [ ] Understand image/container and basic Dockerfile
- [ ] Ready for CI/CD (Week 28)
