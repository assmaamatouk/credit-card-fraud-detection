## Obiettivo del Progetto

L'obiettivo di questo progetto è trovare le transazioni bancarie sospette o imbrogli (frodi) usando il Machine Learning. Nel dataset ci sono pochissime frodi rispetto alle transazioni normali (i dati sono molto sbilanciati).

Nel progetto faccio queste cose:

1. **Guardo i dati (EDA):** Capisco come sono fatti i dati e studio il problema dello sbilanciamento.
2. **Uso diversi algoritmi:** Provo e confronto due metodi diversi:
   * **Metodi non supervisionati (senza etichette):** Cerco le anomalie con la statistica (Z-score) e con algoritmi come *Isolation Forest*.
   * **Metodi supervisionati (con etichette):** Alleno modelli di classificazione adatti a questo tipo di problema.
3. **Controllo i risultati:** Per capire se i modelli funzionano bene, non guardo l'accuratezza generale. Guardo metriche specifiche come **Precision**, **Recall** e **F1-score**, perché è importante non perdere nessuna frode.

Tutto il lavoro è spiegato passo dopo passo nel Jupyter Notebook in questo repository.