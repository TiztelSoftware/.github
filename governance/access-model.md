# Access Model

## Organization owners

Owners manage billing, organization settings, emergency recovery, and final production authority. Keep the owner group small and require strong multifactor authentication.

## Platform maintainers

Platform maintainers manage shared templates and CI components through pull requests. Administrative access is granted only when required.

## Repository maintainers

Maintainers manage assigned repositories, triage work, review changes, and operate releases within approved boundaries.

## Contributors

Contributors receive the minimum repository role needed for assigned work.

## Agents and applications

Agents use installed GitHub applications or dedicated service identities with narrow permissions. Agents receive no organization owner role, no standing production credentials, and no ruleset bypass.

Access must be removed when its purpose ends. Permission changes require an auditable human decision.
