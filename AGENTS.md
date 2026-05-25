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

## Current Focus

**Data**: 2026-05-25

**Completato**:
- Analisi repository (starter React + Supabase)
- Installazione dipendenze npm e verifica `npm audit` (0 vulnerabilities)
- Popolamento documentazione placeholder:
  - `docs/overview.md`: stack tecnico, utenti, obiettivo
  - `docs/user-guide.md`: stato attuale, flussi pianificati
  - `docs/admin-guide.md`: ruoli, configurazione Supabase
  - `docs/faq.md`: domande reali (dev, hosting, security)
  - `docs/changelog.md`: tracciamento modifiche
- Verifica build `mkdocs build --strict` (success)
- Aggiornamento `PROJECT_AI_NOTES.md`

**Manca**:
- Definizione data model (tabelle database)
- Policy RLS su Supabase
- Implementazione pagine React
- Configurazione autenticazione

**Prossimo step concreto**:
- Definire tabelle e relazioni su Supabase, poi implementare policy RLS
