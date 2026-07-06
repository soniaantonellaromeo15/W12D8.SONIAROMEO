# Analisi Esplorativa dei Dati Globali COVID-19 (2022-2023) 📊
## Progetto Finale di Analisi dei Dati con Python (Epicode Exam - Prova Finale)

### 📌 Panoramica del Progetto
Questo progetto costituisce la prova finale d'esame per il modulo di Python. L'obiettivo principale è condurre un'Analisi Esplorativa dei Dati (*Exploratory Data Analysis - EDA*) sul dataset ufficiale globale della pandemia da COVID-19, fornito da *Our World in Data*.

L'analisi si concentra sulla manipolazione di un patrimonio informativo complesso per estrarre metriche temporali e geografiche, isolando specifici contesti regionali e confrontando l'andamento delle ospedalizzazioni in terapia intensiva per alcune delle principali nazioni europee.

---

### 🗃️ Fonte dei Dati
I dati utilizzati provengono dalla banca dati ufficiale open source di **Our World in Data (OWID)** relativi alla diffusione e all'impatto globale del COVID-19.

---

### 🛠️ Tech Stack & Strumenti Utilizzati
* **Python:** Linguaggio di programmazione principale utilizzato per l'intero workflow di analisi dei dati.
* **Jupyter Notebook:** Ambiente di sviluppo interattivo impiegato per la stesura del codice, dei commenti tecnici e delle visualizzazioni.
* **Pandas:** Libreria fondamentale per l'importazione, la pulizia, il filtraggio e l'aggregazione statistica dei dataset.
* **Matplotlib / Seaborn:** Librerie utilizzate per la generazione dei grafici e dei cruscotti visivi a supporto degli insight analitici.

---

### 📊 Fasi dell'Analisi e Logica del Progetto

#### 1. Data Loading & Profiling
* Ispezione iniziale del dataset per comprendere le dimensioni del file, i tipi di variabili e i metadati associati.
* Identificazione delle macro-aree geografiche e gestione delle righe di riepilogo aggregate per evitare duplicazioni nei calcoli.

#### 2. Calcolo dei Trend Globali e Regionali
* Sviluppo di funzioni per calcolare i casi cumulativi totali a livello mondiale.
* Estrazione e confronto statistico dei dati di diffusione tra i diversi continenti, calcolando metriche puntuali, medie e percentuali relative sull'impatto globale.

#### 3. Focus Europa & Analisi delle Terapie Intensive (ICU)
* Analisi approfondita di un subset temporale specifico, focalizzato sul periodo compreso tra **Maggio 2022 e Aprile 2023**.
* Selezione mirata di tre nazioni target: **Italia, Germania e Francia**.
* Confronto grafico e numerico dei pazienti ricoverati nei reparti di terapia intensiva (*ICU patients*) per intercettare i picchi di occupazione, i trend stagionali e le variazioni tra i diversi sistemi sanitari.

---

### 📁 Struttura della Repository
* `.gitattributes`
* `W12D8.SONIAROMEO (1).ipynb` — Jupyter Notebook interattivo contenente tutto il codice Python, le analisi e le visualizzazioni grafiche
* `README.md` — Documentazione del progetto

---

### 👤 Autore & Contatti
* **Autore:** Sonia Antonella Romeo
* **LinkedIn:** [Sonia Antonella Romeo](https://www.linkedin.com/in/sonia-antonella-romeo-318a6313b/)
