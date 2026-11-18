<div align="center">

# maestroav

**A studio for fast‑paced micro‑SaaS.**
Small products, shipped quickly, kept only if they earn it.

</div>

---

### What happens here

Every idea gets the same loop:

```
idea  →  validate  →  build MVP  →  launch  →  measure  →  keep / kill
```

- **Small bets.** Each product is scoped to one painful problem and one clear buyer.
- **Ship in days, not months.** Projects start from a shared template, so the first deploy happens on day one.
- **Measure, then decide.** A product earns more time only if users and revenue show up. Otherwise it is archived, and what we learned moves to the next one.

### How we build

- One repo per product, created from [`micro-saas-template`](https://github.com/maestroav/micro-saas-template)
- Trunk-based: short-lived branches, small PRs, `main` always deployable
- Conventional Commits, automated checks on every PR, Dependabot on
- Secrets live in the platform, never in the repo

### Status board

| Stage | Meaning |
|---|---|
| 🧪 `idea` | Being validated, no code yet |
| 🛠 `building` | MVP in progress |
| 🚀 `live` | Launched and measuring |
| 📦 `archived` | Stopped; learnings kept |

Repos are tagged with these as GitHub topics (`stage-idea`, `stage-building`, `stage-live`, `stage-archived`).

---

<sub>Most work here is private. Reach out via the owner’s GitHub profile: [@vrahmanov](https://github.com/vrahmanov).</sub>
