# Portfolio Progetti di Ingegneria Aerospaziale

Benvenuti nel mio portfolio di progetti accademici ed elaborati, sviluppati durante il mio percorso di Laurea Magistrale in Ingegneria Aerospaziale presso l'Università degli Studi della Campania "Luigi Vanvitelli". Questo repository illustra le mie competenze tecniche e analitiche in diverse aree chiave dell'ingegneria aerospaziale, con un focus particolare su dinamica del volo, sistemi di controllo, astrodinamica e analisi numerica e strutturale.

---

## Competenze Chiave Acquisite:

* **Sistemi di Controllo Avanzati:** Progettazione, taratura e validazione di controllori (PID, LQR, LQI, MPC), stima d'assetto e navigazione (Filtri di Kalman Lineare), analisi di stabilità e robustezza.
* **Dinamica del Volo e Aerodinamica:** Analisi di stabilità dinamica longitudinale e latero-direzionale, modellazione di modi caratteristici (Fugoide, Corto Periodo, Rollio, Spirale, Dutch Roll), analisi di Mach critico, progettazione preliminare di velivoli, studio di profili alari e ali finite, fenomenologia dello stallo e soluzioni correttive (svergolamento, rastremazione).
* **Astrodinamica e Sistemi Spaziali:** Analisi di missione satellitare (es. orbite Sun-Synchronous, propagazione orbitale con effetti J2), valutazione del Ground Track e analisi di moduli radar SAR (Swath, effetto Doppler, tempo di integrazione).
* **Rientro Atmosferico e Aerotermodinamica Ipersonica:** Analisi di corridoi e traiettorie di rientro (balistico e portante), valutazione di carichi termici e strutturali, applicazione della teoria Newtoniana e simulazioni CFD (Ansys Fluent, ICEM CFD).
* **Analisi Strutturale (FEM):** Competenza nel Metodo degli Elementi Finiti (FEM) utilizzando **Abaqus** per analisi in deformazione piana/tensione piana, assialsimmetriche, di buckling lineare e termomeccaniche di componenti aeronautici (sezioni di fusoliera, pannelli rinforzati, sezioni alari).
* **Progettazione e Verifica Strutturale:** Calcolo di carichi critici, flussi di taglio, tensioni normali e verifica di componenti strutturali (pannelli rinforzati, cassoni alari, ordinate di forza) sotto varie condizioni di carico utilizzando approcci a elementi concentrati.
* **Metodi Numerici:** Implementazione di tecniche di integrazione numerica (metodi di Newton-Cotes, Gauss).
* **Analisi Dati e Statistica:** Statistica descrittiva, test di indipendenza, intervalli di confidenza e regressione multipla per modellazione predittiva.
* **Modellazione e Simulazione Numerica:** Ampia esperienza con **MATLAB/Simulink** (avanzato), Ansys Fluent (intermedio, CFD), XFoil (intermedio), AVL (intermedio), **Abaqus** (intermedio, FEA).
* **Programmazione:** MATLAB (avanzato), conoscenze di base di Python e C++.

---

## Progetti Dettagliati:

### **Aerodinamica**

Questa sezione include elaborati e analisi approfondite sul comportamento aerodinamico di profili alari e velivoli completi, esplorando sia le fondamenta teoriche che le applicazioni pratiche.

* **[Elaborato Aerodinamica Ipersonica (AEIP)](AERODINAMICA/elaborato%20AEIP.pdf)**
    * **Contenuto:** Analisi di prefattibilità di una missione di rientro dallo spazio con la capsula Orion. Studio del **corridoio di rientro** (limiti termici, di pressione dinamica e aerodinamici) e **traiettorie di rientro** (balistico e portante) con modelli di atmosfera isotermo e standard. Valutazione di flussi termici, accelerazioni e tempi di volo. Include inoltre un'analisi aerodinamica dello **Space Shuttle Orbiter** in condizioni ipersoniche, confrontando i risultati ottenuti tramite la **Teoria Newtoniana (software Hyper)** e **simulazioni CFD (Ansys Fluent, ICEM CFD)**.
    * **Competenze:** Aerodinamica ipersonica, rientro atmosferico, termodinamica, CFD, analisi numerica, modellazione atmosferica, MATLAB.

* **[Elaborato Aerodinamica dei Velivoli](AERODINAMICA/elaborato_arico_ludovico.pdf)**
    * **Contenuto:** Studio delle polari aerodinamiche di profili alari **NACA 2412 e NACA 632415** tramite **xFoil**, analizzando gli effetti del numero di Reynolds, deflessione di flap e slat. Confronto dei risultati con dati sperimentali (tavole di Abbott). Calcolo del **Mach critico inferiore** per diversi profili. Applicazione della **teoria della linea portante di Prandtl (software AVL)** per l'analisi di ali finite (distribuzione di portanza, carico di portanza, angolo d'attacco indotto). Valutazione del **sentiero di stallo** e delle soluzioni correttive (rastremazione, svergolamento). Include un'analisi **CFD Euleriana** di un velivolo N2A.
    * **Competenze:** Aerodinamica subsonica e transonica, stallo, progettazione alare, analisi di profili, MATLAB, xFoil, AVL, Ansys Fluent (CFD), generazione mesh (ICEM CFD).

### **Costruzioni Aeronautiche**

Questa sezione descrive progetti di analisi e progettazione strutturale di componenti aeronautici, concentrandosi su diverse condizioni di carico e metodi di simulazione numerica tramite FEM.

* **[Progetto Corso Costruzioni Aeronautiche, Modulo 1](relazione_csaer_mod1_arico_241216_180635.pdf)**
    * **Contenuto:** Determinazione del **carico critico di un pannello rinforzato** con rinforzi a T, utilizzando un approccio a elementi concentrati. Analisi del **carico torsionale e flesso-torsionale** su un cassone alare, inclusa la distribuzione dei flussi di taglio e i fenomeni di warping. Verifica di una struttura di cassone alare sotto momento flettente e forze di taglio, calcolando le tensioni normali nelle solette e i flussi di taglio nelle anime. Analisi strutturale di un'ordinata di forza di un aeromobile sotto carichi esterni, determinando gli stati tensionali e verificando il rispetto dei limiti di resistenza del materiale.
    * **Competenze:** Meccanica strutturale, analisi di buckling, analisi di sforzi e deformazioni, flussi di taglio, analisi torsionale, metodo a elementi concentrati.

* **[Progetto Corso Costruzioni Aeronautiche, Modulo 2](relazione_csaer2_ARICO.pdf)**
    * **Contenuto:** Analisi agli Elementi Finiti (FEA) tramite **Abaqus** per vari problemi strutturali:
        * **Analisi in Deformazione Piana:** Studio di una sezione di fusoliera sotto pressione interna, confrontando modelli 2D (plane strain) e 3D per validare l'efficienza computazionale.
        * **Analisi in Tensione Piana:** Analisi strutturale di una forcella, confrontando modelli 2D (plane stress) e 3D.
        * **Analisi Assialsimmetrica:** Studio di tre strutture assialsimmetriche sotto pressione interna, valutando la distribuzione degli sforzi.
        * **Analisi di Buckling Lineare:** Determinazione dei carichi critici di instabilità e dei modi di deformazione per un pannello irrigidito con rinforzi a T.
        * **Analisi Termomeccanica:** Studio di una semiala (materiale Inconel) sottoposta a carichi termici, valutando spostamenti, tensioni di Von Mises e distribuzione della temperatura nel tempo.
    * **Metodi Numerici di Integrazione:** Confronto dei metodi di **Newton-Cotes (regola di Simpson)** e **Gauss (con 2, 3 e 4 punti)** per l'integrazione numerica, valutando accuratezza ed errore.
    * **Competenze:** Analisi agli Elementi Finiti (FEA), Abaqus, meccanica strutturale, analisi di sforzi, buckling, termomeccanica, integrazione numerica.

### **Controllo di Volo**

Progetti focalizzati sulla progettazione e simulazione di sistemi di controllo per velivoli, inclusi modelli matematici e strategie di pilotaggio automatico.

* **[Progetto Sistemi di Controllo di Volo 2 (SCV2)](CONTROLLO%20DI%20VOLO/Progetto_SCV2.pdf)**
    * **Contenuto:** Progettazione e implementazione di **controllori LQR (Linear Quadratic Regulator)** e **LQI (Linear Quadratic Integral)** per la stabilizzazione e l'inseguimento di riferimenti (velocità, angolo di beccheggio) per un velivolo. Analisi della risposta temporale del sistema a fronte di condizioni iniziali perturbate e segnali di ingresso a gradino. Verifica della robustezza del controllore su **modelli non lineari** con inclusione di rumore. Dettagli sulla scelta e l'impatto delle matrici di peso `Q` e `R`. Include lavori preliminari su **Model Predictive Control (MPC)** e **Filtro di Kalman** per la stima dello stato.
    * **Implementazione:** Uso estensivo di **MATLAB/Simulink** per la modellazione e la simulazione.
    * **Competenze:** Controllo ottimo (LQR, LQI, MPC), stima dello stato (Filtro di Kalman), sistemi dinamici, modellazione e simulazione (Simulink), analisi di robustezza, stabilità, risposta dinamica.

### **Dinamica e Progetto di Velivoli**

Elaborati che approfondiscono l'analisi della stabilità dinamica, i modi di volo e la qualità di volo di aeromobili, includendo studi di sensitività e analisi di perturbazioni.

* **[Elaborato Dinamica e Progetto di Velivoli (DPGV)](DINAMICA%20E%20PROGETTO%20DI%20VELIVOLI/Elaborato_DPGV_Arico.pdf)**
    * **Contenuto:** Analisi dettagliata delle **dinamiche longitudinali e latero-direzionali** di un velivolo (McDonnell Douglas F-4) tramite l'utilizzo di derivate di stabilità e modelli a spazio di stato. Studio dei **modi caratteristici** (Fugoide, Corto Periodo, Rollio, Spirale, Dutch Roll) in termini di smorzamento, frequenza naturale e rappresentazione fasoriale. Analisi della **qualità di volo** secondo standard (es. Livelli di MIL-STD). Studio del **luogo delle radici** al variare del margine statico. Approfondimento del **rollio rapido** e degli accoppiamenti inerziali (Diagramma di Philips), e risposta a **turbolenze atmosferiche** (raffiche istantanee e 1-cos, Wind Shear).
    * **Competenze:** Dinamica del volo, stabilità e controllo, analisi dei modi di volo, qualità di volo, analisi di sensitività, simulazione dinamica.

### **Probabilità e Statistica per l'Ingegneria**

Questo progetto dimostra l'applicazione di metodologie statistiche e di analisi dei dati, competenze fondamentali per l'ingegneria, in particolare in contesti dove la gestione dell'incertezza e la modellazione predittiva sono cruciali.

* **[Progetto d'Esame di Probabilità e Statistica](PROBABILITA'%20E%20STATISTICA/progetto_1_2.pdf)**
    * **Contenuto:** Analisi statistica di un dataset (dati immobiliari) tramite:
        * **Statistica Descrittiva:** Descrizione delle variabili, analisi delle distribuzioni (es. numero di piani, bagni, camini), calcolo di misure di tendenza centrale e dispersione (minimo, massimo, media, deviazione standard).
        * **Test di Ipotesi:** Esecuzione di test di indipendenza tra variabili (es. bagni e camini) e test d'ipotesi sulla media tra due popolazioni (basate su codici ZIP).
        * **Intervalli di Confidenza:** Calcolo e interpretazione di intervalli di confidenza per la media di variabili chiave (es. area piano terra, valore totale proprietà).
        * **Regressione Multipla:** Costruzione e valutazione di un modello di regressione multipla per prevedere il valore totale di una proprietà, analizzando la significatività delle variabili (p-value) e la bontà del modello (R-squared).
    * **Tecnologie:** Tutte le analisi e visualizzazioni grafiche (istogrammi, boxplot, scatter plot) implementate utilizzando **MATLAB**.
    * **Rilevanza per l'Aerospazio:** Le competenze dimostrate in questo progetto (analisi dei dati, statistica inferenziale, modellazione predittiva) sono direttamente applicabili in ambito aerospaziale per la gestione di dati di telemetria, stima di parametri (es. determinazione dell'orbita), analisi di performance e valutazione dell'incertezza in sistemi complessi.

### **Sistemi Spaziali**

Questa sezione si concentra sulla progettazione e l'analisi di sistemi e veicoli spaziali, con un'attenzione particolare alle dinamiche orbitali e al funzionamento dei sensori.

* **[Progetto Sistemi Spaziali 2 (SAS2)](SISTEMI%20SPAZIALI/sas2_progetto.pdf)**
    * **Contenuto:** Analisi di missione del satellite **COSMO-SkyMed 1**. Simulazione della **propagazione orbitale** (modello Kepleriano e con effetti J2) e valutazione della **traccia a terra (Ground Track)**. Analisi delle performance di un **modulo radar SAR** a bordo del satellite, inclusa la calibrazione dello **Swath** (Azimuth e Range), l'**effetto Doppler** (con e senza Yaw Steering), la velocità del fascio e il **tempo di integrazione**.
    * **Competenze:** Astrodinamica, meccanica orbitale, sistemi satellitari, radar imaging, MATLAB.

---

**Contatti:**

Per qualsiasi domanda o ulteriore informazione sui miei progetti, non esitate a contattarmi:

* **LinkedIn:** [linkedin.com/in/ludoaric](https://www.linkedin.com/in/ludoaric)
* **Email:** [ludovico.arico@gmail.com](mailto:ludovico.arico@gmail.com)
* **Profilo GitHub:** [github.com/ludoaric](https://github.com/ludoaric) 
