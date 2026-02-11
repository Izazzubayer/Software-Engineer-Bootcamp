# Week 31 — React Native: Native Features & APIs

**Theme:** Mobile Development (React Native)  
**Suggested time:** 12–16 hours total

---

## Learning goals

- Camera (Expo Camera or expo-image-picker)
- Location (Expo Location): get current position, permissions
- AsyncStorage for local persistence
- Push notifications (Expo: setup and receive)
- File system (Expo FileSystem) — optional
- Permissions and error handling

---

## Study resources

| Resource | Link | Notes |
|----------|------|--------|
| Expo SDK | [API Reference](https://docs.expo.dev/versions/latest/) | All APIs |
| React Native Directory | [Packages](https://reactnative.directory/) | Find libraries |
| Programming with Mosh | [React Native APIs](https://www.youtube.com/watch?v=0-S5a0eXPoc) | Overview |
| Expo Camera | [Tutorial](https://www.youtube.com/watch?v=qvqjv_Qz3GY) | Camera |

---

## Practice

- [ ] Camera or image picker: take/select photo; display or upload
- [ ] Location: request permission; get current position; show on screen or map (optional)
- [ ] AsyncStorage: save user prefs or draft; load on app open
- [ ] Push: Expo push notification; get token and send test notification
- [ ] Handle permission denied and errors gracefully

---

## What to focus on

- **Permissions:** request at runtime; explain why (for store compliance); handle “denied”
- **AsyncStorage:** key-value; async; use for small data (token, theme, draft)
- **Background:** avoid long tasks on main thread; use appropriate APIs for background tasks
- **Native modules:** Expo abstracts many; for bare RN you may need linking

---

## Weekly time split (12–16 hrs)

| Activity | Hours |
|----------|--------|
| Camera + Location tutorials | 3–4 |
| Implement 2–3 native features in app | 5–6 |
| AsyncStorage + optional push | 2–3 |
| Permissions and error handling | 2–3 |

---

## Checklist

- [ ] Used camera or image picker and location (or two other native APIs)
- [ ] AsyncStorage for persistence
- [ ] Ready for Accessibility & Distribution (Week 32)
