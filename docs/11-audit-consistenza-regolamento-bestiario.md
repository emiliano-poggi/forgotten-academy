# THE FORGOTTEN ACADEMY
## Audit di consistenza — Regolamento e Bestiario

- **Identificativo:** TFA-AUDIT-RULEBOOK-BESTIARY-001
- **Stato:** Documento di lavoro — non normativo, da sottoporre ad approvazione
- **Repository:** `emiliano-poggi/forgotten-academy`
- **Branch di riferimento:** `main`
- **Ambito:** Regolamento ufficiale, Bestiario del Modulo U, Protocollo di Valutazione e Inventory Catalog
- **Data di redazione:** 1 novembre 2026

---

## 1. Scopo e metodo

Questo audit individua:
1. contraddizioni tra fonti ufficiali;
2. formulazioni ambigue che possono generare applicazioni divergenti;
3. lacune di completezza documentale che non costituiscono, da sole, violazioni delle regole.

L'audit non modifica né sostituisce le fonti esaminate. Le proposte di formulazione sono raccomandazioni da approvare prima di qualsiasi modifica normativa.

### 1.1 Gerarchia applicata

In caso di conflitto si applica la gerarchia stabilita dal progetto: il Regolamento ufficiale prevale sui protocolli e sugli altri documenti subordinati. Curriculum e manuale scolastico restano le fonti per i contenuti matematici.

### 1.2 Fonti esaminate

| Documento | Identificativo | Sezioni rilevanti |
|---|---|---|
| [Regolamento ufficiale](01-regolamento-ufficiale.md) | TFA-RULEBOOK | §§ 4, 5.2, 6, 9 |
| [Bestiario ufficiale](09-bestiario.md) | TFA-BESTIARY-U | §§ 1–6 |
| [Protocollo di Valutazione](08-protocollo-valutazione.md) | TFA-EVALUATION | §§ 6–8 |
| [Inventory Catalog](07-inventory-catalog.md) | TFA-INVENTORY | §§ 8, 10–12 |
| [README del repository](../README.md) | — | Struttura e gerarchia documentale |

---

## 2. Sintesi esecutiva

L'architettura didattica del Bestiario è coerente con il Regolamento: un Mostro per Stanza, un Drago e un Oracolo per Dungeon. La distribuzione dichiarata è di 25 Stanze/Mostri, 4 Draghi, 4 Oracoli e 93 competenze.

È stata rilevata una contraddizione normativa certa relativa allo sblocco dei tesori/artefatti. È inoltre presente un'ambiguità nella definizione degli stati delle Stanze e una lacuna di sviluppo delle schede narrative.

| ID | Rilievo | Tipo | Priorità |
|---|---|---|---|
| AUD-01 | Sblocco dei tesori in conflitto con la consultazione libera degli artefatti | Contraddizione normativa | Alta |
| AUD-02 | Stato COMPLETATA inserito tra gli stati delle Stanze ma definito come condizione del Dungeon | Ambiguità terminologica | Media |
| AUD-03 | Schede individuali delle creature non sviluppate nel documento | Lacuna documentale | Media |
| AUD-04 | Denominazioni provvisorie non ancora approvate | Stato editoriale da completare | Bassa |
| AUD-05 | Stato delle illustrazioni composite | Inventario degli asset da mantenere aggiornato | Bassa |

---

## 3. Rilievi dettagliati

### AUD-01 — Sblocco dei tesori e consultazione degli artefatti

**Classificazione:** contraddizione normativa  
**Priorità:** alta  
**Fonti coinvolte:** Bestiario § 4.1; Protocollo di Valutazione § 6; Regolamento § 9; Inventory Catalog §§ 8 e 10.

**Evidenza documentale**

- Il Bestiario § 4.1 afferma che il superamento del Mostro «sblocca i relativi tesori».
- Il Protocollo di Valutazione § 6 afferma che il superamento del Mostro «sblocca permanentemente i tesori associati».
- Il Regolamento § 9 stabilisce che gli artefatti sono liberamente consultabili in qualsiasi momento, indipendentemente dallo stato della Stanza e dal superamento di Mostri o Draghi.
- L'Inventory Catalog § 8 esclude condizioni di sblocco legate alla progressione della campagna.
- L'Inventory Catalog § 10 specifica che il Campaign Journal non registra sblocchi o possesso di artefatti.

**Valutazione**

Le formulazioni relative allo sblocco dei tesori sono incompatibili con le disposizioni superiori. In base alla gerarchia delle fonti, prevalgono il Regolamento e l'Inventory Catalog: il superamento del Mostro conquista la Stanza, ma non abilita l'accesso agli artefatti, che è già libero.

**Raccomandazione**

Sostituire nei documenti subordinati ogni riferimento allo sblocco dei tesori con una formulazione che distingua la conquista didattica dalla consultazione dei materiali.

**Formulazione proposta per il Bestiario § 4.1**

> Il superamento complessivo del Mostro comporta la conquista della Stanza. Gli artefatti associati alla Stanza restano liberamente consultabili in qualsiasi momento, indipendentemente dal superamento della prova. La conquista registra esclusivamente l'esito didattico previsto dal Regolamento.

**Formulazione proposta per il Protocollo § 6**

> Il superamento del Mostro conquista la Stanza. Non determina lo sblocco di artefatti o materiali, che restano liberamente consultabili secondo il Regolamento e l'Inventory Catalog.

**Decisione richiesta**

Approvare la rimozione del concetto di sblocco dei tesori dal Bestiario e dal Protocollo, mantenendo la conquista della Stanza come conseguenza del superamento del Mostro.

---

### AUD-02 — Stato COMPLETATA: Stanza o Dungeon?

**Classificazione:** ambiguità terminologica  
**Priorità:** media  
**Fonte coinvolta:** Regolamento § 5.2.

**Evidenza documentale**

Il § 5.2 presenta quattro voci sotto il titolo «Stati delle Stanze»: INESPLORATA, IN STUDIO, CONQUISTATA e COMPLETATA.

La definizione di COMPLETATA, tuttavia, è: «il Dungeon ha soddisfatto le condizioni di liberazione del proprio Oracolo».

La definizione descrive quindi una condizione del Dungeon, non una condizione della singola Stanza.

**Valutazione**

La regola sostanziale è coerente con il § 6.5: l'Oracolo viene liberato dopo il superamento di tutti i Mostri e del Drago. È la collocazione della voce COMPLETATA nell'elenco degli stati delle Stanze a generare ambiguità.

**Raccomandazione**

Separare gli stati delle Stanze dallo stato del Dungeon.

**Formulazione proposta**

> **Stati delle Stanze**
> - INESPLORATA: non ancora affrontata.
> - IN STUDIO: attività di apprendimento in corso.
> - CONQUISTATA: il Mostro della Stanza è stato superato.
>
> **Stato del Dungeon**
> - NON COMPLETATO: l'Oracolo non è ancora stato liberato.
> - COMPLETATO: sono stati superati tutti i Mostri delle Stanze e il Drago del Dungeon; l'Oracolo è liberato.

La denominazione «NON COMPLETATO» è proposta per rendere esplicita la distinzione, non è una voce già stabilita dalla fonte.

**Decisione richiesta**

Approvare la separazione formale degli stati delle Stanze e del Dungeon, oppure indicare una diversa terminologia canonica.

---

### AUD-03 — Schede individuali delle creature

**Classificazione:** lacuna documentale, non contraddizione normativa  
**Priorità:** media  
**Fonte coinvolta:** Bestiario §§ 2, 3 e 6.

**Evidenza documentale**

Il Bestiario definisce un modello standard di scheda Mostro con sei elementi:
1. Identità.
2. Rappresentazione visiva e mnemotecnica.
3. Nucleo didattico.
4. Prestazioni attese.
5. Errori e attenzioni.
6. Verifica.

Il documento, tuttavia, presenta principalmente tabelle di associazione tra ID, Stanze, nomi e competenze. Non contiene ancora 25 schede individuali complete secondo il modello.

**Stato delle denominazioni**

- I quattro Mostri di D-U01 hanno nomi approvati.
- Le denominazioni dei Mostri degli altri Dungeon sono indicate come provvisorie.
- Le denominazioni attuali dei Draghi e degli Oracoli sono etichette operative generiche; non risultano sviluppate come identità narrative individuali.

**Valutazione**

Il documento è sufficientemente definito per stabilire la struttura didattica delle creature, ma non costituisce ancora un repertorio narrativo completo.

**Raccomandazione**

Completare le schede in modo incrementale, mantenendo invariati gli ID e i collegamenti alle competenze del Curriculum. Ogni scheda dovrà rispettare il modello già approvato. Non introdurre competenze, errori individuali o contenuti matematici non documentati.

Per i Draghi e gli Oracoli si raccomanda di definire un modello di scheda coerente con le rispettive funzioni, previa approvazione, senza assimilare automaticamente la loro scheda a quella dei Mostri.

**Decisione richiesta**

Stabilire se sviluppare prima tutte le identità dei Mostri oppure procedere Dungeon per Dungeon, completando insieme Mostri, Drago e Oracolo.

---

### AUD-04 — Denominazioni provvisorie

**Classificazione:** stato editoriale da completare  
**Priorità:** bassa  
**Fonte coinvolta:** Bestiario § 2 e tabelle del § 3.

**Evidenza documentale**

Il Bestiario precisa che per D-U01 sono approvati i nomi dei quattro Mostri riportati nella tabella; le altre denominazioni restano provvisorie finché non approvate.

Le etichette provvisorie non costituiscono una violazione delle regole, purché non vengano presentate come nomi definitivi.

**Raccomandazione**

Mantenere una distinzione esplicita tra:
- nome approvato;
- etichetta operativa provvisoria;
- identità narrativa ancora da definire.

Non modificare gli identificativi tecnici durante la revisione dei nomi.

**Decisione richiesta**

Nessuna decisione normativa urgente. L'approvazione dei nomi potrà avvenire durante lo sviluppo delle schede.

---

### AUD-05 — Illustrazioni composite

**Classificazione:** stato degli asset da mantenere aggiornato  
**Priorità:** bassa  
**Fonte coinvolta:** Bestiario § 5; Regolamento § 6.6.

**Evidenza documentale**

Il Bestiario dichiara:
- IMG-U01 — generata e approvata;
- IMG-U02 — non generata;
- IMG-U03 — non generata;
- IMG-U04 — non generata.

Il Regolamento prevede un'illustrazione composita per ogni Dungeon e stabilisce che le quattro illustrazioni siano realizzate e approvate singolarmente.

**Valutazione**

Non emerge una contraddizione normativa: il Bestiario riporta uno stato di avanzamento compatibile con il Regolamento.

**Raccomandazione**

Mantenere aggiornato lo stato degli asset e verificare la presenza effettiva del file dichiarato per IMG-U01 prima di ogni futura revisione del registro. Le immagini restano artefatti da approvare singolarmente; non devono essere generate o inserite automaticamente nelle risposte.

---

## 4. Verifiche di coerenza senza rilievi

### 4.1 Struttura gerarchica

La corrispondenza dichiarata è coerente:

- 4 Dungeon;
- 25 Stanze;
- 25 Mostri, uno per Stanza;
- 4 Draghi, uno per Dungeon;
- 4 Oracoli, uno per Dungeon.

### 4.2 Distribuzione delle competenze

La distribuzione riportata nelle tabelle del Bestiario è:

| Dungeon | Stanze/Mostri | Competenze |
|---|---:|---:|
| D-U01 — Biblioteca delle Funzioni | 4 | 17 |
| D-U02 — Soglia dell'Infinito | 6 | 20 |
| D-U03 — Forgia dei Limiti | 8 | 32 |
| D-U04 — Torre delle Successioni | 7 | 24 |
| **Totale** | **25** | **93** |

I totali coincidono con quelli dichiarati dal Regolamento e dal Bestiario. Gli ID delle competenze sono mantenuti distinti nelle associazioni mostrate.

### 4.3 Funzione didattica delle creature

Le regole sono coerenti nei seguenti punti:

- Il Mostro verifica tutte le competenze della propria Stanza.
- La prova del Mostro è scritta e strutturata in più esercizi o problemi.
- Il Drago verifica l'integrazione delle competenze dell'intero Dungeon.
- La prova del Drago comprende sezioni diagnostiche per le Stanze e un problema finale integrato.
- Il Drago produce un unico esito complessivo, conservando le evidenze diagnostiche.
- L'Oracolo viene liberato dopo il superamento di tutti i Mostri e del Drago.
- Il titolo di Maestro del Dungeon richiede il livello III per tutti i Mostri e per il Drago; non coincide con la liberazione dell'Oracolo.

---

## 5. Rettifica di un rilievo non supportato

In una precedente analisi conversazionale era stata segnalata una presunta presenza di XP, HP, MP e attributi RPG nel Campaign Journal.

Questa affermazione non è supportata dalle fonti condivise effettivamente verificate durante la redazione del presente audit e viene pertanto esclusa dai rilievi.

Le fonti consultate stabiliscono invece che:
- il Regolamento § 4 esclude statistiche RPG, punti esperienza, livelli del personaggio, attributi, punti vita e punti mana;
- l'Inventory Catalog § 10 attribuisce al Campaign Journal la funzione di registro dello stato didattico e specifica che non registra sblocchi o possesso di artefatti.

Non viene formulata alcuna conclusione sul contenuto di eventuali repository individuali, che non sono stati esaminati nell'ambito di questo audit.

---

## 6. Piano di riconciliazione proposto

Si raccomanda il seguente ordine:

1. Approvare la correzione AUD-01 e allineare Bestiario e Protocollo al Regolamento.
2. Approvare la distinzione tra stati delle Stanze e stato del Dungeon (AUD-02).
3. Completare le schede delle creature senza alterare ID o competenze (AUD-03).
4. Approvare progressivamente le denominazioni provvisorie (AUD-04).
5. Verificare e aggiornare il registro delle illustrazioni (AUD-05).

Le correzioni alle fonti normative dovranno essere eseguite solo dopo l'approvazione delle relative decisioni. Ogni modifica dovrà essere verificata insieme agli indici e ai documenti collegati.

---

## 7. Registro delle decisioni

| ID | Decisione | Stato |
|---|---|---|
| AUD-01 | Rimuovere il concetto di sblocco degli artefatti | In attesa di approvazione |
| AUD-02 | Separare stati delle Stanze e del Dungeon | In attesa di approvazione |
| AUD-03 | Definire la sequenza di sviluppo delle schede | In attesa di decisione |
| AUD-04 | Approvare le denominazioni provvisorie | Da pianificare |
| AUD-05 | Verificare e mantenere aggiornato il registro delle immagini | Da verificare |

---

**Fine documento — TFA-AUDIT-RULEBOOK-BESTIARY-001**

*Questo audit è uno strumento di analisi e proposta. Non modifica il Regolamento, il Bestiario, il Protocollo di Valutazione o l'Inventory Catalog e non introduce nuove regole finché le decisioni non vengono approvate e recepite nelle rispettive fonti.*
