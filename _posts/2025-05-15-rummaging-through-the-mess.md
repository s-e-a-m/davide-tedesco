---
title: "Rummaging through the mess"
excerpt: "Sostenibilizzando C.A.G.E. - 2025-05-15"
categories:
  - Diary
tags:
  - C.A.G.E.
  - guitar
---

## Intro

Lo so che devo ancora linkare le pagine html menzionante nel post precedente, lo farò poi...

All'inizio dei tempi il progetto C.A.G.E. nacque da un'idea che avevo iniziato a sviluppare durante il secondo anno di Biennio presso il Conservatorio di Musica S.Cecilia.

Preso dalla voglia di affrontare, finalmente, l'aumentazione di uno strumento, mi misi subito al lavoro per poter avere un controllo di tutto ciò che volevo realizzare sulla chitarra.

Non ci volle molto per comprendere che fossero necessari alcuni strumenti di base.

## I primi moduli per la costruzione di C.A.G.E.

### Gesture->Analog
Per poter far funzionare la chitarra classica aumentata servivano sicuramente 4 componenti di base nella versione analogica (la cito perchè avanti nei prossimi racconti cercherò di far comprendere come il paradigma analogico siamo molto importante e rilevante):
- una chitarra classica da poter martorizzare
- un attuatore
- un sensore piezo-elettrico
- un amplificatore

### Analog->Digital

Sin dalle prime prove, si rese necessario però introdurre un controllo a basso costo molto rilevante sul segnale.

Tutto ciò venne risolto in men che non si dica (in realtà ci penai un po') con dei piccoli programmini compilati tramite uno dei target di FAUST (reperibili [qui](https://gitlab.com/SMERM/BN-Tedesco/-/blob/master/COME-02/Primo_anno/Lezioni_in_Compresenza/20200512/FEEDBACK_CONTROLLER.dsp)).

Si usava in tale contesto:
- una chitarra classica da poter martorizzare
- un attuatore
- un sensore piezo-elettrico
- un amplificatore
- una scheda audio
- un computer

## Cosa si muove e perchè?


### Piezo fisso, attuatore fisso

Sin dall'inizio avevo pensato di dover tener fisso il sensore sullo strumento, incollato come nel [Feed-Drum](https://www.crm-music.it/index.php/invenzioni/strumenti-aumentati/feed-drum) di Lupone, insieme all'attuatore, anch'esso fisso per realizzare e far emettere allo strumento le frequenze possibili vincolando il piano armonico con la mano.

Come si può vedere ed ascoltare [qui](https://www.youtube.com/watch?v=TraqAMf5Exo).

### Piezo mobile, attuatori fissi

La versione realizzata per i concerti del 2024, mi ha portato a cambiare il paradigma, andando a tenere fissi gli attuatori (che nel frattempo sono diventati 3 più un sub esterno (di cui parlerò più avanti)) e di muovere il sensore piezo elettrico, andando a inserire una sorta di lente di ingrandimento nelle mani dell'interprete.

Tale inversione del funzionamento dello strumento ha reso l'ergonomicità e le possibilità molto maggiori rispetto all'inizio.

### Perchè?

Tale metodo di realizzazione del feedback (perchè di feedback stiamo parlando, anche se non è stato ancora citato espressamente), ha reso integrabili ai movimenti dell'interprete, dei movimenti tradizionali delle mani della pratica chitarristica, andando a fondere (anche se ancora a livello troppo rudimentale), una gestualità vicina a quella chitarristica contemporanea.

## Outro

L'utilizzo di una catena elettroacustica con parti digitali, oltre al nuovo modo di gestire il suono tramite il movimento del sensore, lasciando fermo/i gli attuatori, ha portato poi alle realizzazioni dei concerti, con l'utilizzo del sensore/lente nella ricerca dei fenomeni di retroazione causati da tutto l'apparato utilizzato.

Durante le prime analisi, e soprattuto durante i primissimi studi ho pensato e ripensato più volte alla scrittura chitarristica arrivando a scrivere anche un testo, mai pubblicato o distrubito dal titolo esuberante _Verso una nuova frontiera della chitarra classica_ reperibile [qui](https://gitlab.com/SMERM/BN-Tedesco/-/blob/master/COME-02/Primo_anno/Davide_Tedesco_Verso_una_nuova_frontiera_della_chitarra_classica/Davide_Tedesco_Verso_una_nuova_frontiera_della_chitarra_classica.pdf), in esso riassumevo la prima parte di studio/composizione/pensiero che di quei periodi, andando a sedimentare prima di proseguire il viaggio.