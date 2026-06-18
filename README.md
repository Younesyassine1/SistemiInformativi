# RIASSUNTO DEFINITIVO: TEORIA DEI SISTEMI INFORMATIVI

### 1. Il Contesto e l'Organizzazione
L'organizzazione e le sue componenti si strutturano secondo una precisa gerarchia (dal macro al micro):
**Ambiente Esterno** comprende l'**Organizzazione**, che al suo interno definisce un **Sistema Organizzativo**, il quale è supportato da un **Sistema Informativo**, che a sua volta utilizza (se automatizzato) un **Sistema Informatico**.

* **Sistema Organizzativo:** È costituito dall'insieme delle **Risorse** (umane, finanziarie, materiali, informative) e dalle **Regole/Processi aziendali** volti al raggiungimento degli obiettivi.
* **Dato vs Informazione vs Conoscenza:**
    * **Dato:** È l'elemento di base, oggettivo e grezzo, che da solo non permette alcuna comprensione.
    * **Informazione:** È un insieme di dati combinati e contestualizzati, che esprimono soggettività e hanno un significato per chi li riceve.
    * **Conoscenza:** Deriva dall'apprendimento e dalla metabolizzazione dell'informazione; aumenta il patrimonio conoscitivo dell'utente permettendogli di prendere decisioni.

### 2. Il Ciclo di Vita dei Sistemi Informativi
La vita di un sistema informativo si sviluppa in fasi iterative (ciclo), supervisionate costantemente dal **Project Management**:
1.  **Studio di fattibilità:** Valutazione iniziale dei costi/benefici.
2.  **Analisi dei requisiti:** Capire cosa il sistema deve fare.
3.  **Progettazione:** Definizione di dati, logica e interfacce (come lo farà).
4.  **Realizzazione e Testing (Implementazione/Collaudo):** Scrittura del codice e verifica.
5.  **Conduzione e Manutenzione:** Messa in opera e correzione bug.
6.  **Assessment:** Valutazione del raggiungimento degli obiettivi e delle performance.
7.  **Reingegnerizzazione:** Ridefinizione dei processi per migliorarne l'efficienza nel ciclo successivo.

### 3. Analisi dei Requisiti e Catena del Valore
Per progettare un sistema, bisogna prima mappare i processi dell'azienda utilizzando la **Catena del Valore di Porter**, che divide i processi in due macro-categorie:
* **Processi Principali (Primari):** Logistica in entrata, attività operative, logistica in uscita, marketing e vendite, servizi (post-vendita).
* **Processi di Supporto:** Approvvigionamento, gestione delle risorse umane, sviluppo tecnologico, gestione delle infrastrutture.

I requisiti del sistema si dividono in:
* **Requisiti Funzionali:** Esprimono i servizi e le funzionalità che il sistema *deve offrire* agli utenti (es. "inserire un ordine"). Si classificano in MUST (obbligatori), SHOULD (raccomandati), MAY (opzionali).
* **Requisiti Non Funzionali:** Rappresentano i vincoli (tecnologici, di sicurezza, di usabilità) che il sistema *deve rispettare* al fine di funzionare bene (es. "database criptato", "multilingua").

### 4. La Progettazione: Diagrammi, Logica e Interfacce
Durante la progettazione si usano diversi diagrammi e strumenti:
* **DFD (Data Flow Diagram):** Per mostrare come fluiscono i dati tra processi, archivi (data store) e attori esterni.
* **Diagrammi dei Casi d'Uso (Use Case UML):** Per mostrare l'interazione tra attori e funzionalità del sistema.
* **Diagrammi delle Attività (UML):** Per descrivere flussi di lavoro complessi, usando anche corsie (swimlanes) per definire chi fa cosa.
* **Logica di Business:** Non contiene codice vero e proprio, ma fornisce una visione astratta delle classi e dei metodi software (es. operazioni CRUD: Create, Read, Update, Delete).
* **Modellazione delle Interfacce:** Utilizza i **Mockup** per avere una rappresentazione visiva (bozza) di come dovrà essere l'interfaccia grafica, e i **Diagrammi di navigazione** per illustrare come l'utente si sposterà tra le varie schermate (form).

### 5. Evoluzione dei Sistemi Informativi (Forrester vs Anthony)
* **Visione di Forrester:** Inizialmente, il sistema informativo veniva visto solo come uno strumento di *monitoraggio e controllo* delle attività aziendali standard.
* **Visione di Anthony:** Oltre alla funzione operativa, assegna al sistema informativo un ruolo fondamentale nel *supporto alle decisioni*. Ha teorizzato la **Piramide di Anthony**, che divide i processi aziendali in tre livelli:
    1.  **Operativi (Base):** Lavoro quotidiano. Supportati dai Sistemi Operazionali (OLTP).
    2.  **Gestionali / Tattici (Centro):** Controllo risorse e middle-management. Supportati da MIS (Management Information Systems).
    3.  **Direzionali / Strategici (Cima):** Decisioni a lungo termine. Supportati dai Sistemi Decisionali (OLAP), come i DSS (Decision Support Systems) appoggiati ai *Data Warehouse*, e gli ESS (Executive Support Systems).

### 6. Nuove Tecnologie: Big Data e NoSQL
I database tradizionali (relazionali) faticano a gestire i **Big Data** (dati caratterizzati da enormi Volumi, Velocità e Varietà). Per questo nascono i sistemi **NoSQL** (Not Only SQL).
Nascono principalmente per tre motivi:
1.  Gestione dei Big Data.
2.  Limitazioni di scalabilità dei DB Relazionali.
3.  **Teorema CAP:** Principio per cui un sistema distribuito non può garantire contemporaneamente Consistenza, Disponibilità e Tolleranza alle partizioni, forzando a fare dei compromessi.

I NoSQL si dividono in quattro grandi famiglie:
* Chiave-valore
* **Orientati ai documenti** (su cui il corso si sofferma, es. MongoDB, ideali per relazioni 1:1 e senza schemi rigidi)
* Orientati ai grafi
* Orientati alle colonne
