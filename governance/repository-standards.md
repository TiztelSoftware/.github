# Repository Standards

Every delivery repository must have:

- A defined purpose and accountable owner
- A private visibility classification unless public release is explicitly approved
- `main` as the default branch
- A pull request requirement for `main`
- Required conversation resolution
- Required validation checks
- Blocked branch deletion and force pushes
- No standing bypass for agents
- `AGENTS.md`, contribution guidance, a security policy, and a pull request template
- Specifications and architecture decisions stored with the source
- Least privilege GitHub Actions permissions

Direct pushes to `main`, unreviewed production changes, repository secrets in files, and undocumented exceptions are prohibited.
