# Compilazione allegati – Centri UniPA

Applicazione web client-side per la compilazione degli Allegati relativi ai Centri
(Interuniversitari, Interdipartimentali, di Servizi e di Ateneo) dell’Università degli Studi di Palermo.

## Funzionalità principali

- Selezione tipologia di Centro e Allegato
- Generazione automatica dei campi di compilazione
- Controllo campi obbligatori
- Gestione allegati PDF multipli
- Verifica numero minimo di PDF richiesti per ciascun Allegato
- Generazione di un unico PDF finale contenente:
  - riepilogo dati
  - accodamento dei PDF caricati
- Salvataggio e recupero bozza (localStorage del browser)
- Tema grafico chiaro/scuro

## Requisiti tecnici

- Browser moderno (Chrome, Edge, Firefox)
- Nessun server richiesto
- Funziona interamente lato browser

## Pubblicazione su GitHub Pages

1. Caricare il contenuto di questa cartella in un repository GitHub.
2. Aprire Settings → Pages.
3. Selezionare:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /(root)

L'applicazione sarà disponibile all'indirizzo:

https://USERNAME.github.io/NOME-REPOSITORY/

## Note su privacy e dati

- I dati inseriti non vengono inviati a server esterni.
- Le bozze sono salvate esclusivamente nel browser dell’utente tramite localStorage.
- I file PDF restano sul computer dell’utente e sono utilizzati solo per la generazione del PDF finale.

## Licenza

Uso interno – Università degli Studi di Palermo.