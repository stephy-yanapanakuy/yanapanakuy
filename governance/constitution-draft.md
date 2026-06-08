# Bozza Costituzione / *Constitution Draft*

> Documento di lavoro — Fase 0. Non vincolante finche' non approvato dall'assemblea dei Nodi.
> *Working document — Phase 0. Non-binding until approved by the Node assembly.*

---

## 1. Valori fondanti / *Founding values*

I seguenti valori sono immutabili senza referendum generale con soglia del 75% dei Nodi attivi.

*The following values are immutable without a general referendum with a 75% threshold of active Nodes.*

1. **Nessuna gerarchia permanente.** Ogni posizione di governance ha durata limitata e meccanismo di ricambio.
2. **Trasparenza delle decisioni.** Ogni decisione strutturale e' documentata pubblicamente con motivazione.
3. **Nessun dato venduto o ceduto.** I dati degli utenti non sono un prodotto.
4. **Codice sempre aperto.** AGPL-3.0 senza eccezioni. Nessun componente closed-source nel core.
5. **No hate, no harassment.** Contenuti che incitano odio verso persone o gruppi sono incompatibili con la piattaforma.
6. **Nessun singolo punto di controllo.** Nessuna persona fisica o giuridica puo' controllare unilateralmente la piattaforma.

---

## 2. Struttura di governance / *Governance structure*

### 2.1 Livelli / *Levels*

**Cerchio Fondante** — gli ideatori e i primi collaboratori documentati pubblicamente (Fase 0).
- Ha potere decisionale pieno durante la Fase 0.
- Si dissolve automaticamente quando la comunita' raggiunge 50 Nodi attivi e la Fase 1 viene dichiarata.

**Assemblea dei Nodi** — tutti i Nodi verificati e attivi.
- Un Nodo e' "attivo" se ha fatto almeno 1 contributo negli ultimi 90 giorni.
- Ogni Nodo ha un voto. Nessun voto vale piu' di un altro.
- Delibera su: modifiche ai valori fondanti (75%), modifiche alla costituzione (60%), rimozione maintainer (60%), approvazione nuovi Biomes (50%).

**Cerchio Tecnico** — maintainer del codice.
- Eletti dall'Assemblea per mandati di 6 mesi, rinnovabili una volta consecutivamente.
- Gestisce: deploy, sicurezza, architettura tecnica.
- Non puo' modificare regole di governance senza l'Assemblea.

**Cerchio dei Biomes** — i coordinatori di ogni Biome.
- Estratti a rotazione parziale casuale tra i Nodi attivi del Biome (dopo 30 giorni di attivita').
- Mandato: 3 mesi. Non rinnovabile consecutivamente.
- Gestisce: moderazione locale, tono, obiettivi del Biome.

### 2.2 Principio di interdipendenza / *Interdependence principle*

Nessun cerchio puo' agire unilateralmente su decisioni che impattano gli altri cerchi. Le decisioni trasversali richiedono delibera congiunta. In caso di conflitto, l'Assemblea dei Nodi ha precedenza.

---

## 3. Soglie di voto / *Voting thresholds*

| Decisione | Soglia | Quorum minimo |
|---|---|---|
| Modifica valori fondanti | 75% | 50% dei Nodi attivi |
| Modifica costituzione | 60% | 40% dei Nodi attivi |
| Rimozione maintainer | 60% | 30% dei Nodi attivi |
| Approvazione nuovo Biome | 50% | 20% dei Nodi attivi |
| Decisioni operative Biome | 50% | 10% dei Nodi del Biome |

**Finestre di voto / *Voting windows*:** minimo 7 giorni, massimo 30 giorni. Nessun voto puo' chiudersi prima di 7 giorni dall'apertura, indipendentemente dai numeri.

---

## 4. Moderazione / *Moderation*

### 4.1 Principi
- La moderazione e' locale per default (ogni Biome gestisce il proprio spazio).
- I valori fondanti si applicano ovunque e non possono essere derogati localmente.
- Nessuna rimozione di Nodo senza processo documentato e possibilita' di risposta.

### 4.2 Processo di rimozione Nodo
1. Segnalazione da almeno 2 Nodi distinti.
2. Il Cerchio del Biome coinvolto esamina e risponde entro 48 ore.
3. Il Nodo segnalato ha 72 ore per rispondere.
4. Decisione del Cerchio del Biome (semplice maggioranza).
5. Appello possibile all'Assemblea entro 7 giorni (richiede 5 Nodi che co-firmano la richiesta).

### 4.3 Violazioni gravi (accesso immediato sospeso)
Contenuti che incitano violenza fisica, materiale CSAM, doxing. In questi casi la sospensione e' immediata e il processo di revisione avviene a posteriori entro 48 ore.

---

## 5. Maintainer inattivi / *Inactive maintainers*

- Inattivo > 60 giorni: stato **dormiente** (nessun diritto di voto tecnico, nessun merge).
- Inattivo > 90 giorni: il posto e' considerato vacante.
- Sostituzione: proposta da qualsiasi Nodo, approvata dall'Assemblea al 60% entro 30 giorni dalla dichiarazione di vacanza.
- Il maintainer dormiente puo' riattivarsi autonomamente entro i 90 giorni comunicando al Cerchio Tecnico.

---

## 6. Transizione di fase / *Phase transition*

**Fase 0** (ora): Cerchio Fondante, repository pubblico, nessuna piattaforma utente.
**Fase 1** (trigger: 50 Nodi attivi): Assemblea dei Nodi convocata, elezione primo Cerchio Tecnico, attivazione del sistema di voto.
**Fase 2** (trigger: 200 Nodi attivi + 3 Biomes): Governance completamente distribuita, Cerchio Fondante disciolto, piattaforma pubblica.

Ogni transizione richiede dichiarazione pubblica con 14 giorni di preavviso e possibilita' di obiezione formale.

---

## 7. Revisione di questo documento / *Document revision*

Questa bozza viene rivista ogni 60 giorni fino all'approvazione formale in Fase 1. Le modifiche sono tracciate nel git log. Chiunque puo' aprire una PR con proposte motivate.

*This draft is revised every 60 days until formal approval in Phase 1. Changes are tracked in the git log. Anyone can open a PR with reasoned proposals.*

---

*Ultima revisione / Last revision: 2026-06-09 — Fase 0, bozza 1*
