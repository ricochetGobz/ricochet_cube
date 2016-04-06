# Ricochet Cube

Cube Ricochet permettant de jouer un son. Chaque face du cube (6 faces) représente une note du plus grave au plus aigue. Un cube peu être activée et gère les sons joués.

## UML



<img alt="Ricochet cube UML" src="https://github.com/ricochetGobz/ricochet_cube/blob/master/ASSETS/Ricochet_cube-UML.png?raw=true">

## Functionnalities





## Important Components

- **1 ESP8266 :** Module wifi pour la connection permettant aussi la transimission d'informations à l'arduino micro via Serial. Voir aussi [Ricochet_test_wifi](https://github.com/ricochetGobz/ricochet_test_wifi)

- **1 Arduino Micro :** Captation des évènements tel que le `touch`, la `rotation`. Contrôle des sons ainsi que les LEDs.

- **1 Batterie OU piles boutons :** 3.3V pour alimenter le tout.


#### Capteurs

- **Capacitive Touch :** pour capter une action sur le cube. à l'aide de fils conducteurs.

- **Acceleromètre :** captation de l'angle sur lequel le cube se trouve.


#### Actionneurs

- **Module MP3 :** il permet de contrôler et stocker les sons.

- **Haut-parleur :** il émet les sons contrôlé par le module MP3.

- **LED RGB :** controlé par l'Arduino, elle complèe le language graphique.


## Cabling



## Fabrication

*[FabLab cité des sciences](http://carrefour-numerique.cite-sciences.fr/fablab/wiki/doku.php?id=index)*

First craft :

- Découpe laser
- Planche bois 5mm

<img alt="Ricochet cube UML" src="https://pbs.twimg.com/media/CfWh9KuWIAES5ie.jpg">


 