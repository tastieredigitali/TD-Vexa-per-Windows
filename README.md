# TD Vexa

**Il gestionale per il negozio: vendite, cassa, preventivi, ordini, assistenza e magazzino in un solo programma, con il sito WooCommerce collegato.** Un PC tiene i dati, gli altri si collegano a lui. In negozio si usa il programma per Windows; da fuori si lavora dal browser, senza installare niente.

[**Scarica l'ultima versione**](../../releases/latest) · [Pagina del programma](https://tastieredigitali.tech/software/gestionale-negozio/) · Windows 10 e 11 a 64 bit · 7 giorni di prova

![La pagina delle vendite](screenshots/vendite.png?v=v0.44.87)

Il cliente si sceglie da una finestra di ricerca: per ragione sociale, partita IVA, codice, indirizzo o città, così due clienti con lo stesso nome non si confondono.

![La ricerca dei clienti](screenshots/ricerca-clienti.png?v=v0.44.87)

## A cosa serve

TD Vexa è fatto per un negozio che vende al banco, fa assistenza e tiene un magazzino: informatica, elettronica, ricambi. Fa le cose di tutti i giorni senza giri:

- **al banco**: scontrino, fattura, DDT e nota di credito dalla stessa pagina, con il lettore di codici a barre;
- **in cassa**: quanto c'è nel cassetto, versamenti, chiusura della giornata e riepilogo del giorno da stampare;
- **per i clienti**: preventivi con il tuo logo, ordini con caparra, merce messa da parte, avviso quando arriva;
- **in laboratorio**: accettazione con ricevuta, ricambi e manodopera, riconsegna con lo scontrino già compilato;
- **in magazzino**: arrivi, inventario, trasferimenti, scorte minime, ordini ai fornitori e assemblaggio dei PC;
- **sul sito**: prezzi e giacenze mandati a WooCommerce, ordini del sito che entrano nel programma;
- **da fuori**: le stesse pagine dal browser, da casa o da un altro negozio.

In cima al menu ci sono quattro tasti grandi, **Vendite, Preventivi, Assistenza e Cassa**: sono le cose che si fanno cento volte al giorno. Il resto è diviso in sezioni, ognuna con la sua icona e il suo colore.

## Vendite

Cerchi l'articolo scrivendo o lo leggi con il lettore, e la riga è fatta. Il cliente si cerca per nome, telefono o codice, e se non c'è lo crei da lì senza cambiare pagina.

- Sconto su ogni riga **in percentuale e in euro**, **sconto sul totale**, sconto fisso del cliente e tetto massimo di sconto.
- Prezzi scritti **con o senza IVA**, a scelta del negozio.
- **Avviso quando la giacenza non basta**, con gli articoli equivalenti che ci sono; se vuoi, senza giacenza non si vende.
- Fino a tre mezzi di pagamento sullo stesso documento, con il resto calcolato; pagamenti **fino a quattro rate**.
- Vendita **sospesa** e ripresa dopo; vendita **da ordine cliente**, con la caparra scalata da sola.
- **Scontrino e fattura in un gesto**, oppure la fattura dopo, quando il cliente la chiede.
- **Reso dentro lo scontrino** e **cambio merce**: il cliente paga solo la differenza, e se rende di più riceve un **buono** da spendere.
- **Fido** del cliente: una vendita a credito oltre il limite si ferma, e la sblocca solo un amministratore.
- **Numeri di serie** uno per pezzo, mai lo stesso due volte; ricerca della vendita dal numero di serie.
- Fattura elettronica in **XML**, una alla volta o tutte quelle di un periodo.
- Tasti rapidi: F3 scontrino, F4 fattura, F10 nota di credito, F12 DDT.
- Tasto destro su una riga per aprire la scheda dell'articolo o del cliente senza perdere quello che stavi facendo.

## Cassa

La pagina della cassa mette i numeri in grande: quanto c'è nel cassetto, incassi e uscite del giorno, giornata aperta o chiusa. Sotto, le operazioni che contano, ognuna con scritto cosa fa e con la sua conferma.

![La pagina della cassa](screenshots/cassa.png?v=v0.44.87)

- **Chiusura della giornata**, con la chiusura fiscale sul registratore di cassa collegato.
- **Versamento in banca**, uscite ed entrate di cassa.
- **Prima nota** con le scadenze da incassare e da pagare, e **ricevute bancarie** con il file per la banca.
- **Mezzi di pagamento** che decidi tu, con quelli che restano nel cassetto a fine giornata.
- Registratore di cassa in rete, USB o seriale, con ricerca automatica: Micrelec collegate direttamente (in rete o seriale, chiusura fiscale compresa), Epson e RCH dal loro servizio web, Ditron in rete, un elenco di modelli che imposta tutto da solo; le altre marche con i comandi XON/XOFF oppure attraverso il programma ponte che già pilota la cassa (Custom, Ditron, Olivetti, Fasy, Sarema, Sweda e altre).
- Copia non fiscale sulla stampante a rotolo.

## Report

Scegli un giorno o un periodo, oppure premi Oggi, Ieri, Questa settimana, Questo mese. Vedi subito venduto, incassato, uscite e margine, con l'andamento a barre e le tabelle per mezzo di pagamento, tipo di documento, operatore e IVA.

![Il report del periodo](screenshots/report.png?v=v0.44.87)

Ogni report si stampa o si salva in PDF, anche **documento per documento**: ora, cliente, operatore, righe e pagamento di ogni scontrino e fattura. Ci sono poi le statistiche di vendite, incassi, clienti, rotazione del magazzino e assistenza.

## Preventivi e ordini

Il preventivo si scrive come una vendita e si stampa con il tuo logo, il testo di apertura e di chiusura che vuoi tu, e solo le colonne che decidi di mostrare. Si manda per email con il PDF allegato, si clona, e con un tasto diventa un ordine.

![Un preventivo stampato](screenshots/stampa-preventivo.png?v=v0.44.87)

- Ordini dei clienti con **caparra** (e ricevuta da far firmare), consegna prevista, riferimento del cliente.
- Merce **assegnata** all'ordine, lista di quello che manca, avviso al cliente quando arriva.
- Dall'ordine alla consegna con scontrino, fattura o DDT; i DDT si fatturano insieme a fine mese, con la data che scegli.

![Gli ordini dei clienti](screenshots/ordini.png?v=v0.44.87)

## Assistenza

Il cliente porta un oggetto da riparare: lo accetti in una pagina, anche se il cliente è nuovo, e stampi la **ricevuta** per lui e la **scheda interna** per il laboratorio, con tutti i suoi recapiti.

![L'accettazione di una riparazione](screenshots/assistenza.png?v=v0.44.87)

- **Garanzia** con data d'acquisto e scadenza: se l'oggetto l'hai venduto tu, il numero di serie le scrive da solo.
- Urgente, preventivo richiesto, data in cui deve essere pronto.
- **Ricambi e manodopera** riga per riga: i ricambi escono dal magazzino quando li prelevi, e ci tornano se li rendi.
- **Riconsegna con scontrino o fattura** già compilati, anche per più riparazioni dello stesso cliente insieme.
- Cliente avvisato (quando e come), storia dello stesso oggetto dal numero di serie.
- Invio al fornitore con il DDT, **rientro con il suo documento**, e registro delle riparazioni.
- Guasti e resi a fornitore (RMA) con numero, date e stato.

![La gestione degli interventi](screenshots/interventi.png?v=v0.44.87)

## Magazzino e acquisti

![Le giacenze](screenshots/giacenze.png?v=v0.44.87)

- Più magazzini, carichi e scarichi, giacenze e valorizzazione, **trasferimento** da un magazzino all'altro in un colpo.
- **Arrivo merce** con il documento del fornitore, le spese di trasporto divise sui costi e la conferma con il totale.
- **Modifica arrivi**: ogni arrivo si ristampa o si annulla tutto intero.
- **Inventario**: scrivi quello che hai contato, il programma stampa le differenze e porta le giacenze a quei numeri.
- **Scorte minime** e **ordini ai fornitori**, anche creati da soli: un ordine per fornitore con la merce che manca ai clienti e quella sotto scorta, a multipli del lotto minimo.
- **Fornitori alternativi** con il loro codice e il loro costo, e **articoli equivalenti**.
- **Costi dal listino del fornitore**: carichi il suo file e i costi degli articoli in comune si aggiornano.
- **Assemblaggio**: i componenti escono, il PC entra al loro costo, con i numeri di serie.
- Listini, listini derivati, offerte speciali, **prezzi programmati** a data, cambio di aliquota IVA in blocco.
- Etichette, cartelli prezzo ed etichette di spedizione.

![Il registro degli arrivi](screenshots/arrivi.png?v=v0.44.87)

## Articoli, Icecat e sito

![La scheda di un articolo](screenshots/scheda-articolo.png?v=v0.44.87)

- L'articolo nuovo si compila a mano o si scarica da **Icecat** con il codice EAN: descrizione, immagini e caratteristiche.
- Prezzo senza IVA, con IVA e ricarico sul costo, uno accanto all'altro; un articolo si **clona** con un tasto.
- **WooCommerce**: articoli, prezzi e giacenze vanno sul sito, gli ordini del sito arrivano nel programma.
- Importazione di articoli, clienti, fornitori, giacenze e storico dal gestionale di prima (database SQL Server).

## Documenti e stampe

Ogni stampa si apre in anteprima: da lì **Stampa** va diretta alla stampante e **Salva in PDF** propone già il nome del file. Nel PDF il testo si seleziona e si cerca. Il logo si carica una volta in Configurazione e compare su tutti i documenti.

![Una fattura stampata](screenshots/stampa-fattura.png?v=v0.44.87)

- **DDT** con causale, aspetto dei beni, colli, peso, porto e vettore; se vuoi, senza prezzi.
- Su un documento emesso si correggono note, numeri di serie e dati di trasporto, senza rifarlo.
- Annullando l'ultima fattura, il suo numero lo riprende la successiva: niente buchi.
- Tabelle lunghe con l'intestazione ripetuta su ogni foglio e il numero di pagina.
- Ogni lista si stampa o si **salva per Excel**.

## Dal browser, da fuori

Non serve installare niente e non serve una VPN: apri l'indirizzo del negozio dal browser, entri con utente, password e (se l'hai attivata) la verifica in due passaggi, e trovi lo stesso menu del programma.

![Le vendite dal browser](screenshots/web-vendita.png?v=v0.44.87)

- Vendite, preventivi, ordini, documenti, cassa, assistenza, magazzino, anagrafiche e configurazione: le stesse funzioni.
- **Le stampe escono sulla stampante del PC da cui sei collegato**, oppure le salvi in PDF dal browser.
- **Lo scontrino esce sulla cassa del negozio** anche se la vendita la fai dal browser o da un'altra postazione: lo batte il PC a cui la cassa è collegata.

![La cassa dal browser](screenshots/web-cassa.png?v=v0.44.87)

![Ricambi e manodopera di una riparazione, dal browser](screenshots/web-ricambi.png?v=v0.44.87)

![I documenti emessi, dal browser](screenshots/web-documenti.png?v=v0.44.87)

## Come lo vuoi tu

In **Configurazione, Opzioni** scegli come lavora il programma: prezzi con IVA, blocco senza giacenza, sconto massimo, mezzi di pagamento proposti, giorni di validità del preventivo, DDT senza prezzi, riconsegna solo con documento, e altro.

![Le opzioni](screenshots/opzioni.png?v=v0.44.87)

- **Utenti e permessi**: ogni utente vede solo le voci di menu che gli lasci, e il server le chiude davvero.
- **Registro delle attività**: chi ha annullato, eliminato o cambiato cosa, e quando.
- **Numeratori** per continuare la numerazione del programma di prima.

## Chiaro e scuro

![Il tema scuro](screenshots/tema-scuro.png?v=v0.44.87)

## Scaricare e installare

Nella pagina [Releases](../../releases/latest) ci sono due installer:

- **TD-Vexa-Server**: per il PC che tiene i dati e resta acceso. Installa database, server e il programma per usarlo anche lì.
- **TD-Vexa-Postazione**: per gli altri PC. Al primo avvio cerca da solo il server in rete.

Gli installer sono **firmati digitalmente** da Tastiere Digitali: prima di installare, Windows mostra il nostro nome come editore verificato.

### Primo avvio

1. Installa **TD-Vexa-Server** sul PC server.
2. Apri TD Vexa: chiede il **codice del primo avvio**, che trovi nel menu Start, TD Vexa, *Codice del primo avvio*.
3. Crea l'amministratore, poi inserisci la licenza o attiva la **prova di 7 giorni**.
4. Sugli altri PC installa **TD-Vexa-Postazione** e conferma l'impronta del certificato, uguale a quella della pagina *Postazioni* del server.

Gli aggiornamenti li propone il programma: **Aggiorna ora** scarica la versione nuova, la controlla e la installa.

### Per lavorare da fuori

Serve un indirizzo pubblico che porti al PC server, per esempio `gestionale.tuodominio.it`, con un certificato valido: di solito lo fa un proxy (Nginx Proxy Manager o simili) che inoltra in **https** alla porta del server. Poi si apre quell'indirizzo dal browser.

## Dove stanno i dati

- **Sul tuo server, in negozio.** Il database è sul PC che scegli tu: niente cloud.
- **Copie di sicurezza** automatiche ogni giorno, nella cartella che indichi (anche un disco di rete).
- **Da fuori** si entra dal browser, con la verifica in due passaggi.

Le schermate del programma le fa il programma da solo a ogni build (quelle di ogni pagina sono nella cartella [schermate](schermate)); quelle dell'uso dal browser le fa la prova automatica che apre ogni pagina in un browser vero.

Un prodotto di [Tastiere Digitali](https://tastieredigitali.it/) — [TD Vexa su tastieredigitali.tech](https://tastieredigitali.tech/software/gestionale-negozio/)
