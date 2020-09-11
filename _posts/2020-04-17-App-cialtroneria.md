---
layout: post
title:  "App e cialtroneria"
date:   2020-04-17
tags:
  - dataporn
---

*[cialtróne](http://www.treccani.it/vocabolario/cialtrone/) s. m. (f. -a) [etimo incerto]. – Persona volgare e spregevole, arrogante e poco seria, trasandata nell’operare, priva di serietà e correttezza nei rapporti personali, o che manca di parola nei rapporti di lavoro. Anche, con sign. attenuato, persona sciatta nel vestire e nel portamento, o che nel lavoro sia solita fare le cose in fretta e senza attenzione*.

Per l'[ordinanza 10/2020](http://www.governo.it/it/dipartimenti/commissario-straordinario-lemergenza-covid-19/14483) del commissario Arcuri ci sono gli elementi per definire "cialtrone" l'approccio, sia nella definizione primaria che quella attenuata.

Partiamo proprio dal sito del Governo che è pubblicato in assenza delle basi di messa online delle informazioni: manca la connessione criptata in [https](https://it.wikipedia.org/wiki/HTTPS).

![Governo senza ssl](/assets/img/photo/Governo_non-sicuro.png)

 Cito da wikipedia

> HTTPS fornisce l'autenticazione del sito web e del server web associato con cui una delle parti sta comunicando, proteggendo la comunicazione dagli attacchi noti tramite la tecnica del man in the middle. [...] In pratica, tale meccanismo fornisce una garanzia soddisfacente del fatto che si sta comunicando esattamente con il sito web voluto (al contrario di un sito falso), oltre a garantire che i contenuti delle comunicazioni tra l'utente e il sito web non possano essere intercettate o alterate da terzi.

Le premesse di cialtroneria proseguono nello specifico dell'ordinanza quando si entra nel merito della licenza d'uso e del codice sorgente della app di contact tracing. Non entro nello specifico delle qualità e delle caratteristiche tecniche perché non ho competenze, mi limito agli elementi di trasparenza e termini d'uso.

Il [decreto 33/2013](https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2013-03-14;33!vig=2020-04-17) regola i termini di accesso ai dati della Pubblica Amministrazione. Questi termini sono stati [sospesi](http://www.funzionepubblica.gov.it/articolo/dipartimento/03-04-2020/decreto-%E2%80%9Ccura-italia%E2%80%9D) fino al 15 aprile, quindi *in teoria* dovrebbero essere accessibili i termini del *contratto di concessione gratuita della licenza d’uso sul software di contact tracing e di appalto di servizio gratuito con la società Bending Spoons S.p.a.*.

Nell'ordinanza in 23 righe riescono a dire 4 cose diverse:

1. licenza aperta a Commissario e Presidenza del Consiglio
2. Bending Spoons mantiene la titolarità e proprietà intellettuale
3. "qualcuno" non specificato procede all'acquisizione del diritto d'autore del codice
4. si fa un contratto di concessione gratuita della licenza

Che la società Bending Spoons mantenga la proprietà intellettuale mi pare giusto, perché in sostanza si dirà sempre che l'hanno fatta loro. La titolarità però è un po' più delicata, perché potrebbe limitare le possibilità di modifica dei codici sorgenti. Soprattutto la pubblicazione del codice.

Si dirà che il codice non può essere pubblicato *perché degli hacker potrebbero violare la app e rubare tutti i dati*. Questo non sarebbe un rischio nel codice ma nei server in cui verrà installata la app e i criteri di trasmissione e condivisione dati. Se il sito stesso del Governo non usa connessioni criptate in https, non so se queste protezioni verranno naturali applicarle per la app di contact tracing.

La pubblicazione del codice è invece utile proprio per segnalare eventuali bug o migliorie e tranquillizzare i cittadini nell'uso. Più un codice è usato e analizzato meglio è. Però se Bending Spoons, con il proprio business model, valutasse come un danno la pubblicazione del codice, stando a quanto scritto nell'ordinanza si può opporre. E tutti gli elementi di trasparenza sarebbero persi.

Il punto non è la cialtroneria nell'approccio e nella scrittura di questi documenti, ma anche nella stessa gestione. Anni di abuso di termini come opensource, egov, riuso, opendata, linked open data, open innovation e ora la fenomenale "blockchain", hanno svuotato di senso e di interesse i concetti a cui si riferiscono. Dire che una licenza è gratuita, aperta e perpetua ha un significato giuridico, economico e sociale molto profondo. Rendere pubblico un codice che traccia le persone e comunica informazioni sanitarie è un dovere civico, per verificare che non ci sia alcun elemento malevolo. Il codice sorgente non è la copia della chiave per la porta dei dati di tutti i cittadini tracciati.

La sicurezza non è minata dai milioni di server con sistemi operativi opensource, ma da procedure e contratti di fornitura fatti e svolti in maniera cialtrona. Sono i nomi utente "admin" e le password "123456" usati sui server di banche, ministeri e dipartimenti. Sono sistemi che trattano documenti, database e codici senza controllo di versione. Sono le banche dati prive di specifiche di interoperabilità affidate ad aziende che poi subappaltano all'infinito perché "tanto nessuno controlla". Sono gestionali che muovono milioni di dati pubblici che nei contratti non hanno specificato il carico minimo (INPS ad esempio).

È il diprezzo per il tempo e le capacità di esperti chiamati in fatiscenti task force che si sbattono e poi vedono il proprio lavoro svilito in documenti e annunci cialtroni. Basta. Se siete esperti, se avete professionalità, lasciate sole queste strutture. Non date scuse alla cialtronieria burocratica.


### Bonus track - approfondimento noioso

Nel "considerato" a pag. 3 si legge che:

1. "licenza d'uso aperta e gratuita e perpetua"
2. vengono cencessi al Commissario (?) e alla Presidenza del Consiglio dei ministri (??)
3. i codici sorgente e le componenti applicative
4. Bending Spoons completeranno lo sviluppo e messa produzione

Parto dal punto 1, e immagino che la licenza sarà scelta tra licenze aperte come [MIT](https://en.wikipedia.org/wiki/MIT_License), [Gnu GPL](https://www.gnu.org/licenses/gpl-3.0.en.html), mentre non capisco perché l'uso debba essere concesso a un soggetto temporaneo (Commissario) e a una struttura come la Presidenza del Consiglio, quando invece la presa in carico deve essere data direttamente ad un ministero e relativo dipartimento. La necessità dell'individuazione di un dicastero e relativo dipartimento amministrativo èserve per individuare chi prende in consegna i codici sorgente e i componenti che devono essere valutate da tecnici interni e esterni, con pareri di Garante Privacy per l'allineamento con i necessari database e anagrafiche. Il tutto tenendo conto che, almeno nell'ordinanza, Bending Spoons concluderà lo sviluppo e la messa in produzione, ma la manutenzione e le implementazioni saranno a carico o degli uffici pubblici o di altri fornitori che saranno sottoposti a contratto.

Poi si confondono le cose: nel "rilevato" si ribadisce la titolarità e la proprietà intellettuale in capo a Bending Spoons. Oltre a non essere ribaduto il termine "gratuito" espresso nel "ritenuto", si dice che la app è di Bending Spoons e che ogni parte (nome, codice, architettura di sistema...) è e rimane in capo a Bending Spoons. La società dà la licenza d'uso, quindi si presuppone che Commissario e Presidenza saranno gli unici concessionari in cui gli elementi "gratuito e perpetuo" scompaiono. Questo genera confusione perché se prima la "solidarietà" di Bending Spoons si concretizzava con una licenza aperta, gratuita e perpetua, nel periodo successivo si tratta come un normale contratto di acquisto di licenza d'uso. Questo non è un problema in sé, ma limita la possibilità di ispezione del codice e di eventuali modifiche e migliorie. Immaginiamo che i tecnici degli uffici chiedano accesso al codice per cambiare le modalità di scambio con i server, queste attività saranno possibili? I codici saranno consegnati e installati nei server dii qualche ministero? Chiaramente queste specifiche sono oggetto di clausole di contratto, ma se già l'ordinanza fa confusione crea dei problemi di chiarezza.

Nel "ritenuto" finale la confusione aumenta perché si dichiara "opportuno" acquisire il diritto d'autore sui codici da Bending Spoons e nella "disposizione" si dice di stipulare un contratto per la concessione gratuita della licenza d'uso. CAOS TOTALE.
