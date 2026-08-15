# Security Baseline

Every repository must:

- Remain private unless public release is explicitly approved
- Enable the dependency graph and available Dependabot security updates
- Use secret scanning and push protection when the GitHub plan supports them
- Use least privilege workflow permissions
- Pin reusable workflows to reviewed commit SHAs for production use
- Store credentials only in approved secret stores
- Prohibit production personal information and client data in test fixtures
- Protect `main` with required pull requests and validation
- Record security exceptions with an owner, reason, scope, and expiration

Security alerts must be triaged by impact and exposure. A passing build does not override an unresolved critical security finding.
