# Dipartimento della Difesa — FiveM Roleplay

Portale personale delle riunioni, ricavato dai due fogli del modello Excel fornito. Interfaccia in italiano, blu e oro, con stemma originale come icona e timbro sui verbali.

## Avvio

Apri `index.html` nel browser oppure servi questa cartella con un server statico. Non servono installazioni o compilazioni. Per un archivio stabile usa sempre lo stesso browser e lo stesso indirizzo del sito.

## Funzioni

- Crea e modifica riunioni, dati dell’incontro e ordine del giorno.
- Registra partecipanti, presenza, intervento e note.
- Registra problemi, proposte, decisioni e azioni con referente, scadenza e stato.
- Compila conclusioni e prossimi aggiornamenti.
- Archivia, cerca, ripristina ed elimina verbali con conferma.
- Stampa il verbale completo con timbro oppure scegli «Salva come PDF» nella finestra di stampa.
- Esporta e importa backup JSON. L’importazione richiede conferma e sostituisce i record con lo stesso ID, conservando gli altri.

Al primo avvio viene creata la riunione presente nel modello: UDC-001 del 25/09/2026, ore 21:30. Non sono inventati partecipanti o interventi.

## Dati personali e accesso

Le riunioni sono conservate in `localStorage`, esclusivamente nel browser in uso. Non vengono inviate a un server. Non esistono account, sincronizzazione o autenticazione. Chi accede allo stesso profilo browser può consultarle. La cancellazione dei dati del browser può eliminare l’archivio: esporta backup regolari. I backup contengono i verbali in chiaro, quindi conservali privatamente e non caricarli nel repository.

Un repository privato non va confuso con un sito accessibile solo a te. Questa versione non implementa un blocco degli accessi al sito: per l’uso strettamente privato aprila localmente, oppure scegli un hosting con autenticazione. La riunione iniziale presente nell’Excel è inclusa nel codice; rimuovila prima di un’eventuale pubblicazione se non vuoi renderne visibili i contenuti. I verbali successivi non fanno parte del codice pubblicato.

## GitHub

Il progetto è composto da file statici ed è compatibile con un repository GitHub. Carica `index.html`, `style.css`, `app.js`, `.nojekyll` e la cartella `assets`. Non occorrono dipendenze o servizi esterni. L’eventuale pubblicazione e la scelta del controllo accessi vanno configurate sul repository di destinazione. Nessun repository o sito pubblico viene creato automaticamente da questi file.

## Corrispondenza con Excel

Il foglio «Riunione» corrisponde alle sezioni Dati dell’incontro, Ordine del giorno, Presenze e Conclusioni. Il foglio «Interventi e azioni» corrisponde al registro degli interventi nella scheda. Partecipanti e interventi si aggiungono liberamente, senza i limiti delle righe del foglio. Il sito non modifica il file Excel e non importa file XLSX: il ripristino riguarda i propri backup JSON.

Materiale destinato esclusivamente all’ambientazione FiveM RP, senza affiliazione con enti reali.
