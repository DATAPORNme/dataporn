---
layout: post
title:  "Il CNR genera nuovi Mosconi"
date:   2021-12-17
tags:
  - dataporn
---

Ciao, sono Luca. Qualcuno mi conosce per l'interpretazione di Cacciari nei famosi film "Lo dico da 20 anni che i dati devono essere condivisi" o "Quel maledetto dataset per Yuma". Oggi un amico, ricercatore del CNR, mi *tagga* su Facebook un articolo dell'ufficio stampa del CNR [Cnr realizza attraverso OpenAIRE un unico punto di accesso ai risultati della ricerca](https://www.cnr.it/it/news/9333/covid-19-il-cnr-realizza-attraverso-openaire-un-unico-punto-di-accesso-ai-risultati-della-ricerca?fbclid=IwAR2VDdDw7vWjKwSqHUqIWWpc8oNYnUyz_b5BcKq_9sbuhy6DyQMsoF5C544) relativo alla lotta contro il COVID19. Ora, perché tiro in mezzo la memoria del Patrono [Germano Mosconi](https://youtu.be/BaFbXcjy22o)?
## I precedenti
![Cacciari](/assets/img/photo/cacciari.jpg)
Dalle altre mie passate interpretazioni di Cacciari, ad esempio [Dati verità e tempo](https://dataporn.me/2020/03/10/dataporn-12-Dati-verit%C3%A0-tempo.html) oppure [Chiedere la gestione e distribuzione dei dati](https://dataporn.me/2020/11/10/gestione-distribuzione-dati.html), datate ormai 2020 rimane però emblematico [Paesaggi Aperti](https://zenodo.org/record/1220069#.YbxYHBNKgwM) datato addirittura fine 2017. Non provate il link a paesaggipaerti.org perché il dominio non è stato rinnovato ma è una storia molto divertente.

## Zenodo, Gitea e compagnia cantante
Avete presente quando c'è un problema e si cerca di risolverlo? Ecco, il problema allora era: *dove mettiamo i dati paesaggistici e bioeconomici avendo un'infrastruttura a basso costo e il più integrata possibile?*. Dopo circa una settimana di ricerche, del resto eravamo al CNR, abbiamo individuato in [Gitea](https://gitea.io/en-us/) e [Zenodo](https://zenodo.org/) il mix perfetto:
1. una piattaforma interna al CNR per i repository
2. un sistema di conservazione permanente con autorità (il CERN) che in più forniva gratuitamente DOI e relazione con Github.

Una bomba! Cosa facciamo quindi: lo presentiamo al GARR a novembre 2017. Andai io a presentare il progetto, costo totale meno di 5000€ che comprendeva:

1. acquisto dei server
2. data management plan
3. open business model per i dati
4. installazione e manutenzione dell'applicativo
5. supporto tecnico e attività di formazione
6. documentazione di manutezione post incarico

Al GARR praticamente venni trattato come il bimbo che mostra la casetta fatta con i Lego. Era il 2017. Assieme a me c'erano altri ricercatori che presentavano progetti dal costo di oltre 100.000€ che poi alla fine servivano a coprire assegni di ricerca, per i quali non era previsto alcun modello di gestione dopo i fondi di lancio. Altra cosa divertente: altri ricercatori andarono a chiedere al CNR di usare un servizio privato per ottenere DOI, sbagliando il tipo di DOI, scegliendo quello che copriva solo le pubblicazioni e non i dataset. Pensare che la CRUI (che ritengo essere la vera Tana delle Tigri), da l'uso gratuito e illimitato di DOI per università e centri di ricerca.

## E quindi, che c'entra Mosconi?
Dopo le varie disavventure, mantenemmo assieme ai ricercatori coinvolti per un anno il dominio attivo e l'infrastruttura e successe una cosa strana. Altri loro colleghi, che avevano necessità di depositare i dati iniziarono a chiedere in maniera carbonara di usare il sistema di paesaggiaperti, ma di fatto il progetto morì sul nascere tra indifferenza e sospetti: *questi vogliono condividere i dati!!*. Ad oggi mi pare che lo usino ancora usando l'IP interno, ma di fatto ha privato per oltre 4 anni il CNR di un metodo e uno strumento che oltre ad avere in casa era (ed è) facilissimo da mantenere con costi ridicoli (siamo sull'ordine di poche centinaia di euro). Io immagino i vari ricercatori che, non sapendo dell'esistenza di paesaggiaperti e Gitea, tirano giù bestemmie ogni giorno per sapere dove mettere i dati e ottenere dei DOI, senza compilare moduli di richiesta.

## Un sacco bello
Potrebbe sembrare uno dei tanti post passivo-aggressivo, in cui il genio incompreso di turno urla contro il mondo che non lo capisce. Per fortuna, a differenza di Cacciari, la mia vanità viene sistematicamente bastonata da mia figlia e mia moglie oltre agli amici che giustamente mi vedono per quello che sono *il solito cazzone* (ovviamente non riferito a mie doti priapesche). Quello che mi fa ridere è che quando l'amico ricercatore mi ha raccontato di questo articolo, mi è venuto in mente il Professore di Un sacco bello: questo di paesaggiaperti è diventato
> un episodio che amo ricordare. Era l'inverno del 2017, che peraltro fu un invero rigidissimo, e alcuni ricercatori del CNR non sopportando un sistema a basso costo per condividere i dati con DOI uscirono dall'ufficio sbattendo la porta. Io allora li raggiunsi, li fissai negli occhi e dissi loro "da domani per gestirete i dati sarà come andare in giro senza scarpe, a piedi nudi". La sera stessa trovai nella mia casella una mail. Sapete cosa c'era scritto? **'A STRONZO PUNTO ESCLAMATIVO!**

<iframe width="560" height="315" src="https://www.youtube.com/embed/GvriD86-tEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
