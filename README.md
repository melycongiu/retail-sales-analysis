# Analisi Vendite Retail
## Descrizione del progetto
Questo progetto nasce dall’idea di capire meglio come si comportano le vendite in un contesto retail, partendo dai dati grezzi fino a ottenere informazioni utili e facili da interpretare.  
L’obiettivo principale è creare una **dashboard interattiva** che permetta di visualizzare rapidamente i trend delle vendite, i comportamenti dei clienti e le performance dei prodotti, così da avere una panoramica chiara e immediata.  

Per arrivare a questo risultato, il progetto si è sviluppato in tre fasi principali:  
- **Pulizia dei dati**: inizialmente i dati contenevano valori mancanti, duplicati e alcune incongruenze. Attraverso Excel e SQL sono stati sistemati e uniformati, in modo da avere un dataset pronto per l’analisi.  
- **Analisi tramite query SQL**: una volta puliti i dati, sono state eseguite aggregazioni e calcoli per capire quali clienti spendono di più, quali mesi registrano picchi di vendite e come si comportano le diverse categorie di prodotto.  
- **Creazione della dashboard**: infine, i risultati sono stati trasformati in grafici e visualizzazioni interattive tramite Tableau, in modo da rendere immediatamente comprensibili le informazioni più importanti.  

## Principali insight
Dall’analisi dei dati sono emersi alcuni punti interessanti e significativi:  
- Le **vendite totali** del periodo analizzato ammontano a **456.000 €**, una cifra che permette di capire subito la dimensione complessiva delle attività di vendita.  
- I **top 10 clienti**, quelli che hanno speso di più, hanno acquistato per circa **2.000 € ciascuno**, contribuendo però solo al **4,4% del totale delle vendite**. Questo ci fa capire che la maggior parte del fatturato proviene da una base più ampia di clienti con spese più contenute.  
- Analizzando i mesi, si notano **picchi di vendita** in **Maggio e Ottobre 2023**, mentre il minimo si registra in **Gennaio 2024**, suggerendo una certa stagionalità nelle vendite.  
- Le **categorie di prodotto** si comportano in modo diverso: non sempre i prodotti più venduti in quantità generano il maggior ricavo. Alcuni prodotti venduti in numero minore ma a prezzo più alto contribuiscono in modo significativo al fatturato complessivo.  

## Contenuto del repository
- `dataset.xlsx` → dataset riordinato e leggibile + dataset in csv importato (fonte: Kaggle)
- `sql queries` → query SQL utilizzate per l’analisi  
- `Dashboard portfolio.png` → immagini della dashboard e dei grafici  
- `README.md` → documentazione del progetto

## Strumenti utilizzati
- **Excel** → visualizzazione dataset, identificazione errori 
- **BigQuery (SQL)** → pulizia, trasformazione e analisi dei dati  
- **Tableau** → creazione della dashboard e visualizzazione dei dati. Link alla dashboard interattiva: (https://public.tableau.com/app/profile/melissa.congiu/viz/Analisi_ordini/Dashboardportfolio)

## Considerazioni finali
Dall’analisi dei dati emergono diversi pattern interessanti:
La maggior parte del fatturato deriva da una base ampia di clienti che spendono poco, mentre pochi clienti contribuiscono con importi più elevati. Questo suggerisce che puntare su strategie di fidelizzazione e di upselling potrebbe fare davvero la differenza.

Si notano dei picchi stagionali: alcuni mesi, come Maggio e Ottobre, registrano vendite particolarmente alte, mentre altri mesi mostrano cali. Conoscere queste variazioni aiuta a pianificare meglio promozioni e gestione delle scorte.

Non sempre le categorie con più unità vendute generano il maggior ricavo; ci sono prodotti meno venduti ma più costosi che contribuiscono in modo significativo al totale.

I clienti abituali rappresentano una parte consistente del fatturato, il che conferma quanto sia importante mantenerli e curare la loro esperienza.

In sintesi, anche un dataset relativamente semplice può fornire spunti concreti su come migliorare vendite, prezzi e strategie aziendali, offrendo indicazioni pratiche da applicare in contesti reali.
---
