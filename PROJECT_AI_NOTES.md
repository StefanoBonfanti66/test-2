# Project: Race Planner (test-2)

## Obiettivo
- Scopo: Applicazione web per pianificazione e gestione di gare sportive (triathlon, corsa, ecc.)
- Stato attuale: Progetto starter inizializzato da template triathlon-starter
- Risultato atteso della sessione: Analisi repo e inizializzazione documentazione

## Stack e vincoli
- Frontend: React 19 + TypeScript + Vite + TailwindCSS 4 + React Router 7
- Backend: Supabase (Auth, Postgres RLS, Storage)
- Database: PostgreSQL con RLS
- Infra: Vercel + GitHub Actions
- Docs: MkDocs Material + GitHub Pages
- Vincoli tecnici:
- Vincoli di piano/free tier:

## Decisioni prese
- [2026-05-25] Inizializzato sistema documentazione MkDocs

## Lavoro svolto
- File creati: (nessuno - struttura già presente)
- File modificati: `docs/overview.md`, `docs/user-guide.md`, `docs/admin-guide.md`, `docs/faq.md`, `docs/changelog.md`
- Test eseguiti: `npm audit` (0 vulnerabilities), `mkdocs build --strict` (success)

## TODO aperti
1. Definire tabelle database e policy RLS su Supabase
2. Implementare pagine e componenti React
3. Configurare autenticazione

## Problemi aperti
- Nessuno

## File toccati
- `docs/overview.md`
- `docs/user-guide.md`
- `docs/admin-guide.md`
- `docs/faq.md`
- `docs/changelog.md`
- `PROJECT_AI_NOTES.md`

## Prossimo step suggerito
- Definire data model e creare tabelle su Supabase
