# Data Science e Machine Learning: esercizi Kaggle
Questo repository raccoglie una selezione mirata degli esercizi più significativi svolti all'interno dei corsi di formazione Kaggle che ho completato. L'obiettivo di questa raccolta è dimostrare l'applicazione pratica del linguaggio Python attraverso l'intero ciclo di analisi del dato: dall'esplorazione iniziale statistico-visiva fino alla costruzione di modelli predittivi avanzati di Machine Learning, passando per la manipolazione delle features.

---

## 📂 Progetti Selezionati

### 📊 1. Analisi Esplorativa Visiva e Distribuzione Dati (Data Visualization)
*   **File:** `01_distribuzione_dati_clinici.ipynb`
*   **Obiettivo:** Esplorare un dataset clinico contenente le misurazioni geometriche estratte da immagini microscopiche di tumori al seno, analizzando le differenze strutturali tra masse benigne e maligne.
*   **Competenze applicate:**
    *   Generazione e confronto di istogrammi e grafici di densità tramite **KDE Plots** (Kernel Density Estimate) per evidenziare come variano le dimensioni a seconda della diagnosi.
    *   Identificazione visiva di soglie critiche utilizzabili dagli algoritmi di classificazione medica per formulare una diagnosi accurata.
    *   Uso pratico delle librerie `Seaborn` e `Matplotlib` per creare figure comparative pulite ed efficaci.

### 🐼 2. Manipolazione, raggruppamento e ordinamento dei dati (Pandas)
*   **File:** `02_raggruppamento_e_ordinamento_pandas.ipynb`
*   **Obiettivo:** Esplorare un dataset reale di recensioni di vini applicando logiche di raggruppamento e ordinamento gerarchico.
*   **Competenze applicate:**
    *   Aggregazione avanzata di variabili categoriche e numeriche tramite la funzione `groupby()`.
    *   Utilizzo delle funzioni `agg()` e `value_counts()` per costruire un buon riepilogo e mappature statistiche.
    *   Gestione e navigazione di strutture dati a indici gerarchici multipli (*Multi-index*) per favorire l'interpretabilità delle informazioni.

### 🚀 3. Ottimizzazione Predittiva con XGBoost (Intermediate Machine Learning)
*   **File:** `03_ottimizzazione_modello_con_xgboost.ipynb`
*   **Obiettivo:** Costruire e ottimizzare un modello di regressione avanzato per la stima dei prezzi immobiliari (dataset Ames), massimizzando l'accuratezza e riducendo l'errore medio assoluto (MAE).
*   **Competenze applicate:**
    *   Preparazione del dataset con tecniche di codifica categoriale rapida tramite `pd.get_dummies()` (One-Hot Encoding) e allineamento strutturale delle colonne tra train e validation set.
    *   Implementazione dell'algoritmo di Gradient Boosting tramite la libreria `XGBoost`.
    *   Configurazione e fine-tuning dei principali iperparametri (`n_estimators`, `learning_rate` ed `early_stopping_rounds`) per prevenire l'overfitting.
    *   Validazione delle performance del modello attraverso il calcolo del **Mean Absolute Error (MAE)** utilizzando la libreria `Scikit-Learn`.

---
*Nota: Tutti i notebook (`.ipynb`) contengono il codice da me implementato, verificato e commentato durante le sessioni pratiche sulla piattaforma, unendo la teoria statistica all'efficienza del codice Python.*
