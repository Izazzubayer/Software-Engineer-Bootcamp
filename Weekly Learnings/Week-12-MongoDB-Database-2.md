# Week 12 — MongoDB & Database (Part 2)

**Theme:** Back-End Development  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Relationships: embedding vs referencing
- Mongoose `populate()` (references)
- Indexes for performance (basics)
- Aggregation pipeline intro
- Query patterns and simple optimization

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| Mongoose | [Population](https://mongoosejs.com/docs/populate.html) | Joins |
| MongoDB University | M001 or aggregation docs | Aggregation |
| Web Dev Simplified | [Mongoose Crash Course](https://www.youtube.com/watch?v=DZBGEVgL2eE) | Patterns |

---

## Practice

- [ ] Two related models (e.g. User has many Posts); use `ref` and `populate()`
- [ ] Add an index on a frequently queried field
- [ ] One aggregation (e.g. count by category, simple group)
- [ ] Extend your API: filtered list, pagination (limit/skip or cursor)

---

## What to focus on

- **When to embed vs reference:** one-to-few and small docs → embed; many or shared → reference
- **populate:** replace ID with full document(s); avoid N+1 (populate in one query)
- **Indexes:** speed up find/sort; default `_id`; add for fields you filter/sort on
- **Pagination:** limit + skip or cursor-based for large sets

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Relations + populate | 3–4 |
| Aggregation + indexes | 2–3 |
| API with relations and filters | 4–5 |
| Prep for auth (read JWT/bcrypt intro) | 2–3 |

---

## Checklist

- [ ] Used `populate()` for at least one relationship
- [ ] Understood embed vs reference tradeoffs
- [ ] API supports filtering or pagination
- [ ] Ready for Security & Authentication (Week 13)
