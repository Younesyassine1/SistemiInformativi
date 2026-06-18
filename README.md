# TEORIA DEI SISTEMI INFORMATIVI

### 1. Il Contesto e l'Organizzazione
L'organizzazione e le sue componenti si strutturano secondo una precisa gerarchia piramidale e sistemica (dal macro al micro):
**Ambiente Esterno** $\rightarrow$ **Organizzazione** $\rightarrow$ **Sistema Organizzativo** $\rightarrow$ **Sistema Informativo** $\rightarrow$ **Sistema Informatico**.

* **Sistema Organizzativo:** È formalmente definito come una coppia composta da **Risorse** (umane, finanziarie, materiali, tecnologiche) e **Regole/Processi** (norme per lo svolgimento coordinato delle attività aziendali) volte al raggiungimento degli obiettivi dell'organizzazione.
* **La Piramide della Conoscenza:**
    * **Dato:** Elemento di base neutro, oggettivo e grezzo (es. un numero o una data isolata). Da solo non ha significato e non permette alcuna comprensione.
    * **Informazione:** Insieme di dati combinati, strutturati e contestualizzati. Esprime una valenza soggettiva e fornisce un reale significato a chi la riceve.
    * **Conoscenza:** Deriva dall'apprendimento, dalla metabolizzazione e dall'interiorizzazione delle informazioni da parte dell'utente. Ne accresce il patrimonio cognitivo consentendo l'azione e la scelta decisionale.

---

### 2. La Risorsa Informazione e le sue Leggi Economiche
L'informazione all'interno dei sistemi aziendali non è una risorsa fisica tradizionale, ma risponde a precise "leggi" e proprietà immateriali ed economiche:
1.  **Non rivalità (o Espandibilità):** L'uso di un'informazione da parte di un soggetto non ne riduce la disponibilità o l'utilità per gli altri. Più persone possono fruirne simultaneamente.
2.  **Costo di riproduzione asimmetrico:** Produrre la prima unità di informazione (la "matrice") comporta costi fissi altissimi, mentre la sua duplicazione e distribuzione ha un costo marginale quasi nullo.
3.  **Inesauribilità:** L'informazione non si consuma né si deteriora fisicamente con l'uso; al contrario, lo scambio tende a rigenerare e incrementare il valore del patrimonio conoscitivo.
4.  **Dipendenza dal contesto (Soggettività):** Il valore di un'informazione è strettamente legato al contesto interpretativo del ricevente.
5.  **Deterioramento temporale (Obsolescenza):** Molte tipologie di informazioni perdono rapidamente valore economico e strategico con il passare del tempo.
6.  **Asimmetria informativa:** Situazione in cui determinati attori dispongono di informazioni più accurate o tempestive rispetto ad altri, condizionando il potere decisionale.

---

### 3. Il Ciclo di Vita dei Sistemi Informativi
La vita di un sistema informativo si sviluppa in 7 fasi iterative, supervisionate dalle attività di **Project Management**:
1.  **Studio di fattibilità:** Analisi preliminare e bilancio costi/benefici.
2.  **Analisi dei requisiti:** Individuazione di cosa il sistema deve fare e dei bisogni degli utenti.
3.  **Progettazione:** Definizione architetturale (strutturazione dati, logica e interfacce).
4.  **Realizzazione e Testing:** Fase di codifica software e collaudo.
5.  **Conduzione e Manutenzione:** Messa in opera del sistema (può essere correttiva, evolutiva o adattativa).
6.  **Assessment:** Valutazione complessiva delle prestazioni e del raggiungimento degli obiettivi.
7.  **Reingegnerizzazione dei processi:** Studio dei processi per ridefinirli da zero, fornendo l'input per il successivo ciclo di vita.

---

### 4. L'Analisi dello Scenario e la Catena del Valore di Porter
Per mappare accuratamente la realtà aziendale in fase di analisi, si adotta il modello della **Catena del Valore di Porter**. Questo framework **individua e classifica i processi aziendali in base al trasferimento di valore**, con l'obiettivo di massimizzare il *Margine* finale dell'azienda.

I processi si dividono in due macro-categorie:

#### A. Processi Primari (o Principali)
Includono i flussi che incidono direttamente sulla creazione, vendita e assistenza del prodotto/servizio:
* **Logistica in entrata:** Ricevimento, stoccaggio e gestione delle materie prime.
* **Attività Produttive:** Processi di trasformazione degli input nei prodotti o servizi finali.
* **Logistica in uscita:** Raccolta, stoccaggio e distribuzione fisica dei prodotti finiti.
* **Marketing e Vendite:** Promozione del prodotto e gestione commerciale.
* **Servizi post vendita:** Assistenza, customer care e manutenzione per mantenere il valore del prodotto.

#### B. Processi di Supporto
Sostengono trasversalmente le attività primarie fornendo le risorse necessarie:
* **Approvvigionamenti:** Acquisto di risorse (materie prime, macchinari, computer, ecc.).
* **Gestione Risorse Umane:** Reclutamento, formazione, valutazione e retribuzione del personale.
* **Sviluppo Tecnologie:** Ricerca e sviluppo, innovazione di processo/prodotto, software.
* **Gestione Infrastrutture:** Direzione generale, amministrazione, contabilità e affari legali.

---

### 5. Specifica dei Requisiti
I requisiti raccolti si dividono in:
* **Requisiti Funzionali:** Esprimono i servizi e le funzionalità che il sistema *deve offrire* agli utenti. Si categorizzano in **MUST** (obbligatori), **SHOULD** (raccomandati), **MAY** (opzionali).
* **Requisiti Non Funzionali:** Rappresentano le proprietà e i vincoli che il sistema *deve rispettare* per operare bene (es. sicurezza, efficienza, portabilità, multilingua).

---

### 6. La Progettazione: Diagrammi, Logica e Interfacce
* **DFD (Data Flow Diagram):** Mostra come i dati vengono catturati, trasformati e distribuiti (*Processi*, *Flussi di dati*, *Archivi/Data Store* ed *Entità Esterne*).
* **UML - Casi d'Uso (Use Case Diagram):** Descrive l'interazione tra *Attori* e sistema. Include relazioni di *Inclusione* (obbligatoria) ed *Estensione* (opzionale, al verificarsi di una condizione).
* **UML - Diagrammi delle Attività:** Descrivono flussi di lavoro complessi, usando le corsie (**Swimlanes** o Partizioni) per attribuire le responsabilità.
* **Logica di Business:** Non contiene codice, ma definisce una vista astratta di classi e metodi (es. operazioni CRUD).
* **Modellazione delle Interfacce:** Utilizza i **Mockup** (bozze grafiche statiche) e i **Diagrammi di navigazione** (percorsi logici tra le schermate).

---

### 7. Evoluzione dei Sistemi Informativi: Forrester vs Anthony
* **Visione di Forrester:** Il sistema informativo ha un ruolo di standardizzazione, *monitoraggio e controllo* delle attività aziendali.
* **Visione di Anthony:** Il sistema informativo è fulcro di *supporto decisionale*. La **Piramide di Anthony** divide i processi decisionali in tre livelli:
    1.  **Processi Operativi (Base):** Lavoro quotidiano (sistemi transazionali **OLTP**).
    2.  **Processi Gestionali / Tattici (Centro):** Controllo e allocazione risorse (sistemi **MIS**).
    3.  **Processi Direzionali / Strategici (Cima):** Scelte a lungo termine (sistemi analitici **OLAP**, come Data Warehouse e **DSS/ESS**).

---

### 8. Architetture Dati Evolute: Big Data e NoSQL
I sistemi relazionali tradizionali faticano a gestire i **Big Data** (dati con enormi *Volumi*, *Velocità* e *Varietà*). Da qui nascono i database **NoSQL** (*Not Only SQL*).

Nascono principalmente per tre motivi:
1.  Gestione dei Big Data e scalabilità orizzontale.
2.  Superamento dei limiti e della rigidità dei DB Relazionali (schema-less).
3.  **Teorema CAP:** Principio per cui un sistema distribuito non può garantire simultaneamente Consistenza, Disponibilità e Tolleranza alle partizioni, forzando dei compromessi.

Le 4 grandi famiglie NoSQL sono:
* Chiave-Valore
* Orientati alle Colonne
* Orientati ai Grafi
* **Orientati ai Documenti:** (es. MongoDB). Archiviano i dati in documenti flessibili (JSON). Perfetti per relazioni 1:1 o gerarchiche grazie all'uso di *sub-documents* integrati.
