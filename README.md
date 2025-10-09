# Albo d'Oro Fantacalcio

Questo progetto mostra l'albo d'oro del Fantacalcio, con la storia dei vincitori dei principali trofei stagione per stagione. I dati sono visualizzati in una tabella e tramite grafici interattivi.

## Come funziona

- **index.html**: Pagina principale che mostra la tabella e i grafici dei trofei vinti per squadra e utente.
- **albo.json**: File contenente tutti i dati storici delle stagioni e dei vincitori.
- **Bootstrap 5**: Utilizzato per lo stile.
- **ApexCharts**: Utilizzato per i grafici.

## Installazione e utilizzo

1. Clona la repository o scarica i file `index.html` e `albo.json` nella stessa cartella.
2. Apri `index.html` con il tuo browser.
3. I dati saranno caricati automaticamente dal file JSON.

## Aggiornare i dati

Per aggiungere una nuova stagione o modificare i vincitori:
- Modifica il file `albo.json` seguendo la struttura esistente.
- Salva e ricarica la pagina.

## Dipendenze

- [Bootstrap 5](https://getbootstrap.com/)
- [ApexCharts](https://apexcharts.com/)

Entrambe le librerie sono caricate tramite CDN, non è necessario installare nulla.

## Note

- I dati utente sono attualmente non valorizzati nel JSON. Se vuoi mostrare i trofei vinti per utente, aggiorna i campi `utenti` in `albo.json`.
- Per pubblicare online, puoi usare GitHub Pages o qualsiasi servizio statico.
