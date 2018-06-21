---
layout: centrale
title:  "PiezoPinza"
date:   2018-05-30
published: true
permalink: ../piezopinza
categories: progetti
tags: ahl piezo microphone diy
sito: http://audiohacklab.org/
autori: Tito Castelli, Francesco Pasino, Andrea Reali
copertina: piezopinza/piezopinza-cover.jpg
meta: un microfono piezoelettrico pensato per essere pinzato alle superfici
---

<!-- Intro -->

Ormai sono anni che Audio HackLab sperimenta con i dischi piezo utilizzandoli come microfoni a contatto. Uno dei modi più efficaci di utilizzarli è pinzarli alle superfici da microfonare, ecco perchè abbiamo unito un disco piezo, una pinza e un jack.

Abbiamo documentato il tutto step by step.

### Step 1: Lista dei materiali

 Ecco la lista dei materiali che abbiamo usato:

![](../../img/piezopinza/01-materiale.jpg)

- Pinza in plastica con punta a morsetti basculanti
- Trasduttore piezoelettrico (aka piezo buzzer)
- Presa jack femmina mono volante, da ¼ di pollice (6,3mm)
- 15 cm circa (dipende dalle dimensioni della pinza) di cavo microfonico schermato

Inoltre abbiamo utilizzato i seguenti strumenti:
- saldatore e stagno
- terza mano
- taglierino
- forbici
- colla epossidica bi-componente (al suo posto si può anche usare la colla a caldo, ma dura sicuramente meno sul lungo periodo)


### Step 2: Modifica del jack e della pinza

Abbiamo estratto il jack dalla sua guaina e l'abbiamo tagliata della misura adatta per il manico della pinza.

![](../../img/piezopinza/02-jack.jpg)

![](../../img/piezopinza/03-taglio-jack.jpg)

Per far spazio alla guaina del jack abbiamo rifilato il bordo della pinza con un taglierino, rimuovendo la parte tonda.

![](../../img/piezopinza/04-pinza.jpg)

![](../../img/piezopinza/05-taglio-pinza.jpg)


### Step 3: Incollaggio jack/pinza

![](../../img/piezopinza/06-incollaggio-jack.jpg)

![](../../img/piezopinza/07-incollaggio-jack-2.jpg)

Con la colla epossidica abbiamo cosparso l’interno del manico della pinza e un lato della guaina del jack per incollarle tra loro: ovviamente la filettatura va verso l’esterno della pinza.

### Step 4: Preparazione del jack e del cavo

Dopo aver spellato circa un centimetro di cavo abbiamo intrecciato la calza con il polo nero e il polo rosso su se stesso.
Poi li abbiamo stagnati per facilitare il passaggio successivo.   

![](../../img/piezopinza/08-preparazione-cavo.jpg)

Abbiamo prestagnato anche i terminali del jack.

![](../../img/piezopinza/09-preparazione-jack.jpg)


### Step 5: Saldatura del jack con il cavo

Il polo nero (intrecciato con la calza) l'abbiamo saldato alla massa del jack (ground) e il polo rosso al terminale corrispondente alla punta del jack o “tip”. Nel nostro caso il terminale più largo è la massa, ma questo può variare in base al modello.

![](../../img/piezopinza/10-saldatura-jack.jpg)

![](../../img/piezopinza/11-saldatura-jack-2.jpg)

Consulta il datasheet del tuo jack per capire a cosa corrispondono i terminali oppure aiutati con un tester che abbia il controllo di continuità: inserisci un jack maschio e verifica a quale dei due poli della femmina sono collegati la punta del cavo e la base del cavo (gnd). Non hai un tester? Usa una pila ed un led!

### Step 6: Inserimento del jack

Per inserire il jack abbiamo prima infilato il cavo nella guaina facendolo passare sotto la molla e poi avvitato.

![](../../img/piezopinza/12-inserimento-jack.jpg)


### Step 7: Saldatura del piezo

Tagliato il cavo della giusta misura abbiamo prima saldato il terminale rosso alla parte ceramica del piezo (quella centrale bianca) e poi il terminale nero al bordo in metallo, questa volta senza calza metallica altrimenti la schermatura non avrebbe effetto.

![](../../img/piezopinza/13-saldatura-piezo.jpg)

La parte in ceramica è molto delicata, quindi se vuoi saldare anche tu un piezo usa temperature basse per il sadatore e tenta di metterci meno tempo possibile. E salda abbastanza vicino al bordo per facilitare il prossimo passaggio.


### Step 8: Incollaggio del piezo

Con un altro po’ di miscela di colla abbiamo cosparso delicatamente il piezo in modo da ricoprire tutto il lato della saldatura.

![](../../img/piezopinza/14-incollaggio-piezo.jpg)

Tenendo la pinza aperta abbiamo posizionato il piezo facendo attenzione a mantenere i punti di saldatura verso l’interno della pinza e a non incastrarli tra il piezo e la punta della pinza stessa.     

![](../../img/piezopinza/15-incollaggio-su-pinza.jpg)

![](../../img/piezopinza/16-pinza-piezo.jpg)

Dopo aver chiuso la pinza, facendo attenzione a non spostare il piezo, abbiamo utilizzato il residuo di colla per rifinire e consolidare il tutto.

### Step 9: Collaudo!

A colla asciutta siamo passati al collaudo. Il jack alla pinza si usa come un normale microfono e l'abbiamo collegato ad un amplificatore: pronti per ascoltare suoni inediti?

![](../../img/piezopinza/piezopinza-cover.jpg)

Noi l'abbiamo provato pinzando oggetti metallici vari: reti, molle, corde, ringhiere, etc.; ma anche tavoli e strumenti musicali. Abbiamo anche aggiunto un delay luuuungo per un risultato straordinario!   

Per qualsiasi dubbio, per farci vedere la tua nuova pinza o farci ascoltare i suoni che hai registrato, scrivici a: info@audiohacklab.org

Autori: _Tito Castelli_, _Francesco Pasino_, _Andrea Reali_


<!--more-->
