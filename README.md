# Sapin_de_Noel_Wled
Réalisation d'un sapin de Noel avec des leds adressables et WLED

Aller sur ce Git: http://wled.me/
pour telecharger le fichier WLED_011.0_ESP8266.bin (je l'ai aussi mis sur Github avec le logiciel de flash).

Connecter ensuite l'esp8266. pour ma part un nodeMCU V3 (https://fr.aliexpress.com/item/32656775273.html?spm=a2g0o.productlist.0.0.20827d96Esrnrk&algo_pvid=98176f4b-a0eb-410f-b8e4-74197047aa48&algo_expid=98176f4b-a0eb-410f-b8e4-74197047aa48-0&btsid=0bb0623616080561437848349edde9&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_)

le flasher avec le fichier precedent par l'aplication ESPHome_flasher (dispo aussi ici)

le redemarrer et se connecter au nouveau reseau WLED-AP avec le mdp wled1234

Normalement un navigateur s'ouvre sinon rentrer l'IP 4.3.2.1

Aller dans wifi settings et saisir son reseau wifi et sont mdp
saisir aussi un nom d'adresse (pour mon ca wled-led1)

Cliquer ensuite sur Save and reboot
rebooter physiquement l'ESP

Se reconnecter au Wifi de la maison et saisir l'adresse http://wled-led1.local dans mon cas
on peut qller apres dans les reglages wifi pour trouver l'adresse IP.
Cet IP peu ensuite etre utiliser pour générer un QRCODE qui permet l'acces sur une page web aux reglages des leds.

Bien connecter le fil de données des leds sur D4
et biensur une alim externe pour les leds si il y en a beaucoup.

Il y a aussi une apli sur Iphone qui fait le job et qui est assez bien foutu

voila plus qu'a essayer, creer des synchros etc...

Pour les plus mordus qui veulent faire comme sur les videos d'eclairage de noel de fous aux USA, les wemos peuvent etre gérés par un controleur DMX.
