# TD Vexa

**Il gestionale per il negozio: vendite, cassa, preventivi, ordini, assistenza e magazzino in un solo programma, con il sito WooCommerce collegato.** Un PC tiene i dati, gli altri si collegano a lui. In negozio si usa il programma per Windows; da fuori si lavora dal browser, senza installare niente.

[**Scarica l'ultima versione**](../../releases/latest) · [Pagina del programma](https://tastieredigitali.tech/software/gestionale-negozio/) · Windows 10 e 11 a 64 bit · 7 giorni di prova

![La pagina delle vendite](screenshots/vendite.png?v=v0.45.12)

Il cliente si sceglie da una finestra di ricerca: per ragione sociale, partita IVA, codice, indirizzo o città, così due clienti con lo stesso nome non si confondono.

![La ricerca dei clienti](screenshots/ricerca-clienti.png?v=v0.45.12)

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

![La pagina della cassa](screenshots/cassa.png?v=v0.45.12)

- **Chiusura della giornata**, con la chiusura fiscale sul registratore di cassa collegato.
- **Versamento in banca**, uscite ed entrate di cassa.
- **Prima nota** con le scadenze da incassare e da pagare (doppio clic su un movimento nato da uno scontrino o da una fattura: si apre il documento con le sue righe), e **ricevute bancarie** con il file per la banca.
- **Mezzi di pagamento** che decidi tu, con quelli che restano nel cassetto a fine giornata.
- Registratore di cassa in rete, USB o seriale, con ricerca automatica: Micrelec collegate direttamente (in rete o seriale, chiusura fiscale compresa), Epson e RCH dal loro servizio web, Ditron in rete, un elenco di modelli che imposta tutto da solo; le altre marche con i comandi XON/XOFF oppure attraverso il programma ponte che già pilota la cassa (Custom, Ditron, Olivetti, Fasy, Sarema, Sweda e altre).
- Copia non fiscale sulla stampante a rotolo.

## Report

Scegli un giorno o un periodo, oppure premi Oggi, Ieri, Questa settimana, Questo mese. Vedi subito venduto, incassato, uscite e margine, con l'andamento a barre e le tabelle per mezzo di pagamento, tipo di documento, operatore e IVA.

![Il report del periodo](screenshots/report.png?v=v0.45.12)

Ogni report si stampa o si salva in PDF, anche **documento per documento**: ora, cliente, operatore, righe e pagamento di ogni scontrino e fattura. Ci sono poi le statistiche di vendite, incassi, clienti, rotazione del magazzino e assistenza.

## Preventivi e ordini

Il preventivo si scrive come una vendita e si stampa con il tuo logo, il testo di apertura e di chiusura che vuoi tu, e solo le colonne che decidi di mostrare. Si manda per email con il PDF allegato, si clona, e con un tasto diventa un ordine.

![Un preventivo stampato](screenshots/stampa-preventivo.png?v=v0.45.12)

- Ordini dei clienti con **caparra** (e ricevuta da far firmare), consegna prevista, riferimento del cliente.
- Merce **assegnata** all'ordine, lista di quello che manca, avviso al cliente quando arriva.
- Dall'ordine alla consegna con scontrino, fattura o DDT; i DDT si fatturano insieme a fine mese, con la data che scegli.

![Gli ordini dei clienti](screenshots/ordini.png?v=v0.45.12)

## Assistenza

Il cliente porta un oggetto da riparare: lo accetti in una pagina, anche se il cliente è nuovo, e stampi la **ricevuta** per lui e la **scheda interna** per il laboratorio, con tutti i suoi recapiti.

![L'accettazione di una riparazione](screenshots/assistenza.png?v=v0.45.12)

- **Garanzia** con data d'acquisto e scadenza: se l'oggetto l'hai venduto tu, il numero di serie le scrive da solo.
- Urgente, preventivo richiesto, data in cui deve essere pronto.
- **Ricambi e manodopera** riga per riga: i ricambi escono dal magazzino quando li prelevi, e ci tornano se li rendi.
- **Riconsegna con scontrino o fattura** già compilati, anche per più riparazioni dello stesso cliente insieme.
- Cliente avvisato (quando e come), storia dello stesso oggetto dal numero di serie.
- Invio al fornitore con il DDT, **rientro con il suo documento**, e registro delle riparazioni.
- Guasti e resi a fornitore (RMA) con numero, date e stato.

![La gestione degli interventi](screenshots/interventi.png?v=v0.45.12)

## Magazzino e acquisti

![Le giacenze](screenshots/giacenze.png?v=v0.45.12)

- Più magazzini, carichi e scarichi, giacenze e valorizzazione, **trasferimento** da un magazzino all'altro in un colpo.
- **Arrivo merce** con il documento del fornitore, le spese di trasporto divise sui costi e la conferma con il totale.
- **Modifica arrivi**: ogni arrivo si ristampa o si annulla tutto intero.
- **Inventario**: scrivi quello che hai contato, il programma stampa le differenze e porta le giacenze a quei numeri.
- **Scorte minime** e **ordini ai fornitori**, anche creati da soli: un ordine per fornitore con la merce che manca ai clienti e quella sotto scorta, a multipli del lotto minimo.
- **Fornitori alternativi** con il loro codice e il loro costo, e **articoli equivalenti**.
- **Costi dal listino del fornitore**: carichi il suo file e i costi degli articoli in comune si aggiornano.
- **Assemblaggio**: i componenti escono, il PC entra al loro costo, con i numeri di serie.
- Listini, listini derivati, offerte speciali, **prezzi programmati** a data, cambio di aliquota IVA in blocco.
- **Gestione listini** (Configurazione e utilità): la tabella «Relazione fra listini» dice come nasce ogni listino: origine (costo medio, un altro listino, o manuale), ricarico o sconto generico in %, listino limite, ordine di ricalcolo e arrotondamenti; si cambia lì e si salva con «Salva impostazioni». Sotto, il ricalcolo: per listino, classe e sottoclasse, subito o da una data, con le opzioni (anche dove l'origine vale zero, anche gli articoli con distinta base, dal costo medio anche con giacenza zero) e la generazione del listino in data per i soli articoli arrivati da fornitore da un certo giorno.
- Cambiando listino in un preventivo o in una vendita le righe prendono i prezzi del listino nuovo; il programma dice quante righe sono cambiate (un articolo con lo stesso prezzo nei due listini resta com'è).
- Etichette, cartelli prezzo ed etichette di spedizione.

![Il registro degli arrivi](screenshots/arrivi.png?v=v0.45.12)

## Articoli, Icecat e sito

![La scheda di un articolo](screenshots/scheda-articolo.png?v=v0.45.12)

- L'articolo nuovo si compila a mano o si scarica da **Icecat** con il codice EAN: descrizione, immagini e caratteristiche.
- Prezzo senza IVA, con IVA e ricarico sul costo, uno accanto all'altro; un articolo si **clona** con un tasto.
- **WooCommerce**: articoli, prezzi e giacenze vanno sul sito, gli ordini del sito arrivano nel programma. Come si usa è scritto qui sotto, in «Il sito web».
- Importazione di articoli, clienti, fornitori, giacenze e storico dal gestionale di prima (database SQL Server).

## Il sito web

Tutto quello che riguarda il sito WooCommerce sta in una sezione sola del menu, **Sito web**. La voce di ogni giorno è **Sincronizzazione sito**. Sotto ci sono le voci che si toccano una volta, e che restano dell'amministratore: «Sito WooCommerce» (indirizzo del sito e chiavi), «Categorie del sito» (quale categoria del sito corrisponde a ogni classe) e «Icecat».

![Da sincronizzare](screenshots/web-sito-da-sincronizzare.png?v=v0.45.12)

**1. Il primo sync, dal sito al programma.** La prima volta la pagina mostra un tasto solo: **Primo sync dal sito**. Legge i prodotti, le categorie e le foto che il sito ha già, collega ogni prodotto al suo articolo (per codice, poi per EAN) e abbina le classi del programma alle categorie del sito: una classe prende la categoria dove il sito tiene i suoi articoli e, se non ne ha, quella con lo stesso nome. Sul sito non scrive niente. Finché non è stato fatto, verso il sito non parte niente: né a mano né in automatico. **Da lì in poi comanda il programma**: prezzi, giacenze, categorie e prodotti nuovi vanno dal programma al sito. La lettura va in sottofondo, con la barra e la percentuale dei prodotti letti: su un sito con migliaia di prodotti dura qualche minuto, e intanto si può cambiare pagina.

Dopo, lo stesso tasto diventa «Rifai il primo sync dal sito» (abbina le classi rimaste senza categoria; gli abbinamenti già fatti non li tocca) e compare **Leggi il sito**, che rilegge i prodotti quando si vuole, sempre senza scrivere.

**2. Gli elenchi.**

- **Da sincronizzare**: è quello su cui si apre la pagina, e dice a colpo d'occhio cosa c'è da portare sul sito. Dentro ci sono gli articoli con la spunta «visibile sul web» che il sito non ha ancora (anche un PC o un altro prodotto composto appena creato: un articolo nuovo nasce con la spunta già messa, e chi non deve andare sul sito la toglie dalla scheda) e quelli già collegati con il prezzo o la giacenza cambiati. Accanto a ogni riga c'è scritto cosa c'è da fare. **Sincronizza** li manda tutti: i nuovi nascono sul sito (già in vendita, o come bozze se scelto in Sito WooCommerce), agli altri partono prezzi e giacenze. Con delle righe scelte partono solo quelle. Fatto, l'elenco si svuota. Il numero fra parentesi sul tasto dell'elenco dice quante righe ci sono.
- **Già sul sito**: gli articoli collegati a un prodotto, con il nostro prezzo e la nostra disponibilità accanto a quelli del sito. Le righe diverse sono evidenziate. La colonna «foto nostre / sito» dice quante foto ha l'articolo e quante il prodotto.
- **Non ancora sul sito**: gli articoli che il sito non ha. «Manda sul sito gli scelti» li crea, con nome, descrizione, foto, prezzo e giacenza. Nascono già in vendita, o come bozze se scelto in Sito WooCommerce.
- **Solo sul sito**: i prodotti che il sito ha e il programma no. Con un tasto diventano articoli.

![Le categorie del sito](screenshots/web-sito.png?v=v0.45.12)

**3. Le categorie.** Negli altri tre elenchi, a sinistra c'è l'albero della classificazione, la stessa del programma: **famiglia, classe, sottoclasse**. Accanto a ogni ramo c'è quanti prodotti dell'elenco contiene (un ramo conta anche quelli che gli stanno sotto). Un clic su un ramo e l'elenco mostra solo i suoi prodotti. «Nascondi le categorie vuote» toglie dall'albero i rami senza prodotti. Solo sotto «Solo sul sito», dove gli articoli nel programma non ci sono, l'albero è quello delle categorie del sito.

**Le categorie vanno sul sito come sono nel programma.** La classificazione del programma fa da modello. Quando un prodotto parte con le categorie, il suo ramo (famiglia, classe, sottoclasse) viene abbinato alla categoria del sito che ha lo stesso nome sotto la stessa madre; se sul sito non c'è, viene creata, con tutto il ramo che ha sopra. Così una classe nuova con dentro dei prodotti arriva sul sito già al suo posto nell'albero. **Ogni prodotto sta in una categoria sola, quella esatta a cui è associato**: se è in una sottoclasse va lì e basta, non anche nella classe o nella famiglia sopra. Un ramo già abbinato non si tocca, e sul sito non si rinomina e non si cancella niente. Gli abbinamenti si vedono e si correggono in «Categorie del sito»; la creazione si spegne in «Sito WooCommerce», voce «Porta sul sito le categorie come sono nel programma».

**4. Sincronizza gli scelti.** Cosa mandare si sceglie nella riga sopra l'elenco. Si spuntano le righe e si sceglie cosa mandare: **prezzi**, **giacenze**, **categorie**, **foto**. Nome e descrizione di un prodotto che è già sul sito non vengono mai toccati.

**5. Le foto, senza copie.** Un sito si riempie di foto doppie quando un programma le ricarica a ogni invio. Qui non succede:

- le foto partono **solo se lo scegli tu**, mai nel giro automatico;
- prima di mandare, il programma chiede al sito quali foto ha quel prodotto **in quel momento**;
- una foto che il sito ha già non si rimanda: vale per quelle mandate dal programma (se le segna una per una) e per quelle caricate da altri con lo stesso nome di file;
- se tutte le foto ci sono già, al prodotto non viene scritto niente.

Le scelte sono tre:

| Scelta | Cosa fa |
|---|---|
| **Foto: non toccare** | Niente. È la scelta di partenza. |
| **Foto: aggiungi solo quelle che mancano** | Aggiunge al prodotto le foto dell'articolo che il sito non ha. Non toglie niente. |
| **Foto: allinea** | Come sopra, e in più toglie dal prodotto le foto mandate dal programma che nell'articolo non ci sono più. Le foto messe a mano sul sito restano sempre. |

Con la spunta **«Prima chiedi a Icecat le foto di oggi»** il programma, per ogni articolo scelto che ha l'EAN, guarda se su Icecat le foto sono cambiate: se sì aggiorna l'articolo e manda al sito solo quelle nuove. Alla fine un messaggio dice quante foto sono state aggiunte, quante tolte e quanti prodotti erano già a posto.

Da sapere: una foto tolta da un prodotto resta nella libreria dei media del sito, da dove si cancella a mano. Ogni articolo manda al massimo otto foto.

**6. Togliere e cancellare.** «Togli dalla vendita» mette il prodotto in bozza: non si vede più, ma resta. «Cancella dal sito» lo manda nel cestino di WooCommerce, da dove si recupera per 30 giorni; nel programma l'articolo resta. **Dalla scheda articolo**: togliendo la spunta «Articolo visibile sul sito», o mettendo l'articolo obsoleto, il suo prodotto compare in «Da sincronizzare» con scritto «da togliere dal sito» (e conta nel numerino del menu); alla sincronizzazione va nel cestino di WooCommerce. Il giro automatico di ogni minuto non toglie niente: succede solo quando si preme «Sincronizza».

**7. Automatico.** Con la spunta «Automatico», ogni minuto partono verso il sito prezzi e giacenze **solo degli articoli cambiati**. Gli ordini del sito arrivano nel programma solo se in Sito WooCommerce è accesa la spunta «Ricevi gli ordini dal sito»: spenta, il giro automatico manda prezzi e giacenze e gli ordini non li tocca. Senza la spunta, il sito si aggiorna solo quando lo chiedi tu.

**8. In sottofondo, con la barra.** «Sincronizza» e le foto non tengono ferma la pagina: il lavoro lo fa il server. Compare una barra con la percentuale e il tasto «Ferma»; si può cambiare pagina, aprire un'altra sezione o chiudere il programma, e il lavoro va avanti lo stesso. Tornando sulla pagina (anche da un'altra postazione) si ritrova la barra, o l'esito dell'ultimo lavoro. Va in due tempi. Prima i dati: prezzi, giacenze, categorie e prodotti nuovi partono a pacchi, pochi secondi anche per tanti articoli; i nuovi nascono senza foto. Poi le foto, tre prodotti insieme: è il sito a scaricarle una per una, ed è la parte che dura. Il giro automatico resta a piccoli passi (al massimo 300 aggiornamenti e 20 prodotti nuovi per giro) e aspetta mentre c'è un lavoro in corso.

**Quello che cambi sul sito resta.** Una sincronizzazione manda prezzi, giacenze e categorie, e basta: la descrizione o una foto sistemate a mano sul sito non vengono riscritte. Per riportare sul sito quello che c'è nel programma, in «Già sul sito» si scelgono le righe e si preme **«Aggiorna forzatamente sul sito»**: riscrive nome, descrizioni, caratteristiche e foto con quelli dell'articolo, e chiede conferma. Il giro automatico non tocca mai né descrizioni né foto. Vale per tutti i prodotti.

**Se manca la scheda Icecat.** La scheda si cerca con ogni codice a barre dell'articolo e poi con marca e codice del produttore. Se Icecat non la dà, il prodotto nasce lo stesso, con il solo titolo e il testo dell'articolo, e finisce nell'elenco **«Senza scheda Icecat»** della pagina: codice, marca, EAN e il motivo (indirizzo IP non ammesso nel profilo Icecat, marca fuori da Open Icecat, articolo che Icecat non ha). Con il solo account gratuito Icecat dà le marche di Open Icecat; per le altre non dà niente, né foto né caratteristiche. Questi articoli si sistemano dalla loro scheda, caricando le foto, oppure da lì con «Riprova con Icecat e aggiorna sul sito».

**Il giro automatico, voce per voce.** Accanto ad «Automatico ogni minuto» ci sono tre spunte divise: manda i prezzi, manda le giacenze, ricevi gli ordini dal sito. Si accende solo quello che serve, per esempio le giacenze sì e gli ordini no.

**Descrizioni e foto nella scheda articolo.** Nella scheda di ogni articolo, sotto il titolo (il campo «Descrizione»), ci sono i due editor delle descrizioni per il sito e subito sotto le foto:

![Descrizioni e foto di un articolo](screenshots/web-articolo-foto.png?v=v0.45.12)

- **Descrizione breve** (sul sito sta accanto alla foto) e **descrizione estesa** (sotto, nella scheda), ognuna nel suo editor: grassetto, corsivo, titoli, elenchi, collegamenti, emoji con Windows + punto. Un testo copiato da una pagina del sito o da Word si incolla con la sua formattazione: restano titoli, grassetti ed elenchi, se ne vanno stili e classi, e le emoji che WordPress mostra come immagini tornano caratteri (se no uscirebbero giganti). Nel programma installato l'editor si apre con il tasto o con un doppio clic sul riquadro. Un testo scritto senza formattazione va sul sito con i suoi a capo.
- **Foto**: «Aggiungi foto» carica le immagini dal PC; la prima è la **principale**, le altre la **galleria**. Con la stella una foto diventa la principale, con le frecce si ordina, con la croce si toglie. Si salvano con «Salva». Chi ha le sue foto non le prende da Icecat, e chi ha la sua descrizione estesa tiene quella: Icecat riempie solo quello che manca (la tabella delle caratteristiche la aggiunge comunque). «Aggiungi immagini» ne mette altre in coda; «Sostituisci immagini» toglie quelle che ci sono e mette le nuove.

**Un PC, un sito.** Una volta sincronizzate, le foto caricate si tolgono dal programma e restano sul sito: la scheda lo dice («Immagini sincronizzate sul sito ed eliminate in locale») e continua a mostrarle leggendole dal sito. Chi le vuole tenere anche nel programma spegne la scelta in Sito WooCommerce.

Sul sito le foto arrivano ridotte a 1200 px e in WebP. Lo fa un piccolo plugin che si scarica da **Sito web, Sito WooCommerce, «Scarica il mu-plugin delle foto»** e si copia sul sito nella cartella `wp-content/mu-plugins`. Usa le stesse chiavi API, non servono altre credenziali. Con il plugin sul sito anche le foto di Icecat passano di lì, ridotte e in WebP; senza, quelle di Icecat vanno com'erano e quelle caricate nel programma non partono (la pagina lo dice). Con «Foto: allinea» il sito segue l'ordine dell'articolo: cambiata la principale nel programma, cambia sul sito.

**Rifare il primo sync** non sta più nella pagina di ogni giorno: è in Sito WooCommerce, con una conferma. Non scrive sul sito e non tocca giacenze e prezzi del programma.

**Articoli da non mettere sul sito.** In «Da sincronizzare», «Non ancora sul sito» e «Già sul sito» si scelgono le righe e si preme **«Ignora (non mandare sul sito)»**: l'articolo esce dagli elenchi e dal giro automatico e va nell'elenco **«Ignorati»**, da dove si rimette con un tasto. Chi sul sito c'è già ci resta com'è. La stessa spunta sta nella scheda dell'articolo.

**Un ordine da far pagare sul sito.** Negli ordini dei clienti, «Link di pagamento sul sito» crea sul sito un prodotto con il nome dell'ordine e quello che resta da pagare: non esce nel negozio né nelle categorie, lo apre chi ha il collegamento e chi cerca sul sito il numero dell'ordine, per esempio «ordine 00768». Si apre una finestrella con le due cose da dare al cliente, il collegamento e il numero da cercare, ognuna con il suo tasto «Copia». Si compra una volta sola. Quando il cliente ha pagato, al giro dopo l'ordine prende la nota «Pagato sul sito» con data e ora, l'esito della sincronizzazione lo dice e il prodotto sparisce dal sito. «Togli il pagamento dal sito» lo ritira prima. L'incasso sull'ordine lo registrate voi come sempre.

**I numerini nel menu.** Accanto a «Sincronizzazione sito» (e sulla sua sezione, anche chiusa) un pallino rosso dice quanti articoli sono cambiati o nuovi e il sito non li ha ancora ricevuti. Si aggiorna ogni minuto.

**Le scelte restano.** Prezzi, giacenze, categorie, foto, Icecat e «nascondi le categorie vuote» restano come li lasci: valgono in «Da sincronizzare» e in «Già sul sito», per tutte le postazioni, e prezzi, giacenze e categorie anche per il giro automatico.

**Cosa finisce nel prodotto nuovo.** Per gli articoli con l'EAN il programma chiede la scheda a Icecat da solo (spunta «Prendi sempre le foto da Icecat» in Sito WooCommerce): foto, testo e tutte le caratteristiche; chi non ha l'EAN, come i PC composti, va sul sito senza passare da Icecat. Sul sito il testo va nella descrizione breve, accanto alla foto; sotto, nella descrizione, la tabella «Descrizione e Caratteristiche» con tutte le voci. I prodotti nascono **già in vendita**; se preferite controllarli prima, in Sito WooCommerce si spegne «I prodotti nuovi nascono sul sito già in vendita» e nascono come bozze. Nella tabella i valori sono senza unità di misura, come nelle schede già sul sito. Se Icecat risponde che la scheda non è per il vostro account, controllate nel profilo Icecat gli «Indirizzi IP ammessi»; le marche fuori da Open Icecat vogliono Full Icecat con i due token.

**Il prezzo dei rivenditori** parte insieme ai prezzi, nel campo personalizzato scritto in Sito WooCommerce (se il prodotto non ce l'ha, WooCommerce lo crea), e si vede negli elenchi: «riv. nostro» e «riv. sito».

**Il magazzino.** Le giacenze del sito sono quelle del magazzino scelto in Sito WooCommerce. Finché non è scelto, la disponibilità negli elenchi è zero per tutti e le giacenze non partono: la pagina lo dice in alto.

**Categorie di un altro sito.** Se le classi portano abbinamenti a categorie che questo sito non ha (per esempio provando su un sito di prova), leggendo il sito quegli abbinamenti si tolgono e le categorie nascono per nome al primo invio.

**9. Chi può farlo.** La sincronizzazione si dà a chi serve, dai ruoli (Configurazione e utilità, Utenti): la voce «Sincronizzazione sito» fa vedere la pagina; il permesso «manda prodotti, prezzi, giacenze e foto» fa sincronizzare; il permesso «toglie dalla vendita e cancella prodotti» è a parte. Chi ha solo la voce guarda e basta. Nei ruoli le voci sono divise per sezione: la spunta sulla sezione dà o toglie tutte le sue voci in un colpo, poi si ritocca voce per voce.

## Documenti e stampe

Ogni stampa si apre in anteprima: da lì **Stampa** va diretta alla stampante e **Salva in PDF** propone già il nome del file. Nel PDF il testo si seleziona e si cerca. Il logo si carica una volta in Configurazione e compare su tutti i documenti.

![Una fattura stampata](screenshots/stampa-fattura.png?v=v0.45.12)

- **DDT** con causale, aspetto dei beni, colli, peso, porto e vettore; se vuoi, senza prezzi.
- Su un documento emesso si correggono note, numeri di serie e dati di trasporto, senza rifarlo.
- Annullando l'ultima fattura, il suo numero lo riprende la successiva: niente buchi.
- Tabelle lunghe con l'intestazione ripetuta su ogni foglio e il numero di pagina.
- Ogni lista si stampa o si **salva per Excel**.

## Dal browser, da fuori

Non serve installare niente e non serve una VPN: apri l'indirizzo del negozio dal browser, entri con utente, password e (se l'hai attivata) la verifica in due passaggi, e trovi lo stesso menu del programma.

![Le vendite dal browser](screenshots/web-vendita.png?v=v0.45.12)

- Vendite, preventivi, ordini, documenti, cassa, assistenza, magazzino, anagrafiche e configurazione: le stesse funzioni.
- **Le stampe escono sulla stampante del PC da cui sei collegato**, oppure le salvi in PDF dal browser.
- **Lo scontrino esce sulla cassa del negozio** anche se la vendita la fai dal browser o da un'altra postazione: lo batte il PC a cui la cassa è collegata.

![La cassa dal browser](screenshots/web-cassa.png?v=v0.45.12)

![Ricambi e manodopera di una riparazione, dal browser](screenshots/web-ricambi.png?v=v0.45.12)

![I documenti emessi, dal browser](screenshots/web-documenti.png?v=v0.45.12)

## Come lo vuoi tu

In **Configurazione, Opzioni** scegli come lavora il programma: prezzi con IVA, blocco senza giacenza, sconto massimo, mezzi di pagamento proposti, giorni di validità del preventivo, DDT senza prezzi, riconsegna solo con documento, e altro.

![Le opzioni](screenshots/opzioni.png?v=v0.45.12)

- **Utenti e permessi**: ogni utente vede solo le voci di menu che gli lasci, e il server le chiude davvero.
- **Registro delle attività**: chi ha annullato, eliminato o cambiato cosa, e quando.
- **Numeratori** per continuare la numerazione del programma di prima.

## Chiaro e scuro

![Il tema scuro](screenshots/tema-scuro.png?v=v0.45.12)

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
