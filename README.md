# QuickStatik 📐

**QuickStatik** è uno strumento software didattico progettato per l'analisi e la risoluzione di travi isostatiche a singola asta orizzontale. Pensato specificamente per l'apprendimento della Scienza delle Costruzioni, è la soluzione ideale per studenti che necessitano di comprendere e verificare il comportamento statico delle strutture, calcolando le reazioni vincolari e visualizzando i diagrammi delle sollecitazioni interne in modo semplice e intuitivo.

## 🚀 Funzionalità Principali

Il programma offre un set completo di strumenti per definire e analizzare una struttura:

### 1. Geometria della Trave

* **Lunghezza Personalizzata**: Definisci la lunghezza esatta della trave su cui operare.

### 2. Gestione dei Vincoli

Puoi inserire i seguenti tipi di vincoli e posizionarli liberamente lungo l'asse della trave:

* **Incastro**: Impedisce traslazione (orizzontale e verticale) e rotazione.
* **Cerniera (Appoggio Fisso)**: Impedisce la traslazione orizzontale e verticale, ma consente la rotazione.
* **Carrello (Appoggio Mobile)**: Impedisce la traslazione perpendicolare all'asse di scorrimento, consentendo traslazione parallela e rotazione.

### 3. Applicazione dei Carichi

Aggiungi una varietà di carichi per simulare condizioni reali:

* **Forze Concentrate**: Applica forze puntuali in qualsiasi punto, con la possibilità di specificarne l'**inclinazione** (rotazione).
* **Momenti Concentrati**: Inserisci momenti puri lungo la trave.
* **Carichi Distribuiti**:
   * **Uniformi (rettangolari)**: Carichi costanti su una porzione della trave.
   * **A Variazione Lineare (triangolari/trapezioidali)**: Carichi la cui intensità varia linearmente tra due punti.

## 📊 Calcolo e Visualizzazione

Una volta definito il sistema, QuickStatik esegue i calcoli statici e ne fornisce una rappresentazione grafica chiara e immediata, permettendo agli studenti di verificare i propri calcoli manuali e comprendere meglio il comportamento strutturale.

### Calcoli Eseguiti

* **Equazioni di Equilibrio**: Risolve il sistema di equazioni di equilibrio statico (ΣF_x=0, ΣF_y=0, ΣM=0) per la struttura definita.
* **Calcolo delle Reazioni**: Determina i valori numerici delle componenti di reazione (forze e momenti) per ogni vincolo presente.

### Diagrammi delle Sollecitazioni Interne

Il tool genera i tre diagrammi fondamentali per l'analisi della trave:

* **Sforzo Normale (N)**: Rappresentazione grafica dello sforzo assiale lungo la trave.
* **Sforzo di Taglio (T)**: Visualizzazione della distribuzione delle forze di taglio.
* **Momento Flettente (M)**: Diagramma del momento flettente lungo l'intera trave.

## 🛠️ Workflow di Utilizzo

L'utilizzo del programma segue un flusso di lavoro logico e semplice, ideale per l'apprendimento progressivo:

1. **Avvia QuickStatik**.
2. **Definisci la Geometria**: Imposta la lunghezza totale della trave.
3. **Posiziona i Vincoli**: Aggiungi i vincoli necessari (es. una cerniera e un carrello) specificando la loro posizione.
4. **Aggiungi i Carichi**: Inserisci forze, momenti o carichi distribuiti, configurandone posizione, intensità e (se applicabile) orientamento.
5. **Analizza i Risultati**:
   * Leggi i valori numerici delle **reazioni vincolari**.
   * Esplora i **diagrammi grafici** di Sforzo Normale, Taglio e Momento per comprendere il comportamento della struttura sotto carico.
   * Confronta i risultati con i calcoli svolti manualmente per verificare la correttezza del procedimento.
