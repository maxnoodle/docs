# Fondamentali di Programmazione

- **Algoritmo**: Una serie di istruzioni step-by-step per eseguire un compito specifico.
- **Struttura Dati**: Modi di organizzare i dati per un accesso e una manipolazione efficienti (es. array, lista, coda, pila, albero, grafico).
- **OOP (Object-Oriented Programming)**: Paradigma di programmazione basato su "oggetti", che possono contenere dati e metodi.
- **Procedural Programming**: Un tipo di programmazione imperativa basata su procedure o funzioni.
- **Functional Programming**: Paradigma di programmazione dove il calcolo è trattato come la valutazione di funzioni matematiche.
- **TEST**: TEST.
- **Debugging**: processo di problem solving che porta alla risoluzione di errori nel codice.
- **Complessità Computazionale**: Concetto chiave che valuta le risorse (tempo, spazio) richieste da un algoritmo. Comprendere la complessità computazionale è fondamentale per progettare algoritmi efficienti.

# Sviluppo Web

- **HTML/CSS/JavaScript**: Tecnologie di base per lo sviluppo web; HTML per la struttura, CSS per lo stile, e JavaScript per la funzionalità.
- **Front-End**: Parte dell'applicazione web con cui l'utente interagisce direttamente.
- **Back-End**: Parte dell'applicazione responsabile per la gestione dei dati, logica del server, e autenticazione.
- **API (Application Programming Interface)**: Un insieme di regole che permettono alle applicazioni di comunicare tra loro.
- **Framework e Librerie**: Strumenti come React, Angular, Vue (front-end) o Node.js, Django, Ruby on Rails (back-end) che facilitano lo sviluppo web.
- **Architettura di microservizi**: L'architettura di microservizi suddivide un'applicazione in una serie di servizi distribuibili in modo indipendente che comunicano tramite API.
- **Deploy** :  Processo di distribuzione di un'applicazione o di un sistema software in un ambiente operativo o di produzione in modo che sia accessibile e utilizzabile dagli utenti finali.
- **Responsive Design**: Progettazione di siti web che si adattano a diverse dimensioni di schermo e dispositivi.

# Database

- **SQL (Structured Query Language)**: Linguaggio standard per gestire i database relazionali.
- **NoSQL**: Database non relazionali, utilizzati per la grande scalabilità e la flessibilità nell'organizzazione dei dati.
- **CRUD (Create, Read, Update, Delete)**: Le quattro operazioni di base dei dati.

# Controllo Versione

- **Git**: Sistema di controllo versione per tracciare i cambiamenti nel codice sorgente.
- **Repository**: Raccolta di codice sorgente, documentazione, file di configurazione, ecc.
- **Fork**: Copia di un repository che ci permette di sperimentare qualsiasi cambiamento vogliamo senza modificare il progetto principale.
- **Pull Request**:  Una richiesta per integrare le modifiche apportate in un branch in un altro, spesso utilizzato in collaborazione con altri sviluppatori.
- **GitHub**: Un servizio di hosting per progetti software, implementazione dello strumento di Git.
- **Commit**: Snapshot (istantanea) del repository in uno specifico momento nel tempo. 
- **Merge**: Comando che serve a combinare più sequenze di commit in una cronologia unificata. Nei casi d’uso più frequenti, git merge viene utilizzato per combinare due branch.

# Testing e Debugging

- **Unit Testing**: Test di singole parti (unità) di codice.
- **Integration Testing**: Test su come diverse parti del sistema lavorano insieme.
- **Debugging**: Processo di individuazione e risoluzione di errori o bug nel codice.

# Principi di Sviluppo

- **Agile**: Metodologia di sviluppo software che enfatizza la consegna incrementale, collaborazione, adattabilità, e riflessione continua.
- **Waterfall**: La metodologia waterfall prevede una gestione sequenziale dei progetti, suddivisa in fasi distinte.
- **DevOps**: Pratica che punta all'unificazione dello sviluppo software (Dev) e delle operazioni IT (Ops).
- **Clean Code**: La scrittura di codice leggibile, manutenibile e comprensibile, seguendo principi come la chiarezza e la modularità.
- **Machine Learning**: Sottocampo dell’Intelligenza Artificiale che si concentra sulla creazione di modelli e algoritmi che permettono ai computer di apprendere dai dati e fare previsioni o prendere decisioni

# Data science

- **Data mining**: Il data mining è un processo di estrazione di conoscenza dai dati. I data miner utilizzano tecniche statistiche e algoritmi di machine learning per identificare pattern e relazioni nei dati.
- **Data visualization**: La data visualization è il processo di rappresentazione dei dati in modo visivo. I grafici, i diagrammi e le mappe sono tutti esempi di visualizzazione dei dati.

# Sicurezza
- **Crittografia**:  Conversione dei dati da un formato leggibile in un formato codificato che può essere letto o elaborato solo dopo che è stato,La crittografia è usata in molte applicazioni come le carte per le transazioni bancarie, le password dei computer e le transazioni di commercio elettronico. 
-**Cybersecurity**: Insieme di tecnologie, processi e misure di protezione progettate per ridurre il rischio di attacchi informatici.
- **Autenticazione e Autorizzazione**: Processi che controllano chi può accedere a un sistema o a una risorsa e cosa può fare.
- **Firewall**: Dispositivo di sicurezza che monitora e controlla il traffico di rete.
- **Penetration Testing**: Attività mirata a testare la sicurezza di un sistema simulando attacchi reali per identificare vulnerabilità.
- **SQL Injection**: È un tipo di attacco che inietta del codice malevolo all’interno di un database, solitamente sfruttando una vulnerabilità del software.


# Data science
- **Machine learning**: apprendimento automatico dei dati
- **Data mining**: estrazione di conoscenza dai dati
- **Data visualization**: rappresentazione visiva dei dati


# Performance e Ottimizzazione

- **Scalabilità**: Capacità di un sistema di gestire un crescente numero di richieste.
- **Ottimizzazione**: Migliorare l'efficienza del codice o delle risorse del sistema.
- **Concorrenza**: Capacità di un sistema di gestire più attività contemporaneamente, consentendo loro di avanzare in modo apparentemente simultaneo.
- **Parallelismo**: Esecuzione effettiva di più attività allo stesso momento, generalmente distribuite tra diverse risorse di elaborazione.

# Cloud Computing

- **IAAS, PAAS, SAAS**: Diversi livelli di servizi cloud (Infrastruttura, Piattaforma, Software come Servizio).
- **Provider Cloud**: Servizi come AWS, Azure, Google Cloud che offrono risorse di computing su internet.

# Hardware Virtualization
- **Full Virtualization**: tutto dall'Host viene "Virtualizzato", usualmente risultando in performance peggiori.
- **Paravirtualization**: Host e Guest comunicano tra di loro attraverso APIs specifiche, risultando in performance migliori. L'host dovrà comunque offrire supporto kernel.
- **OS Level Virtualization**: usato per esempio da docker, l'Host permette instanze multiple di virtualizzazione, chiamate "containers", che hanno accesso a determinati set di risorse sia per motivi di sicurezza, sia per motivi di perfomance. Questo comporta minor "overhead", ma sia Host che Guest devono girare sullo stesso OS.