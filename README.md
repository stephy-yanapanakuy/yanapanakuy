# Yanapanakuy
### Costruiamo insieme uno spazio che non appartiene a nessuno.
### *Building together a space that belongs to no one.*

> *Yanapanakuy* — quechua: aiutarsi a vicenda, cooperazione reciproca.

---

Yanapanakuy e' una piattaforma federata open source per cooperazione e mutuo aiuto, governata collettivamente. Questo repository contiene il codice, la documentazione e le decisioni di governance del progetto.

*Yanapanakuy is a federated open source platform for cooperation and mutual aid, collectively governed. This repository contains the code, documentation and governance decisions of the project.*

---

## Il problema / *The problem*

Le piattaforme digitali dominanti non sono strumenti neutrali. Sono sistemi ottimizzati per massimizzare il tempo di permanenza dell'utente, con un obiettivo preciso: vendere attenzione agli inserzionisti e dati comportamentali a chi puo' pagarli.

Le conseguenze architetturali sono documentate e verificabili:
- Gli algoritmi di raccomandazione amplificano i contenuti emotivamente attivanti perche' generano piu' engagement — l'outrage e la paura performano meglio della riflessione.
- I feed infiniti eliminano la conclusione naturale dell'esperienza, producendo affaticamento cognitivo e dipendenza.
- La metrica del like trasforma l'espressione in performance competitiva.
- I dati raccolti vengono usati per micro-targeting commerciale e politico senza consenso reale.

Non e' un problema di cattive intenzioni individuali. E' il risultato di sistemi ottimizzati per metriche che producono strutturalmente divisione e passivita' come effetto collaterale non corretto.

**Yanapanakuy parte da qui:** se l'architettura tecnica di una piattaforma determina i comportamenti che produce, cambiare i comportamenti richiede cambiare l'architettura.

---

## Il framework di analisi / *The analytical framework*

Il progetto usa il materialismo storico marxista come metodo di analisi — non come dottrina da imporre, ma come strumento per leggere chi possiede cosa, chi decide cosa, e come il potere si riproduce nelle strutture digitali.

Applicato al digitale, produce domande verificabili: chi possiede l'infrastruttura? Chi decide cosa e' visibile? Chi accumula valore dal lavoro degli utenti? Le risposte non sono opinioni — sono leggibili nei bilanci aziendali, nei brevetti, nelle ricerche accademiche.

Le implementazioni storiche del marxismo-leninismo come sistema di governo hanno prodotto concentrazione di potere e assenza di meccanismi di correzione — errori che questo progetto non ha intenzione di replicare, e che lo stesso framework permette di analizzare e nominare per evitarli strutturalmente.

---

## Architettura / *Architecture*

**Perche' federato / *Why federated*:**
- Nessun single point of failure o controllo centralizzato
- Chiunque puo' ospitare un nodo; le regole locali coesistono con standard condivisi
- Il codice e' open source e auditabile
- Nessuna azienda puo' chiudere la rete

**Perche' non X / *Why not X*:**
- *Discord*: proprietario, vende dati, puo' chiudere il server unilateralmente
- *Mastodon esistente*: UX ostile, nessun controllo sulla governance dell'istanza
- *Reddit*: IPO 2024, stesso modello di incentivi che critichiamo
- *Telegram*: centralizzato, governance opaca

**Verifica identita' / *Identity verification*:**
Esclusivamente tramite trust sociale: un nuovo Nodo viene introdotto da un Nodo gia' verificato. Nessuna email, nessun telefono. Il grafo delle introduzioni esiste ed e' trasparente per design — e' un dato necessario al funzionamento del sistema, protetto e non usato per altri scopi.

**Dati raccolti / *Data collected*:** nome, cognome, eta', genere (facoltativo). Niente altro.

**Verifica assenza tracker / *Verify no trackers*:**
Apri DevTools > Network > ricarica la pagina. Nessuna richiesta verso domini di analytics. Il codice sorgente e' pubblico: ogni script e' commentato e spiegato.

**Governance del codice / *Code governance*:**
- Contributor nuovi: ogni PR richiede review da almeno 2 maintainer
- Contributor con storia (>6 mesi, >10 PR): merge autonomo su componenti non critiche
- Componenti critiche (auth, moderazione, governance): review multipla sempre
- Deploy in produzione: threshold signatures 3 di 5 maintainer
- Maintainer inattivo >60 giorni: stato dormiente. Sostituzione possibile con voto al 60% dell'assemblea entro i successivi 30 giorni.

**Licenza / *License*:**
Il codice e' di tutti sotto AGPL-3.0. L'APS e' il custode legale, non il proprietario. Nessuno puo' chiuderlo, appropriarsene o usarlo per servizi proprietari.

---

## Struttura / *Structure*

**Yanapanakuy** — lo spazio complessivo. Valori fondanti immutabili senza referendum generale (75%).

**Biomes** — spazi tematici con obiettivi, stile e governance propri. Tutti vincolati ai valori fondanti. Core: *Discussione* e *Mutuo Aiuto*.

**Nodi** — le persone. Ogni nodo e' uguale in dignita', unico nelle connessioni. Il profilo mostra: Biomes di appartenenza, progetti contribuiti, tipo di contributo, frase libera. Non mostra: crediti totali, classifiche, confronti.

**Bootstrap governance:**
Il potere iniziale appartiene agli ideatori e ai primi collaboratori documentati pubblicamente. La transizione avviene tramite sistema misto: anzianita' verificata + ricambio parziale casuale estratto tra i Nodi attivi dopo periodo minimo di collaborazione. Nessuna posizione e' permanente.

---

## Struttura del repository / *Repository structure*

```
/docs          documentazione e decisioni
/platform      codice sorgente (in sviluppo)
/content       script e materiali contenuti social
/governance    bozza costituzione e meccanismi di voto
/design        sistema visivo e componenti UI
```

---

## Come contribuire / *How to contribute*

Il progetto e' in Fase 0. Non c'e' ancora una piattaforma da usare.

- **Competenze tecniche** (backend, frontend, infra, AI/ML, sicurezza): leggi la sezione architettura, apri una issue con le tue osservazioni. Il disaccordo tecnico motivato e' benvenuto.
- **Competenze non tecniche** (organizzazione, comunicazione, legale, design): ogni Biome in costruzione ha bisogno di persone che non siano developer.
- **Curiosi**: nessun impegno richiesto per guardare.

Il primo contributo non deve essere grande. Deve essere reale.

---

## Licenza / *License*

GNU Affero General Public License v3.0

Qualsiasi fork o derivato deve rimanere open source sotto la stessa licenza.

---

*Yanapanakuy non appartiene a nessuno. Costruiscila con noi.*
*Yanapanakuy belongs to no one. Build it with us.*
