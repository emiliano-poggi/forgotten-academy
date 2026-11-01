# THE FORGOTTEN ACADEMY
## Protocollo dei repository individuali

**Identificativo:** TFA-REPOSITORY-PROTOCOL  
**Stato:** Ufficiale  
**Regolamento di riferimento:** TFA-RULEBOOK

---

# 1. Scopo e architettura

The Forgotten Academy utilizza due livelli di archiviazione:

1. **Repository comune** — `emiliano-poggi/forgotten-academy`, che contiene le fonti canoniche e i modelli condivisi.
2. **Repository individuale** — un repository GitHub privato creato e posseduto da ciascuno studente, che contiene lo stato della sua campagna e i suoi artefatti personali.

Ogni studente crea il proprio repository individuale. Non si utilizza una cartella condivisa nel repository comune per separare i dati degli studenti: la riservatezza è garantita dalla separazione in repository privati e dai relativi permessi.

# 2. Creazione e autorizzazione

Lo studente:

1. Crea un nuovo repository GitHub.
2. Imposta la visibilità su **Private**.
3. Sceglie un nome riconoscibile, per esempio `forgotten-academy-[identificativo]`.
4. Inserisce nel repository la struttura descritta in questo protocollo, usando i modelli del repository comune quando disponibili.
5. Condivide con il GM l'URL del repository e concede l'accesso tramite un'autorizzazione GitHub esplicita, per esempio installando l'integrazione autorizzata sul repository o aggiungendo l'identità GitHub del GM come collaboratore.

Il metodo concreto di autorizzazione dipende dalle funzionalità GitHub disponibili nell'account dello studente e dall'integrazione utilizzata dal GM. La sola condivisione dell'URL non concede accesso a un repository privato.

Lo studente mantiene la titolarità del repository e il controllo dei permessi. Può revocare l'accesso al GM. Il GM deve operare soltanto sui repository ai quali l'accesso è stato effettivamente concesso e verificato.

# 3. Struttura standard

La struttura minima raccomandata è:

```text
forgotten-academy-[identificativo]/
├── README.md
├── campaign-journal.md
├── living-world-map.md
└── artifacts/
    ├── index.md
    └── [ID-STANZA]/
        ├── grimorio/
        ├── pergamene/
        ├── runari/
        └── cristalli/
```

I nomi delle cartelle possono essere adattati, ma i contenuti devono restare identificabili e coerenti.

## 3.1 README.md

Contiene:
- identificativo scelto dallo studente;
- nome della campagna;
- collegamento al repository canonico;
- branch principale;
- data di inizializzazione;
- istruzioni per riconoscere il repository come archivio individuale.

Non inserire password, token, chiavi API o altri segreti.

## 3.2 campaign-journal.md

È la fonte di verità sullo stato didattico dello studente. Registra progressi, competenze, verifiche, evidenze, errori osservati, obiettivi, Mostri, Draghi, Oracoli e stato della campagna.

Il Journal individuale deve essere inizializzato dal modello ufficiale, senza importare risultati di altri studenti o progressi di campagne precedenti non esplicitamente autorizzati.

## 3.3 living-world-map.md

Registra esclusivamente i luoghi e i collegamenti geografici effettivamente conosciuti dal personaggio. Non sostituisce la World Map canonica e non deve essere aggiornata automaticamente in seguito a progressi didattici.

## 3.4 artifacts/

Contiene i materiali didattici effettivamente generati e conservati per lo studente. Le cartelle per categoria rispecchiano le quattro funzioni ufficiali:
- `grimorio/` — conoscenza teorica;
- `pergamene/` — organizzazione concettuale;
- `runari/` — metodi e procedimenti;
- `cristalli/` — esempi e applicazioni.

La categoria è determinata dalla funzione didattica prevalente, non dal formato del file.

## 3.5 artifacts/index.md

È l'indice di ricerca degli artefatti. Per ogni artefatto registra almeno:

| Campo | Descrizione |
|---|---|
| ID | Identificativo stabile dell'artefatto |
| Titolo | Nome riconoscibile |
| Categoria | Grimorio, Pergamena, Runario o Cristallo |
| Stanza | Identificativo della Stanza associata, se pertinente |
| Competenze | Identificativi delle competenze correlate |
| Descrizione | Funzione e contenuto |
| Percorso | Percorso relativo del file principale |
| Formati | Formati disponibili e relativi percorsi |
| Fonti | Riferimenti verificabili |
| Provenienza | Originale, derivato dal manuale o adattato |

L'indice deve contenere soltanto artefatti realmente presenti nell'archivio. Non deve registrare come creati materiali soltanto proposti o pianificati.

# 4. Procedura del GM per la gestione della campagna

All'inizio di una nuova campagna o quando cambia il contesto individuale, il GM:

1. Identifica lo studente.
2. Verifica l'associazione tra studente e repository privato.
3. Verifica che il repository sia accessibile e che la sua identità corrisponda allo studente.
4. Consulta il Campaign Journal prima di dichiarare progressi, risultati o attività in corso.
5. Consulta la Living World Map soltanto per le informazioni geografiche conosciute.
6. Consulta l'indice degli artefatti quando deve recuperare o proporre materiali.

Se il repository non è accessibile, il GM deve dichiarare il limite e chiedere allo studente di ripristinare l'autorizzazione o fornire il contenuto pertinente. Non deve ricostruire o inventare lo stato mancante.

# 5. Procedura di creazione e riutilizzo degli artefatti

Quando lo studente richiede un artefatto, il GM:

1. Identifica Stanza, competenze e funzione didattica.
2. Consulta `artifacts/index.md` per verificare se esiste già un artefatto adeguato.
3. Se esiste, lo recupera e lo riutilizza. Se serve, propone una revisione.
4. Se non esiste, prepara il contenuto e ne verifica la correttezza matematica e la coerenza con le fonti.
5. Assegna un ID stabile secondo il Catalogo ufficiale.
6. Salva il file nel percorso appropriato del repository individuale.
7. Aggiorna l'indice con metadati e percorsi verificati.
8. Verifica che il file e l'indice siano effettivamente presenti nel repository.

Una richiesta di generazione non equivale a un salvataggio. Il GM comunica il materiale come archiviato soltanto dopo aver verificato il completamento dell'operazione GitHub.

Le revisioni di un artefatto mantengono lo stesso ID, salvo che venga creato un contenuto autonomo distinto. I formati derivati (per esempio PDF e infografica dello stesso contenuto) sono collegati alla stessa scheda e non duplicano l'identità dell'artefatto.

# 6. Separazione tra archivio e valutazione

La presenza di un artefatto nel repository individuale:
- non certifica una competenza;
- non conquista una Stanza;
- non sconfigge un Mostro o un Drago;
- non libera un Oracolo;
- non modifica automaticamente il Campaign Journal.

Il Journal registra soltanto evidenze didattiche effettivamente osservate e risultati conseguiti secondo il Regolamento. L'archivio degli artefatti è una biblioteca personale liberamente consultabile, non un sistema di ricompense o valutazione.

# 7. Riservatezza e separazione dei dati

Il GM deve:
- consultare e modificare esclusivamente il repository individuale corretto;
- non copiare dati, progressi, risultati o artefatti da un repository a un altro;
- non pubblicare nel repository comune informazioni personali o contenuti individuali;
- non rendere pubblico un repository privato;
- non inserire credenziali o token nei file;
- segnalare eventuali errori di associazione prima di effettuare modifiche.

I repository individuali sono separati, ma la riservatezza effettiva dipende anche dalla corretta configurazione dei permessi GitHub e dalla gestione delle credenziali.

# 8. Cronologia e verifiche

Le modifiche persistenti devono usare commit descrittivi. Prima di aggiornare un file esistente, il GM consulta la versione corrente. Dopo la modifica verifica il contenuto aggiornato e il commit risultante.

Il GM non dichiara mai un file salvato, aggiornato o archiviato se GitHub non ha confermato l'operazione.

---

**Fine documento — TFA-REPOSITORY-PROTOCOL**
