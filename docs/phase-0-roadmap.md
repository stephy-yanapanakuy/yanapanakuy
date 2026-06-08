# Roadmap Fase 0 / *Phase 0 Roadmap*

> Stato: **attivo** — aggiornato al 2026-06-09
> *Status: **active** — updated 2026-06-09*

Fase 0 e' la fase di fondazione. Non esiste ancora una piattaforma pubblica. L'obiettivo e' costruire le fondamenta: codice, governance, comunita' iniziale.

*Phase 0 is the foundation phase. There is no public platform yet. The goal is to build the foundations: code, governance, initial community.*

---

## Obiettivo di uscita dalla Fase 0 / *Exit condition*

- [ ] 50 Nodi attivi verificati
- [ ] Bozza costituzione approvata dall'assemblea bootstrap
- [ ] MVP tecnico funzionante (autenticazione, spazi, post, moderazione base)
- [ ] Almeno 2 Biomes attivi (Discussione + Mutuo Aiuto)
- [ ] Audit di sicurezza esterno completato

---

## Milestone / *Milestones*

### M1 — Fondazione documentale *(completata)*
- [x] Repository pubblico creato
- [x] Licenza AGPL-3.0 applicata
- [x] README bilingue (IT/EN) con valori, architettura, struttura
- [x] Bozza costituzione (`governance/constitution-draft.md`)
- [x] Programma Pioneer documentato
- [ ] Apertura Issue pubbliche per contributi

### M2 — Architettura tecnica *(in corso)*
- [ ] Scelta stack definitiva (ActivityPub nativo vs Discourse/Decidim come MVP)
- [ ] Documento ADR (Architecture Decision Record) per ogni scelta critica
- [ ] Schema database iniziale
- [ ] Definizione API minima per autenticazione trust-based
- [ ] Prototipo sistema inviti (generazione codice, tracciamento grafo)

### M3 — Identita' e sicurezza
- [ ] Implementazione autenticazione senza email/telefono
- [ ] Sistema inviti funzionante (codici, scadenza, soglie 30gg)
- [ ] QR code per contributi in presenza (generazione + verifica)
- [ ] Audit privacy: zero tracker verificabile da DevTools
- [ ] Policy di moderazione tecnica (rate limiting, anti-spam)

### M4 — Piattaforma alpha (accesso solo Pioneer)
- [ ] Biome Discussione funzionante
- [ ] Biome Mutuo Aiuto funzionante
- [ ] Sistema di voto per decisioni di Biome
- [ ] Profilo Nodo (senza classifiche pubbliche)
- [ ] Deploy su infrastruttura autogestita (no cloud proprietario)

### M5 — Governance operativa
- [ ] Prima assemblea dei Nodi (online)
- [ ] Votazione formale sulla costituzione
- [ ] Elezione primo Cerchio Tecnico
- [ ] Dichiarazione pubblica di transizione a Fase 1

---

## Decisioni aperte / *Open decisions*

Queste decisioni richiedono discussione tecnica. Aprire una Issue per ciascuna.

| # | Decisione | Stato | Issue |
|---|---|---|---|
| 1 | Stack tecnico: ActivityPub nativo o MVP su Discourse? | aperta | - |
| 2 | Infrastruttura: self-hosted VPS o bare metal? | aperta | - |
| 3 | Sistema di voto: soluzione esistente (Decidim, Loomio) o custom? | aperta | - |
| 4 | QR code contributi: firma crittografica o hash semplice? | aperta | - |
| 5 | Lingua primaria del codice: italiano o inglese? | aperta | - |

---

## Rischi / *Risks*

| Rischio | Probabilita' | Impatto | Mitigazione |
|---|---|---|---|
| Pochi contributori tecnici in Fase 0 | alta | alto | Pioneer program, Issue aperte, comunicazione diretta |
| Deriva ideologica della governance | media | alto | Costituzione con valori immutabili |
| Attacchi spam/sybil al sistema inviti | media | medio | Soglie temporali + limite inviti attivi |
| Dipendenza da singolo maintainer | bassa | alto | Threshold signatures 3/5, processo sostituzione |
| Pressioni legali su contenuti | bassa | alto | APS come custode legale, AGPL protegge il codice |

---

## Come contribuire ora / *How to contribute now*

In Fase 0 le contribuzioni piu' utili sono:

1. **Revisione della bozza costituzione** — apri una PR su `governance/constitution-draft.md`
2. **Discussione stack tecnico** — commenta la Issue #1 (quando aperta)
3. **Design del sistema inviti** — Issue #4
4. **Revisione linguistica** — segnala errori o ambiguita' nel README o nella costituzione
5. **Contatti per Pioneer** — se conosci persone adatte, contatta i maintainer

---

*Questo documento viene aggiornato ad ogni milestone completata.*
*This document is updated at each completed milestone.*
