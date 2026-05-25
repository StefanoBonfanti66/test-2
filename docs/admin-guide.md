# Guida amministratore

## Ruoli e permessi

*Ruoli da definire completamente in fase di implementazione*

| Ruolo | Descrizione |
|-------|-------------|
| `anon` | Utente non autenticato - sola lettura dati pubblici |
| `authenticated` | Utente autenticato - gestione dei propri dati |
| `admin` | Amministratore - gestione completa piattaforma |

## Configurazione Supabase

### Setup iniziale

1. Crea un progetto su [supabase.com](https://supabase.com)
2. Abilita Row Level Security (RLS) sulle tabelle `public`
3. Configura le variabili ambiente in `.env`:
   - `VITE_SUPABASE_URL`
   - `VITE_SUPABASE_ANON_KEY`

### Setup locale

```bash
cd app
cp ../.env.example .env
# modifica .env con le tue credenziali
npm install
npm run dev
```

## Controlli periodici

- Verifica policy RLS correttamente applicate
- Monitoraggio autenticazioni e accessi
- Backup automatici (abilitati da Supabase)
- Controllo utilizzo storage e bandwidth
