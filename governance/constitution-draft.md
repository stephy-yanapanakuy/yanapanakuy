# Bozza Costituzione / *Constitution Draft*

> Documento di lavoro — Fase 0. Non vincolante finche' non approvato dall'assemblea dei Nodi.
> *Working document — Phase 0. Non-binding until approved by the Node assembly.*

---

## 1. Valori fondanti / *Founding values*

I seguenti valori sono immutabili senza referendum generale con soglia del 75% dei Nodi attivi.
*The following values are immutable without a general referendum with a 75% threshold of active Nodes.*

1. **Nessuna gerarchia permanente.** Ogni posizione di governance ha durata limitata e meccanismo di ricambio.
   *No permanent hierarchy. Every governance position has a limited term and a rotation mechanism.*

2. **Trasparenza delle decisioni.** Ogni decisione strutturale e' documentata pubblicamente con motivazione.
   *Decision transparency. Every structural decision is publicly documented with its rationale.*

3. **Nessun dato venduto o ceduto.** I dati degli utenti non sono un prodotto.
   *No data sold or transferred. User data is not a product.*

4. **Codice sempre aperto.** AGPL-3.0 senza eccezioni. Nessun componente closed-source nel core.
   *Code always open. AGPL-3.0 without exceptions. No closed-source component in the core.*

5. **No hate, no harassment.** Contenuti che incitano odio verso persone o gruppi sono incompatibili con la piattaforma.
   *No hate, no harassment. Content inciting hatred toward people or groups is incompatible with the platform.*

6. **Nessun singolo punto di controllo.** Nessuna persona fisica o giuridica puo' controllare unilateralmente la piattaforma.
   *No single point of control. No individual or legal entity can unilaterally control the platform.*

---

## 2. Struttura di governance / *Governance structure*

### 2.1 Livelli / *Levels*

**Cerchio Fondante** — gli ideatori e i primi collaboratori documentati pubblicamente (Fase 0).
- Ha potere decisionale pieno durante la Fase 0.
- Si dissolve automaticamente quando la comunita' raggiunge 50 Nodi attivi e la Fase 1 viene dichiarata.

*Founding Circle — the founders and the first publicly documented collaborators (Phase 0).*
*- Has full decision-making power during Phase 0.*
*- Automatically dissolves when the community reaches 50 active Nodes and Phase 1 is declared.*

**Assemblea dei Nodi** — tutti i Nodi verificati e attivi.
- Un Nodo e' "attivo" se ha fatto almeno 1 contributo negli ultimi 90 giorni.
- Ogni Nodo ha un voto. Nessun voto vale piu' di un altro.
- Delibera su: modifiche ai valori fondanti (75%), modifiche alla costituzione (60%), rimozione maintainer (60%), approvazione nuovi Biomes (50%).

*Node Assembly — all verified and active Nodes.*
*- A Node is "active" if it has made at least 1 contribution in the last 90 days.*
*- Every Node has one vote. No vote counts more than another.*
*- Deliberates on: changes to founding values (75%), changes to the constitution (60%), maintainer removal (60%), approval of new Biomes (50%).*

**Cerchio Tecnico** — maintainer del codice.
- Eletti dall'Assemblea per mandati di 6 mesi, rinnovabili una volta consecutivamente.
- Gestisce: deploy, sicurezza, architettura tecnica.
- Non puo' modificare regole di governance senza l'Assemblea.

*Technical Circle — code maintainers.*
*- Elected by the Assembly for 6-month terms, renewable once consecutively.*
*- Manages: deployment, security, technical architecture.*
*- Cannot modify governance rules without the Assembly.*

**Cerchio dei Biomes** — i coordinatori di ogni Biome.
- Estratti a rotazione parziale casuale tra i Nodi attivi del Biome (dopo 30 giorni di attivita').
- Mandato: 3 mesi. Non rinnovabile consecutivamente.
- Gestisce: moderazione locale, tono, obiettivi del Biome.

*Biomes Circle — coordinators of each Biome.*
*- Drawn by partial random rotation among the Biome's active Nodes (after 30 days of activity).*
*- Term: 3 months. Not renewable consecutively.*
*- Manages: local moderation, tone, Biome objectives.*

### 2.2 Principio di interdipendenza / *Interdependence principle*

Nessun cerchio puo' agire unilateralmente su decisioni che impattano gli altri cerchi. Le decisioni trasversali richiedono delibera congiunta. In caso di conflitto, l'Assemblea dei Nodi ha precedenza.

*No circle can act unilaterally on decisions that impact other circles. Cross-cutting decisions require joint deliberation. In case of conflict, the Node Assembly takes precedence.*

---

## 3. Soglie di voto / *Voting thresholds*

| Decisione / *Decision* | Soglia / *Threshold* | Quorum minimo / *Min. quorum* |
|---|---|---|
| Modifica valori fondanti / *Change founding values* | 75% | 50% dei Nodi attivi / *of active Nodes* |
| Modifica costituzione / *Change constitution* | 60% | 40% dei Nodi attivi / *of active Nodes* |
| Rimozione maintainer / *Maintainer removal* | 60% | 30% dei Nodi attivi / *of active Nodes* |
| Approvazione nuovo Biome / *Approve new Biome* | 50% | 20% dei Nodi attivi / *of active Nodes* |
| Decisioni operative Biome / *Biome operational decisions* | 50% | 10% dei Nodi del Biome / *of Biome Nodes* |

**Finestre di voto / *Voting windows*:** minimo 7 giorni, massimo 30 giorni. Nessun voto puo' chiudersi prima di 7 giorni dall'apertura, indipendentemente dai numeri.
*Minimum 7 days, maximum 30 days. No vote can close before 7 days from opening, regardless of the numbers.*

---

## 4. Moderazione / *Moderation*

### 4.1 Principi / *Principles*

- La moderazione e' locale per default: ogni Biome gestisce il proprio spazio.
  *Moderation is local by default: each Biome manages its own space.*
- I valori fondanti si applicano ovunque e non possono essere derogati localmente.
  *Founding values apply everywhere and cannot be waived locally.*
- Nessuna rimozione di Nodo senza processo documentato e possibilita' di risposta.
  *No Node removal without a documented process and the opportunity to respond.*

### 4.2 Processo di rimozione Nodo / *Node removal process*

1. Segnalazione da almeno 2 Nodi distinti. / *Report from at least 2 distinct Nodes.*
2. Il Cerchio del Biome coinvolto esamina e risponde entro 48 ore. / *The Biome Circle examines and responds within 48 hours.*
3. Il Nodo segnalato ha 72 ore per rispondere. / *The reported Node has 72 hours to respond.*
4. Decisione del Cerchio del Biome (semplice maggioranza). / *Decision by the Biome Circle (simple majority).*
5. Appello possibile all'Assemblea entro 7 giorni (richiede 5 Nodi co-firmatari). / *Appeal to the Assembly possible within 7 days (requires 5 co-signing Nodes).*

### 4.3 Violazioni gravi / *Serious violations*

Contenuti che incitano violenza fisica, materiale CSAM, doxing: la sospensione e' immediata e il processo di revisione avviene a posteriori entro 48 ore.

*Content inciting physical violence, CSAM material, doxing: suspension is immediate and the review process takes place retrospectively within 48 hours.*

---

## 5. Maintainer inattivi / *Inactive maintainers*

- Inattivo > 60 giorni: stato **dormiente** — nessun diritto di voto tecnico, nessun merge.
  *Inactive > 60 days: **dormant** status — no technical voting rights, no merges.*
- Inattivo > 90 giorni: il posto e' considerato vacante.
  *Inactive > 90 days: the position is considered vacant.*
- Sostituzione: proposta da qualsiasi Nodo, approvata dall'Assemblea al 60% entro 30 giorni dalla dichiarazione di vacanza.
  *Replacement: proposed by any Node, approved by the Assembly at 60% within 30 days of the vacancy declaration.*
- Il maintainer dormiente puo' riattivarsi autonomamente entro i 90 giorni comunicando al Cerchio Tecnico.
  *A dormant maintainer can self-reactivate within 90 days by notifying the Technical Circle.*

---

## 6. Transizione di fase / *Phase transition*

**Fase 0** (ora): Cerchio Fondante, repository pubblico, nessuna piattaforma utente.
*Phase 0 (now): Founding Circle, public repository, no user platform.*

**Fase 1** (trigger: 50 Nodi attivi): Assemblea dei Nodi convocata, elezione primo Cerchio Tecnico, attivazione del sistema di voto.
*Phase 1 (trigger: 50 active Nodes): Node Assembly convened, first Technical Circle elected, voting system activated.*

**Fase 2** (trigger: 200 Nodi attivi + 3 Biomes attivi): Governance completamente distribuita, Cerchio Fondante disciolto, piattaforma pubblica.
*Phase 2 (trigger: 200 active Nodes + 3 active Biomes): Fully distributed governance, Founding Circle dissolved, public platform.*

Ogni transizione richiede dichiarazione pubblica con 14 giorni di preavviso e possibilita' di obiezione formale.
*Every transition requires a public declaration with 14 days' notice and the possibility of formal objection.*

---

## 7. Revisione di questo documento / *Document revision*

Questa bozza viene rivista ogni 60 giorni fino all'approvazione formale in Fase 1. Le modifiche sono tracciate nel git log. Chiunque puo' aprire una PR con proposte motivate.

*This draft is revised every 60 days until formal approval in Phase 1. Changes are tracked in the git log. Anyone can open a PR with reasoned proposals.*

---

*Ultima revisione / Last revision: 2026-06-09 — Fase 0, bozza 2*
