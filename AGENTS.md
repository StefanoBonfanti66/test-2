# Agent rules

- Read PROJECT_AI_NOTES.md before doing major work.
- Prefer small diffs.
- Ask before touching secrets, .env, deployment, infra, auth, billing.
- Follow existing code style.
- Update PROJECT_AI_NOTES.md at meaningful checkpoints.

## Documentation workflow

- The `docs/` folder is the single source of truth for project documentation.
- Any change affecting features, user flows, roles, admin operations, or external integrations must be reflected in the relevant files under `docs/`.
- Before closing a milestone, verify whether `docs/overview.md`, `docs/user-guide.md`, `docs/admin-guide.md`, `docs/faq.md`, or `docs/changelog.md` need updates.
- Before final delivery, verify that the documentation builds correctly with MkDocs.
