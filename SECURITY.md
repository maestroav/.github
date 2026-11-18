# Security Policy

## Reporting a vulnerability

**Do not open a public issue.** Use GitHub's private reporting instead:
**Security → Report a vulnerability** on the affected repository.

Please include the affected repo and version/commit, reproduction steps, and the impact you expect.

You can expect an acknowledgement within **3 business days** and a status update within **7 days**. We'll credit you in the fix release unless you'd rather stay anonymous.

## Supported versions

Only the latest deployed version of each product (the `main` branch) gets security fixes.

## Baseline practices in every repo

- Dependabot alerts and updates enabled
- Secret scanning and push protection where the plan allows
- Secrets only in the hosting platform or GitHub Actions secrets, never in code
- Least‑privilege `permissions:` on every workflow
