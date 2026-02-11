# Week 11 — MongoDB & Database (Part 1)

**Theme:** Back-End Development  
**Suggested time:** 12–16 hours total

---

## Learning goals

- MongoDB basics: documents, collections, databases
- MongoDB Atlas (cloud) setup — free tier
- CRUD in MongoDB (shell or Compass)
- Mongoose: connection, Schema, Model
- Basic validation in schemas

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| MongoDB University | [M001: MongoDB Basics](https://university.mongodb.com/courses/M001/about) | Free cert |
| freeCodeCamp | MongoDB tutorial | Quick start |
| Mongoose | [Getting Started](https://mongoosejs.com/docs/index.html) | ODM |
| Traversy Media | [MongoDB Crash Course](https://www.youtube.com/watch?v=ofme2o29ngU) | Overview |
| Net Ninja | [MongoDB Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9h77dJ-QJlwGlZlTd4ecZOA) | Playlist |

---

## Practice

- [ ] Create Atlas cluster, get connection string, connect from Node
- [ ] Define a Mongoose schema (e.g. User, Post) with types and `required`
- [ ] Implement CRUD with Mongoose (create, find, findById, updateOne, deleteOne)
- [ ] Connect your Week 9/10 API to MongoDB instead of in-memory data

---

## What to focus on

- **Document model:** JSON-like documents; no fixed schema (schema in Mongoose for app)
- **Mongoose:** Schema → Model; `new Model()`, `Model.save()`, `Model.find()`, etc.
- **Connection:** `mongoose.connect(uri)`; use env for URI
- **Validation:** required, type, min/max; custom validators later

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| MongoDB + Atlas + Mongoose tutorials | 4–5 |
| Schema design + CRUD in Node | 4–5 |
| Wire API to MongoDB | 3–4 |
| MongoDB University (optional) | 2 |

---

## Checklist

- [ ] Atlas cluster created and connected from Node
- [ ] One or more Mongoose models with validation
- [ ] API persists data in MongoDB
- [ ] Continue with relations and queries (Week 12)
