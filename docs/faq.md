# FAQ

## Come si accede in sviluppo?

1. Installa le dipendenze: `cd app && npm install`
2. Copia `.env.example` in `.env` e inserisci le credenziali Supabase
3. Avvia il dev server: `npm run dev`

## Come si segnala un problema?

Apri una issue sul repository GitHub o contatta l'amministratore di progetto.

## Chi può modificare le impostazioni?

Solo gli amministratori di sistema (ruolo `admin`) possono modificare le impostazioni globali. Gli utenti autenticati possono modificare solo le proprie impostazioni personali.

## Dove viene ospitato il progetto?

- **Frontend**: Vercel (deploy automatico da `main`)
- **Backend**: Supabase (Auth, Database, Storage)
- **Documentazione**: GitHub Pages (aggiornata automaticamente da GitHub Actions)

## Che politiche di sicurezza sono attive?

- Row Level Security (RLS) su tutte le tabelle `public`
- Autenticazione JWT tramite Supabase Auth
- Variabili ambiente per chiavi API (mai commitare `.env`)
