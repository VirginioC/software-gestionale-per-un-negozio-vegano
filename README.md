# Software gestionale per un negozio vegano

## Descrizione
Questo progetto, prodotto durante il Master in Data Science di Profession AI, consiste nel realizzare un software gestionale per un negozio vegano utilizzando il linguaggio **Python**. 
L'obiettivo principale è fornire uno strumento che consenta di gestire l'inventario, tracciare gli ordini e ottenere report dettagliati sulle vendite.

Il software è testuale, quindi utilizzabile da riga di comando, e persistente: le informazioni inserite dall'utente vengono mantenute tra diverse esecuzioni del programma.

Il progetto è stato sviluppato su **Google Colab** e utilizza librerie Python per la gestione e la visualizzazione dei dati.

## Funzionalità e Comandi
Il software offre le seguenti funzionalità, che possono essere attivate tramite i comandi corrispondenti:

- Registrare nuovi prodotti in magazzino (nome, quantità, prezzo di vendita e acquisto): `aggiungi`
- Elencare tutti i prodotti presenti in magazzino: `elenca`
- Registrare le vendite effettuate: `vendita`
- Visualizzare i profitti lordi e netti totali: `profitti`
- Mostrare e descrivere in un menu di aiuto i comandi disponibili: `aiuto`
- Chiudere il programma: `chiudi`

Per rendere il software persistente le informazioni inserite in ogni esecuzione vengono salvate in due file TVS:
- Lista dei prodotti presenti in magazzino: `products_list.tsv`
- Lista delle vendite effettuate: `sales_list.tsv`

## Tecnologie utilizzate
- **Linguaggio**: Python
- **Ambiente di sviluppo**: Google Colab (Jupyter Notebook)

## Come eseguire il software
1. Clona o scarica il repository.
2. Apri il file `software_gestionale_negozio_vegano.ipynb` su Google Colab o altri ambienti compatibili con Jupyter Notebook.
3. Segui le istruzioni presenti nel notebook per eseguire il software.

## Autore
[Virginio Cocciaglia](https://github.com/VirginioC)

---
