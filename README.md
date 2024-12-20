# PAC 3 - Visionant el futur amb les ulleres de Manovich: Redescobrint la hibridació

**Autora:** Erola Vilella Sepúlveda


## 1. Els jocs de taula en el món de la Realitat Virtual i Realitat Augmentada

Un cas d'hibridació que podem trobar actualment és el dels jocs de taula en entorns de Realitat Virtual o Realitat Augmentada. Els jocs de taula, ja siguin simples com ara el parxís o més complexos com el "Dungeons and Dragons" sempre han tingut un públic molt ampli i han estat un bon passatemps per a amics i familiars. L'auge dels videojocs i la globalització va donar peu a la creació de videojocs on s'hi podien jugar jocs de taula, i en els darrers anys, aquests jocs s'han adaptat a la realitat virtual i augmentada.

Alguns dels exemples que podem trobar són jocs com ara l'[All on Board](https://thegamekitchen.com/all-on-board-vr/) o el [Tabletop Simulator](https://www.tabletopsimulator.com/). Mitjançant unes ulleres de Realitat virtual com ara les [Quest 3](https://www.meta.com/es/quest/quest-3s/) o les [PS VR](https://www.playstation.com/es-es/ps-vr/) podem jugar a temps real amb els nostres amics que estàn a kilòmetres de distància. 
Aquests jocs ens permeten jugar tal i com ho fariem a la vida real, movent manualment les peces una per una, agafant les cartes, tirant els daus nosaltres mateixos en un entorn totalment virtual.

![All on Board](https://distritoxr.com/wp-content/uploads/2023/09/All-on-Board-1366_2000.jpeg)
A més, els personatges que utilitzem es mouen de la mateixa forma que ho fariem nosaltres; de per si tenim sensors al cap (les ulleres) que capten el moviment del nostre cap. També tenim dos controladors, un per cada mà que ens permetes realitzar diverses accions. Els models també mouen els ulls de forma automàtica i la boca, utilitzant un sensor sonor.
Alguns dels jocs permeten inclús incorporar "trackers" de cos sencer, cosa que ens permetria moure'ns lliurement per l'espai i que el joc captés els nostres moviments amb alta fidelitat.

**PRINCIPIS DE LA HIBRIDACIÓ APLICATS AL CAS**

 - **Representació numèrica:** El funcionament del joc està basat en operacions matemàtiques en tot moment. Per a digitalitzar-l'ho i automatitzar-l'ho s'han hagut de fer centenars d'operacions referents al joc, als personatges, al moviment...
 - **Modularitat:** El concepte de joc virtual és molt modular i consisteix en un conjunt de diverses peçes que conjuntament creen el joc. En aquest cas tenim tenim diversos jocs amb mecàniques diferents, que es poden reutilitzar, com ara els daus, el sistema de cartes, les peçes del tauler...
 - **Automatització:** Per a facilitar la implementació dels jocs en l'entorn virtual s'han automatitzat certes tasques com ara la puntuació (que s'actualitza automàticament), la barreja i el repartiment de cartes i/o inclús el recompte de monedes per a cada jugador.
 - **Variabilitat:** Tal i com s'ha mencionat en el principi de "Modularitat", hi ha elements que es poden reutilitzar en diversos jocs, com ara els daus. També tenim personalització de les sales i dels personatges, fent que cada un tingui una experiència feta a mida.
 - **Transcodificació:** S'ha agafat un recurs tradicional, els jocs de taula, i s'ha digitalitzat per a poder practicar-se en l'entorn virtual.
 

## 2. Streamers i Idols Virtuals

En els últims anys s'ha popularitzat la creació de contingut online, però tot va començar al 2005, quan [Jawed Karim](https://es.wikipedia.org/wiki/Jawed_Karim), co-fundador de Youtube, es va fer el primer compte de Youtube. A partir d'aquí cada cop més gent va començar a pujar vídeos i, uns anys més tard, a fer directes a temps real.
Aquest tipus de contingut normalment s'ha realitzat mitjançant captures de pantalla i a vegades "webcams" amb les quals els "youtubers" i "streamers" ensenyen la seva cara.

A començaments de 2014 però, va començar a surgir una nova moda al Japó anomenada "[VTuber](https://es.wikipedia.org/wiki/VTuber)". És un joc de paraules entre "Virtual" i "Youtuber".
Els i les VTubers són creadors de contingut que, en ves d'ensenyar la seva cara, utilitzen un avatar 2D o 3D que captura els moviments de la cara; ulls, boca i inclús del cos. A poc a poc es va anar popularitzant a Estats Units i ara sembla que va arribant a Europa.

Una de les coses vitals a l'hora de crear videos i fer directes és l'expressivitat del creador, i, estant darrere d'un avatar això pot arribar a ser complex. És per això que existeixen dos tipus de "VTubers": 

 1. Model 2D (altrament dit Live2D): utilitzat un sistema de captura d'imatge que detecta punts claus de la cara, un avatar 2D es mou de forma síncrona amb el creador. Només permet el moviment de cap i cara, i moviment de mans limitat.
 
![Model Live2D](https://www.live2d.com/wp-content/themes/cubism_new/assets/img/cubism/cubism-about_02.jpg)[Imatge de Live2D Cubism](https://www.live2d.com/en/).

 2. Model 3D: si es disposa de sistema de "tracking" de cos sencer es pot arribar a moure tot el cos de forma molt fidel a la vida real, incloent els dits i la cara.
 
   ![Code Miko](https://i.ytimg.com/vi/RValfgNuP4U/hq720.jpg?sqp=-oaymwEhCK4FEIIDSFryq4qpAxMIARUAAAAAGAElAADIQj0AgKJD&rs=AOn4CLDIQr5sdJJ7vnoxHwsiSkbgMrf_1w)[Imatge de Code Miko](https://www.youtube.com/c/codemiko).
   
   Aquesta nova forma de crear contingut ha estat molt ben valorada recentment ja que no només incrementa la seguretat i privacitat de la persona que hi ha darrere creant el contingut, sinó que obre portes a molts altres tipus de contingut. 
   Sobretot a Àsia, que és on més públic hi ha del sector, s'estan fent [concerts i grups de música](https://www.youtube.com/watch?v=CDljbqawDkw) on tots els integrants són virtuals, utilitzant els mateixos mètodes mencionats anteriorment. També s'estan fent sèries d'animació i inclús surten a televisions públiques. És una manera de digitalitzar encara més la creació de contingut.

**PRINCIPIS DE LA HIBRIDACIÓ APLICATS AL CAS**

 - **Representació numèrica:** La creació dels models utilitza milers de formes matemàtiques per a calcular el moviment, gravetat, il·luminació a temps real...
 - **Modularitat:** És molt modular. Permet canviar i modificar qualsevol cosa en un segon, ja sigui el model, que pot canvair de roba o pentinat de forma quasi instantània, com l'escenari. A més, també és molt més fàcil d'adaptar al contingut, videojocs en particular.
 - **Automatització:** Permet l'automatització de tasques secundàries com ara modificacions de l'escenari o del model a temps real.
 - **Variabilitat:** Els models 2D i 3D donen joc a infinitat de propostes. Des de fer vídeos i directes, a fer concerts, sortir a la televisió, estar en videojocs, etc.
 - **Transcodificació:** S'ha agafat un recurs més tradicional, que és fer contingut ensenyant la cara, i s'ha digitalitzat de tal forma que els creadors estan darrere d'un avatar.

## Referències

 1. [Manovich, Lev. (2013) *El software toma el mando*](https://es.slideshare.net/slideshow/principios-de-lev-manovich/3439954)
 2. [Descals Ruiz, Núria. (2010) *Principios de Lev Manovich*](https://es.slideshare.net/slideshow/principios-de-lev-manovich/3439954)
 3. [The Game Kitchen. (2025) *All on Board*](https://thegamekitchen.com/all-on-board-vr/)
 4. [Berserk Games. (2014) *Tabletop Simulator*](https://www.tabletopsimulator.com/)
 5. [Code Miko. (2017)](https://www.youtube.com/c/codemiko)
 6. [Live2D Cubism. (2008)](https://www.live2d.com/en/)
