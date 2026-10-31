# THE FORGOTTEN ACADEMY
## Bestiario ufficiale — Modulo U

**Identificativo:** TFA-BESTIARY-U  
**Versione:** 1.1  
**Stato:** Ufficiale  
**Regolamento di riferimento:** TFA-RULEBOOK v2.1  
**Curriculum di riferimento:** TFA-CURRICULUM-U v2.0  
**Ambito:** Modulo U — Capitoli 20–23

---

# 1. Finalità

Il Bestiario raccoglie i Mostri associati alle competenze matematiche del Modulo U.

Ogni Mostro rappresenta una specifica competenza del Curriculum. Il suo nome, la descrizione narrativa e l'eventuale illustrazione hanno funzione mnemonica e simbolica: non modificano il contenuto matematico da apprendere o verificare.

Il collegamento tra Mostro e competenza è stabile e identificato da un codice univoco.

Il Bestiario comprende 93 Mostri distribuiti nelle 25 Stanze dei quattro Dungeon del Modulo U.

# 2. Principi di gestione

## 2.1 Identificativi

Ogni Mostro possiede un identificativo stabile secondo il formato:

`MON-U[dungeon]-[stanza]-[numero]`

Esempio: `MON-U01-01-01`.

L'identificativo non cambia quando vengono modificati il nome narrativo, la descrizione o l'illustrazione.

## 2.2 Generazione delle illustrazioni

Le illustrazioni vengono generate **on demand**, quando lo studente incontra il relativo Mostro.

Non è prevista la produzione preventiva delle 93 immagini.

Ogni immagine deve:
- rispettare lo stile pittorico dark fantasy approvato;
- essere originale e coerente con l'identità visiva dell'Accademia;
- rappresentare in modo riconoscibile il Mostro;
- contenere riferimenti visivi alla competenza associata;
- evitare formule, testi e simboli matematici decorativi non necessari.

L'illustrazione viene sottoposta allo studente, che può approvarla, richiederne la modifica o chiederne una nuova versione.

Solo dopo l'approvazione viene considerata immagine definitiva del Mostro.

## 2.3 Distinzione tra stato didattico e stato dell'immagine

L'approvazione dell'immagine non equivale al superamento del Mostro.

Il Bestiario tiene separati:
- **Stato didattico:** determinato dalle verifiche e dal Campaign Journal.
- **Stato dell'immagine:** determinato dalla generazione e dall'approvazione artistica.

Gli stati dell'immagine sono:

| Stato | Significato |
|---|---|
| NON GENERATA | Nessuna illustrazione prodotta |
| DA REVISIONARE | Illustrazione generata, in attesa del giudizio dello studente |
| DA MODIFICARE | Lo studente ha richiesto modifiche |
| APPROVATA | Illustrazione confermata dallo studente |
| ARCHIVIATA | File definitivo presente nel repository e collegato al catalogo |

## 2.4 Archiviazione

Gli asset definitivi sono conservati nel repository:

`assets/bestiario/dungeon-uXX/`

Formato previsto: WebP, orientamento verticale, dimensione indicativa 768 × 1024 px, obiettivo di compressione pari o inferiore a 300 KB.

Il nome del file corrisponde all'identificativo del Mostro.

Esempio:

`assets/bestiario/dungeon-u01/MON-U01-01-01.webp`

Il percorso viene inserito nel catalogo soltanto dopo la verifica del caricamento.

# 3. Dungeon I — Biblioteca delle Funzioni

**ID:** D-U01  
**Capitolo:** 20 — Le funzioni e le loro proprietà  
**Totale Mostri:** 17

## R-U01-01 — La Natura delle Funzioni

**Riferimento:** Capitolo 20, §1, p. 1354.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U01-01-01 | Il Tessitore di Legami | A-U01-01 — Comprendere il concetto di funzione reale di variabile reale |
| MON-U01-01-02 | Il Cartografo dei Due Regni | A-U01-02 — Riconoscere dominio e codominio |
| MON-U01-01-03 | Il Veggente delle Tracce | A-U01-03 — Interpretare il grafico di una funzione |
| MON-U01-01-04 | Il Doppio Senza Volto | A-U01-04 — Distinguere una funzione da una relazione che non è funzione |

## R-U01-02 — Il Dominio

**Riferimento:** Capitolo 20, §1, p. 1354 e relativi esercizi.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U01-02-01 | Il Divoratore di Valori Vietati | A-U01-05 — Determinare il dominio di funzioni algebriche |
| MON-U01-02-02 | La Sfinge delle Condizioni | A-U01-06 — Determinare il dominio di funzioni contenenti radicali e frazioni |
| MON-U01-02-03 | Il Cerbero delle Tre Soglie | A-U01-07 — Determinare il dominio di funzioni esponenziali, logaritmiche e goniometriche |
| MON-U01-02-04 | L'Arbitro dei Confini | A-U01-08 — Combinare più condizioni di esistenza |

## R-U01-03 — Le Proprietà delle Funzioni

**Riferimento:** Capitolo 20, §2, p. 1359.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U01-03-01 | Il Cacciatore delle Impronte Uniche | A-U01-09 — Riconoscere funzioni iniettive |
| MON-U01-03-02 | Il Signore delle Immagini Mancanti | A-U01-10 — Riconoscere funzioni suriettive |
| MON-U01-03-03 | Il Custode dei Patti Perfetti | A-U01-11 — Riconoscere funzioni biiettive |
| MON-U01-03-04 | Il Serpente delle Salite e delle Discese | A-U01-12 — Studiare la monotonia |
| MON-U01-03-05 | Il Gemello dello Specchio | A-U01-13 — Riconoscere funzioni pari e dispari |
| MON-U01-03-06 | La Falena del Ritorno | A-U01-14 — Individuare la periodicità |
| MON-U01-03-07 | L'Evocatore dei Percorsi Inversi | A-U01-15 — Determinare o interpretare funzioni inverse |

## R-U01-04 — Le Trasformazioni dei Grafici

**Riferimento:** Capitolo 20, §2 e materiali associati.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U01-04-01 | Il Trasfiguratore delle Curve | A-U01-16 — Interpretare le trasformazioni geometriche dei grafici |
| MON-U01-04-02 | Il Giudice delle Metamorfosi | A-U01-17 — Riconoscere gli effetti delle trasformazioni sulle proprietà della funzione |

# 4. Dungeon II — Soglia dell'Infinito

**ID:** D-U02  
**Capitolo:** 21 — I limiti delle funzioni  
**Totale Mostri:** 20

## R-U02-01 — La Geometria della Retta Reale

**Riferimento:** Capitolo 21, §1, p. 1404.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U02-01-01 | Il Divisore degli Intervalli | A-U02-01 — Comprendere gli intervalli della retta reale |
| MON-U02-01-02 | Il Tessitore delle Vicinanze | A-U02-02 — Comprendere il concetto di intorno |
| MON-U02-01-03 | Il Custode delle Tre Prossimità | A-U02-03 — Riconoscere intorni completi, circolari e destri o sinistri |
| MON-U02-01-04 | L'Eremita dell'Accumulazione | A-U02-04 — Interpretare i punti di accumulazione e i concetti topologici introdotti nel testo |

## R-U02-02 — Il Limite Finito in un Punto

**Riferimento:** Capitolo 21, §2, p. 1413.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U02-02-01 | Il Sussurratore dell'Avvicinamento | A-U02-05 — Comprendere la definizione di limite finito per x che tende a x₀ |
| MON-U02-02-02 | Il Pittore dell'Incontro | A-U02-06 — Interpretare il significato grafico della definizione |
| MON-U02-02-03 | Il Falso Volto | A-U02-07 — Distinguere il valore della funzione dal suo limite |
| MON-U02-02-04 | Il Guardiano delle Due Direzioni | A-U02-08 — Interpretare i limiti destro e sinistro |

## R-U02-03 — Il Limite Infinito in un Punto

**Riferimento:** Capitolo 21, §3, p. 1420.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U02-03-01 | Il Pozzo Senza Fondo | A-U02-09 — Comprendere la definizione di limite infinito per x che tende a x₀ |
| MON-U02-03-02 | Il Giano delle Divergenze | A-U02-10 — Distinguere divergenza positiva e negativa |
| MON-U02-03-03 | Il Veggente della Voragine | A-U02-11 — Interpretare il comportamento grafico della funzione |

## R-U02-04 — Il Limite Finito all'Infinito

**Riferimento:** Capitolo 21, §4, p. 1425.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U02-04-01 | Il Viandante dell'Orizzonte | A-U02-12 — Comprendere la definizione di limite finito per x che tende all'infinito |
| MON-U02-04-02 | Il Pellegrino dell'Estremo | A-U02-13 — Interpretare il comportamento di una funzione per valori assoluti crescenti della variabile |
| MON-U02-04-03 | Il Disegnatore dell'Asintoto Lontano | A-U02-14 — Interpretare graficamente il limite finito all'infinito |

## R-U02-05 — Il Limite Infinito all'Infinito

**Riferimento:** Capitolo 21, §5, p. 1428.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U02-05-01 | Il Colosso dell'Estensione | A-U02-15 — Comprendere la definizione di limite infinito per x che tende all'infinito |
| MON-U02-05-02 | Il Bifronte dell'Illimitato | A-U02-16 — Distinguere le diverse direzioni di divergenza |
| MON-U02-05-03 | Il Divoratore dell'Orizzonte | A-U02-17 — Interpretare il comportamento di funzioni illimitate all'infinito |

## R-U02-06 — I Primi Teoremi sui Limiti

**Riferimento:** Capitolo 21, §6, p. 1430.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U02-06-01 | L'Arconte delle Conseguenze | A-U02-18 — Comprendere i primi teoremi sui limiti |
| MON-U02-06-02 | Il Custode delle Premesse | A-U02-19 — Riconoscere le condizioni di applicabilità |
| MON-U02-06-03 | Il Giudice delle Deduzioni | A-U02-20 — Utilizzare correttamente i teoremi nella risoluzione di esercizi |

# 5. Dungeon III — Forgia dei Limiti

**ID:** D-U03  
**Capitolo:** 22 — Il calcolo dei limiti  
**Totale Mostri:** 32

## R-U03-01 — Le Operazioni sui Limiti

**Riferimento:** Capitolo 22, §1, p. 1476.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U03-01-01 | Il Fabbro delle Operazioni | A-U03-01 — Applicare le operazioni sui limiti |
| MON-U03-01-02 | Il Mietitore delle Somme | A-U03-02 — Calcolare limiti di somme e differenze |
| MON-U03-01-03 | Il Divoratore di Prodotti | A-U03-03 — Calcolare limiti di prodotti e quozienti |
| MON-U03-01-04 | Il Forgiatore delle Potenze | A-U03-04 — Applicare le proprietà delle potenze e delle funzioni coinvolte nei limiti |

## R-U03-02 — Le Forme Indeterminate

**Riferimento:** Capitolo 22, §2, p. 1484.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U03-02-01 | Il Mascherato delle Sette Forme | A-U03-05 — Riconoscere le forme indeterminate trattate nel manuale |
| MON-U03-02-02 | Il Trasmutatore delle Espressioni | A-U03-06 — Individuare una strategia algebrica adeguata |
| MON-U03-02-03 | Il Dissolutore dell'Indeterminato | A-U03-07 — Risolvere limiti che presentano forme indeterminate |

## R-U03-03 — I Limiti Notevoli

**Riferimento:** Capitolo 22, §3, p. 1489.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U03-03-01 | L'Oracolo delle Costanti | A-U03-08 — Comprendere i limiti notevoli presentati nel manuale |
| MON-U03-03-02 | Il Notaio delle Condizioni | A-U03-09 — Riconoscere le condizioni di applicabilità |
| MON-U03-03-03 | Il Riconduttore | A-U03-10 — Utilizzare i limiti notevoli nelle trasformazioni |
| MON-U03-03-04 | Il Chimico delle Equivalenze | A-U03-11 — Risolvere esercizi che richiedono combinazioni di limiti notevoli |

## R-U03-04 — Infinitesimi e Infiniti

**Riferimento:** Capitolo 22, §4, p. 1492.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U03-04-01 | La Falena dell'Evaporazione | A-U03-12 — Comprendere il concetto di infinitesimo |
| MON-U03-04-02 | Il Titano dell'Illimitato | A-U03-13 — Comprendere il concetto di infinito |
| MON-U03-04-03 | Il Bilanciere degli Ordini | A-U03-14 — Confrontare infinitesimi e infiniti |
| MON-U03-04-04 | Il Predatore delle Gerarchie | A-U03-15 — Utilizzare il confronto per risolvere limiti |

## R-U03-05 — La Continuità

**Riferimento:** Capitolo 22, §5, p. 1497.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U03-05-01 | Il Guardiano del Filo Ininterrotto | A-U03-16 — Comprendere la definizione di funzione continua |
| MON-U03-05-02 | Il Sigillatore del Punto | A-U03-17 — Verificare la continuità in un punto |
| MON-U03-05-03 | Il Custode del Cammino | A-U03-18 — Studiare la continuità negli intervalli |
| MON-U03-05-04 | Il Giurista della Continuità | A-U03-19 — Comprendere e applicare i teoremi sulle funzioni continue introdotti nel manuale |

## R-U03-06 — Le Discontinuità

**Riferimento:** Capitolo 22, §6, p. 1500.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U03-06-01 | Il Cercatore delle Fratture | A-U03-20 — Riconoscere i punti di discontinuità |
| MON-U03-06-02 | Il Tassonomo delle Fratture | A-U03-21 — Classificare le discontinuità secondo la trattazione del manuale |
| MON-U03-06-03 | Il Chirurgo delle Lacune | A-U03-22 — Distinguere discontinuità eliminabili e non eliminabili |
| MON-U03-06-04 | Il Pittore delle Interruzioni | A-U03-23 — Interpretare graficamente i diversi casi |

## R-U03-07 — La Ricerca degli Asintoti

**Riferimento:** Capitolo 22, §7, p. 1503.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U03-07-01 | Il Tracciatore delle Rette Lontane | A-U03-24 — Comprendere la definizione di asintoto |
| MON-U03-07-02 | Il Pilastro dell'Abisso | A-U03-25 — Ricercare asintoti verticali |
| MON-U03-07-03 | La Lama dell'Orizzonte | A-U03-26 — Ricercare asintoti orizzontali |
| MON-U03-07-04 | Il Viandante Inclinato | A-U03-27 — Ricercare asintoti obliqui |
| MON-U03-07-05 | Il Cartografo delle Frontiere | A-U03-28 — Interpretare la relazione tra limiti e asintoti |

## R-U03-08 — Il Grafico Probabile

**Riferimento:** Capitolo 22, §8, p. 1507.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U03-08-01 | L'Archivista delle Curve | A-U03-29 — Organizzare le informazioni ricavate dallo studio di una funzione |
| MON-U03-08-02 | Il Cercatore dei Segni | A-U03-30 — Determinare le caratteristiche utili alla costruzione del grafico |
| MON-U03-08-03 | Il Disegnatore del Destino | A-U03-31 — Costruire il grafico probabile |
| MON-U03-08-04 | Il Lettore delle Forme | A-U03-32 — Interpretare il grafico alla luce delle proprietà analitiche |

# 6. Dungeon IV — Torre delle Successioni

**ID:** D-U04  
**Capitolo:** 23 — Le successioni e le serie  
**Totale Mostri:** 24

## R-U04-01 — La Natura delle Successioni

**Riferimento:** Capitolo 23, §1, p. 1568.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U04-01-01 | Il Seminatore dei Numeri | A-U04-01 — Comprendere il concetto di successione |
| MON-U04-01-02 | Il Tessitore dell'Indice | A-U04-02 — Interpretare una successione attraverso il termine generale |
| MON-U04-01-03 | Il Collezionista delle Sequenze | A-U04-03 — Rappresentare e riconoscere successioni numeriche |

## R-U04-02 — Tipologie di Successioni

**Riferimento:** Capitolo 23, §2, p. 1570.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U04-02-01 | Il Bestiografo delle Sequenze | A-U04-04 — Riconoscere i tipi di successioni presentati nel testo |
| MON-U04-02-02 | Il Custode dei Caratteri | A-U04-05 — Analizzare le proprietà delle successioni |
| MON-U04-02-03 | Il Cerimoniere dei Confini | A-U04-06 — Studiare monotonia e limitatezza quando pertinenti |

## R-U04-03 — Il Limite di una Successione

**Riferimento:** Capitolo 23, §3, p. 1571.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U04-03-01 | Il Pellegrino dell'Indice Infinito | A-U04-07 — Comprendere la definizione di limite di una successione |
| MON-U04-03-02 | Il Bifronte della Convergenza | A-U04-08 — Distinguere convergenza e divergenza |
| MON-U04-03-03 | Il Signore dei Due Infiniti | A-U04-09 — Riconoscere divergenza positiva e negativa |
| MON-U04-03-04 | Il Veggente dei Termini | A-U04-10 — Verificare il comportamento di una successione |

## R-U04-04 — I Teoremi sui Limiti delle Successioni

**Riferimento:** Capitolo 23, §4, p. 1574.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U04-04-01 | L'Arconte delle Successioni | A-U04-11 — Comprendere i teoremi sui limiti delle successioni |
| MON-U04-04-02 | Il Custode delle Premesse | A-U04-12 — Riconoscere le ipotesi dei teoremi |
| MON-U04-04-03 | Il Giudice delle Deduzioni | A-U04-13 — Applicare i teoremi nella risoluzione degli esercizi |

## R-U04-05 — I Limiti delle Progressioni

**Riferimento:** Capitolo 23, §5, p. 1576.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U04-05-01 | Il Cronista dei Passi Regolari | A-U04-14 — Comprendere le progressioni trattate nel manuale |
| MON-U04-05-02 | Il Gemello della Ragione | A-U04-15 — Riconoscere progressioni aritmetiche e geometriche |
| MON-U04-05-03 | Il Custode del Ritmo | A-U04-16 — Utilizzare le proprietà delle progressioni |
| MON-U04-05-04 | Il Viandante dei Passi Infiniti | A-U04-17 — Determinare i limiti delle progressioni |

## R-U04-06 — La Nascita di una Serie

**Riferimento:** Capitolo 23, §6, p. 1579.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U04-06-01 | Il Sommatore delle Eternità | A-U04-18 — Comprendere il concetto di serie numerica |
| MON-U04-06-02 | Il Custode dei Frammenti | A-U04-19 — Comprendere il ruolo delle somme parziali |
| MON-U04-06-03 | Il Tessitore delle Somme | A-U04-20 — Collegare il comportamento delle somme parziali al concetto di limite |

## R-U04-07 — Convergenza e Divergenza delle Serie

**Riferimento:** Capitolo 23, §7, p. 1581.

| ID Mostro | Nome | Competenza |
|---|---|---|
| MON-U04-07-01 | Il Collezionista dell'Equilibrio | A-U04-21 — Comprendere le serie convergenti |
| MON-U04-07-02 | Il Divoratore delle Somme | A-U04-22 — Comprendere le serie divergenti |
| MON-U04-07-03 | L'Enigma delle Somme | A-U04-23 — Riconoscere le serie indeterminate secondo la classificazione del manuale |
| MON-U04-07-04 | Il Giudice dell'Infinita Somma | A-U04-24 — Determinare il comportamento di una serie attraverso le somme parziali |

# 7. Registro delle illustrazioni

Il registro viene aggiornato quando lo studente incontra e approva le immagini dei Mostri.

| ID Mostro | Nome | Stato immagine | Percorso repository |
|---|---|---|---|
| MON-U01-01-01 | Il Tessitore di Legami | APPROVATA — caricamento indicato dall'utente, contenuto binario non verificato dal connettore | `assets/bestiario/dungeon-u01/MON-U01-01-01.webp` |
| MON-U01-01-02 | Il Cartografo dei Due Regni | APPROVATA — asset non ancora verificato nel repository | Da assegnare |
| Tutti gli altri Mostri | — | NON GENERATA | Da assegnare al momento della creazione |

La tabella è un registro operativo: le immagini non generate non costituiscono contenuti mancanti del Curriculum.

# 8. Conteggio ufficiale

| Dungeon | Stanze | Mostri |
|---|---:|---:|
| D-U01 — Biblioteca delle Funzioni | 4 | 17 |
| D-U02 — Soglia dell'Infinito | 6 | 20 |
| D-U03 — Forgia dei Limiti | 8 | 32 |
| D-U04 — Torre delle Successioni | 7 | 24 |
| **Totale** | **25** | **93** |

Ogni Mostro è associato a una e una sola competenza del Curriculum.

# 9. Relazione con le verifiche

Il Mostro è l'identità narrativa della competenza, non una valutazione già conseguita.

La verifica del Mostro segue il Regolamento ufficiale e il Protocollo di Valutazione:
- prova scritta strutturata con più esercizi o problemi;
- livello scelto dallo studente: I — Apprendista, II — Adepto, III — Arcimago;
- valutazione qualitativa basata su correttezza, comprensione, autonomia e trasferimento;
- registrazione dell'esito nel Campaign Journal.

Il Bestiario non assegna livelli di padronanza e non registra sconfitte o certificazioni: tali informazioni appartengono al Campaign Journal.


# 10. Modello standard della scheda Mostro

Le schede dei Mostri adottano una struttura a prevalenza didattica. La componente narrativa è limitata a quanto serve a identificare il personaggio e a rendere memorabile il concetto; non deve sostituire né diluire la spiegazione matematica.

Ogni scheda comprende:

1. **Identità:** ID, nome, Dungeon, Stanza, competenza associata e riferimento al manuale.
2. **Rappresentazione visiva e mnemotecnica:** illustrazione e spiegazione sintetica del rapporto tra gli elementi visivi e il concetto matematico.
3. **Nucleo didattico:** spiegazione del concetto, con definizioni, proprietà e notazione aderenti alla fonte scolastica. Non si introducono contenuti non documentati dal manuale.
4. **Comportamento didattico:** capacità e prestazioni osservabili che lo studente deve sviluppare in relazione alla competenza. Non descrive il comportamento narrativo della creatura.
5. **Errori e attenzioni:** confusioni e difficoltà da monitorare, da precisare sulla base delle evidenze didattiche e senza attribuire allo studente errori non ancora osservati.
6. **Verifica della competenza:** rimando al Regolamento e al Protocollo di Valutazione. La scheda non anticipa né sostituisce l'esito della verifica.

La descrizione fantasy estesa non è un campo standard. Il simbolismo visivo è invece mantenuto perché svolge una funzione mnemotecnica.

## 10.1 Scheda pilota — MON-U01-01-01

### Identità

- **Nome:** Il Tessitore di Legami
- **Dungeon:** D-U01 — Biblioteca delle Funzioni
- **Stanza:** R-U01-01 — La Natura delle Funzioni
- **Competenza:** A-U01-01 — Comprendere il concetto di funzione reale di variabile reale.
- **Riferimento:** Capitolo 20, §1, p. 1354 del *Manuale blu 2.0 di matematica*, Volume U.
- **Immagine:** approvata dallo studente; percorso previsto: `assets/bestiario/dungeon-u01/MON-U01-01-01.webp`.

### Rappresentazione visiva e mnemotecnica

L'illustrazione raffigura una figura incappucciata che dispone fili luminosi tra sfere sospese.

- **Fili:** richiamano le corrispondenze tra gli elementi.
- **Sfere:** rappresentano visivamente i valori coinvolti nella relazione.
- **Collegamenti ordinati:** richiamano la condizione caratteristica della funzione: a ogni elemento del dominio deve corrispondere uno e un solo valore.
- **Trama complessiva:** evoca la struttura di una funzione come corrispondenza tra variabili.

Questa lettura è un ausilio mnemonico e non sostituisce la definizione matematica.

### Nucleo didattico

Da sviluppare sulla base del paragrafo del manuale indicato. Definizioni, proprietà, notazione ed eventuali esempi dovranno rispettare il testo della fonte scolastica, senza integrazioni non verificate.

### Comportamento didattico

Lo studente deve saper:
- riconoscere una funzione reale di variabile reale;
- individuare la variabile indipendente e quella dipendente;
- interpretare la corrispondenza tra i valori di ingresso e i valori associati;
- comprendere la condizione che distingue una funzione da una relazione generica.

Questi punti esplicitano operativamente la competenza A-U01-01 e non costituiscono nuove competenze del Curriculum.

### Errori e attenzioni

Nessun errore individuale viene attribuito in anticipo. Le eventuali difficoltà saranno registrate nel Campaign Journal soltanto quando emergeranno durante attività o verifiche.

### Verifica della competenza

La verifica segue il Protocollo di Valutazione vigente. La scheda non assegna livelli di padronanza e non registra un esito didattico.

# 11. Registro delle revisioni

| Versione | Stato | Modifiche |
|---|---|---|
| 1.0 | Ufficiale | Prima catalogazione dei 93 Mostri; identificativi stabili; collegamento alle 93 competenze; regole per generazione on demand e approvazione delle illustrazioni; registro iniziale delle immagini |\n| 1.1 | Ufficiale | Introdotto il modello standard a prevalenza didattica delle schede; aggiunta la scheda pilota del Tessitore di Legami |

**Fine documento — TFA-BESTIARY-U v1.1**
