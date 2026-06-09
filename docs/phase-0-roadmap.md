# Roadmap Fase 0 / *Phase 0 Roadmap*

> Stato: **attivo** — aggiornato al 2026-06-09
> *Status: **active** — updated 2026-06-09*

Fase 0 e' la fase di fondazione. Non esiste ancora una piattaforma pubblica. L'obiettivo e' costruire le fondamenta: codice, governance, comunita' iniziale.

*Phase 0 is the foundation phase. There is no public platform yet. The goal is to build the foundations: code, governance, initial community.*

---

## Obiettivo di uscita dalla Fase 0 / *Phase 0 exit conditions*

- [ ] 50 Nodi attivi verificati / *50 verified active Nodes*
- [ ] Bozza costituzione approvata dall'assemblea bootstrap / *Constitution draft approved by the bootstrap assembly*
- [ ] MVP tecnico funzionante (autenticazione, spazi, post, moderazione base) / *Working technical MVP (auth, spaces, posts, basic moderation)*
- [ ] Almeno 2 Biomes attivi (Discussione + Mutuo Aiuto) / *At least 2 active Biomes (Discussion + Mutual Aid)*
- [ ] Audit di sicurezza esterno completato / *External security audit completed*

---

## Milestone

### M1 — Fondazione documentale / *Documentary foundation* *(completata / completed)*

- [x] Repository pubblico creato / *Public repository created*
- [x] Licenza AGPL-3.0 applicata / *AGPL-3.0 license applied*
- [x] README bilingue (IT/EN) con valori, architettura, struttura / *Bilingual README (IT/EN) with values, architecture, structure*
- [x] Bozza costituzione (`governance/constitution-draft.md`) / *Constitution draft*
- [x] Programma Pioneer documentato / *Pioneer Program documented*
- [ ] Apertura Issue pubbliche per contributi / *Open public Issues for contributions* — vedi Issues #1 #2 #3 / *see Issues #1 #2 #3*

### M2 — Architettura tecnica / *Technical architecture* *(in corso / in progress)*

- [ ] Scelta stack definitiva (ActivityPub nativo vs Discourse/Decidim come MVP) / *Final stack decision (native ActivityPub vs Discourse/Decidim as MVP)*
- [ ] Documento ADR (Architecture Decision Record) per ogni scelta critica / *ADR document for each critical decision*
- [ ] Schema database iniziale / *Initial database schema*
- [ ] Definizione API minima per autenticazione trust-based / *Minimal API definition for trust-based authentication*
- [ ] Prototipo sistema inviti (generazione codice, tracciamento grafo) / *Invite system prototype (code generation, graph tracking)*

### M3 — Identita' e sicurezza / *Identity and security*

- [ ] Implementazione autenticazione senza email/telefono / *Authentication without email/phone implemented*
- [ ] Sistema inviti funzionante (codici, scadenza, soglie 30gg) / *Working invite system (codes, expiry, 30-day thresholds)*
- [ ] QR code per contributi in presenza (generazione + verifica) / *QR codes for in-person contributions (generation + verification)*
- [ ] Audit privacy: zero tracker verificabile da DevTools / *Privacy audit: zero trackers verifiable from DevTools*
- [ ] Policy di moderazione tecnica (rate limiting, anti-spam) / *Technical moderation policy (rate limiting, anti-spam)*

### M4 — Piattaforma alpha (accesso solo Pioneer) / *Alpha platform (Pioneer access only)*

- [ ] Biome Discussione funzionante / *Discussion Biome working*
- [ ] Biome Mutuo Aiuto funzionante / *Mutual Aid Biome working*
- [ ] Sistema di voto per decisioni di Biome / *Voting system for Biome decisions*
- [ ] Profilo Nodo (senza classifiche pubbliche) / *Node profile (no public rankings)*
- [ ] Deploy su infrastruttura autogestita (no cloud proprietario) / *Deployed on self-managed infrastructure (no proprietary cloud)*

### M5 — Governance operativa / *Operational governance*

- [ ] Prima assemblea dei Nodi (online) / *First Node assembly (online)*
- [ ] Votazione formale sulla costituzione / *Formal vote on the constitution*
- [ ] Elezione primo Cerchio Tecnico / *First Technical Circle elected*
- [ ] Dichiarazione pubblica di transizione a Fase 1 / *Public declaration of transition to Phase 1*

---

## Decisioni aperte / *Open decisions*

Queste decisioni richiedono discussione tecnica. Ogni Issue e' linkata qui.
*These decisions require technical discussion. Each Issue is linked here.*

| # | Decisione / *Decision* | Stato / *Status* | Issue |
|---|---|---|---|
| 1 | Stack tecnico: ActivityPub nativo o MVP su Discourse? / *Tech stack: native ActivityPub or MVP on Discourse?* | aperta / *open* | #1 |
| 2 | Infrastruttura: self-hosted VPS o bare metal? / *Infrastructure: self-hosted VPS or bare metal?* | aperta / *open* | - |
| 3 | Sistema di voto: soluzione esistente (Decidim, Loomio) o custom? / *Voting system: existing solution or custom?* | aperta / *open* | - |
| 4 | QR code contributi: firma crittografica o hash semplice? / *Contribution QR: crypto signature or simple hash?* | aperta / *open* | #3 |
| 5 | Lingua primaria del codice: italiano o inglese? / *Primary code language: Italian or English?* | aperta / *open* | - |

---

## Rischi / *Risks*

| Rischio / *Risk* | Probabilita' / *Probability* | Impatto / *Impact* | Mitigazione / *Mitigation* |
|---|---|---|---|
| Pochi contributori tecnici in Fase 0 / *Few technical contributors in Phase 0* | alta / *high* | alto / *high* | Pioneer program, Issue aperte / *open Issues, direct outreach* |
| Deriva ideologica della governance / *Governance ideological drift* | media / *medium* | alto / *high* | Costituzione con valori immutabili / *Constitution with immutable values* |
| Attacchi spam/sybil al sistema inviti / *Spam/sybil attacks on invite system* | media / *medium* | medio / *medium* | Soglie temporali + limite inviti attivi / *Time thresholds + active invite limit* |
| Dipendenza da singolo maintainer / *Single-maintainer dependency* | bassa / *low* | alto / *high* | Threshold signatures 3/5, processo sostituzione / *replacement process* |
| Pressioni legali su contenuti / *Legal pressure on content* | bassa / *low* | alto / *high* | APS come custode legale, AGPL protegge il codice / *APS as legal custodian, AGPL protects the code* |

---

## Come contribuire ora / *How to contribute now*

In Fase 0 le contribuzioni piu' utili sono:
*In Phase 0 the most useful contributions are:*

1. **Revisione della bozza costituzione** — apri una PR su `governance/constitution-draft.md`
   *Review the constitution draft — open a PR on `governance/constitution-draft.md`*

2. **Discussione stack tecnico** — commenta la Issue #1
   *Technical stack discussion — comment on Issue #1*

3. **Design del sistema inviti** — commenta la Issue #3
   *Invite system design — comment on Issue #3*

4. **Revisione linguistica** — segnala errori o ambiguita' nel README o nella costituzione
   *Linguistic review — report errors or ambiguities in the README or constitution*

5. **Contatti per Pioneer** — se conosci persone adatte, contatta i maintainer
   *Pioneer contacts — if you know suitable people, contact the maintainers*

---

*Questo documento viene aggiornato ad ogni milestone completata.*
*This document is updated at each completed milestone.*
