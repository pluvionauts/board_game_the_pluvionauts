# Livret de Règles des Pluvionautes

## Principe du jeu

Explorez le ciel en tant que **pilote de montgolfière**. A la recherche de la pluie, utilisez votre ballon pour **remorquer des îles volantes** et façonner le ciel à votre avantage !

**Aidez un maximum de villageois** pour être élu le meilleur **pluvionaute** du pays !

## Mise en place

1. La boîte du jeu sert de plateau. Commencez par retirer le **dé montgolfière** ![Balloon die icon](../images/icons/die_balloon.svg), les **12 cartes missions** ![Request card icon](../images/icons/card_request.svg), les **6 bâtiments muraille** ![Wall building icon](../images/icons/building_wall.svg), les **3 bâtiments château d'eau** ![Water tower building icon](../images/icons/building_water_tower.svg) et les **3 bâtiments phare** ![Lighthouse building icon](../images/icons/building_lighthouse.svg) de la boîte. Les **10 îles plaine** ![Plain island icon](../images/icons/island_plain.svg), les **6 îles forêt** ![Forest island icon](../images/icons/island_forest.svg), les **5 îles montagne** ![Mountain island icon](../images/icons/island_mountain.svg) et les **2 dés météo** ![Weather die icon](../images/icons/die_weather.svg) restent dans la boîte.
2. Mélangez la boîte de sorte que chaque **île** et **dé météo** soient placés au hasard sur le plateau. Assurez-vous ensuite que chaque **île** soit correctement placée au centre d'un emplacement hexagonal du plateau, puis placez la boîte au centre de la table.
3. Chaque joueur reçoit **1 bâtiment muraille** ![Wall building icon](../images/icons/building_wall.svg) et aléatoirement, une **1 mission élevage** ![Request card icon](../images/icons/card_request_livestock.svg) et une **1 mission culture** ![Request card icon](../images/icons/card_request_crop.svg) et les place face cachée devant lui. Les joueurs peuvent regarder leur propre **missions** à tout moment pendant la partie. Les **bâtiments** restants sont placé à côté du plateau pour former une **réserve commune de bâtiments**. Les **missions** restantes ne sont pas utilisés pour cette partie.
4. Le premier joueur, choisi au hasard, prend le **dé montgolfière** ![Balloon die icon](../images/icons/die_balloon.svg).

![Schéma de mise en place du jeu.](./images/schema_mise_en_place.svg)
*Représentation du jeu au début d'une partie, mis en place pour 4 joueurs ici.*

## Missions

Le but du jeu est d'aider un maximum de villageois en accomplissant au mieux vos **missions** et être élu le meilleur **pluvionaute** du pays.
Il existe **2** types de **missions** différentes:

* **Les missions d'élevage** : les villageois demandent la plus grande région possible d'un type de **terrain** donné (plaine, forêt ou montagne) indépendamment de la météo.
* **Les missions de culture** : les villageois demandent un maximum de **pluie (sans orage)** sur un type de **terrain** donné (plaine, forêt ou montagne).

Le nombre de villageois aidés est comptabilisé en fonction de l'état du plateau à la fin de la partie:
* **Pour une mission d'élevage** : le joueur aide le nombre de villageois correspondants au nombre d'animaux indiqués sur la carte pour chaque **île** qui compose la plus grande **région** du type de **terrain**  indiqué.
* **Pour une mission culture** : le joueur aide le nombre de villageois indiqués sur la carte pour chaque terrain du type indiqué qui est sous la **pluie (sans orage)**.

<img align="left" width="140" src="./images/mission_elevage.svg" alt="Exemple de mission d'élevage.">
<img align="right" width="140" src="./images/mission_culture.svg" alt="Exemple de mission de culture.">

**Exemples:** 
* L'image de **gauche** est un exemple de **mission d'élevage**. Indiqué par le nombre de rennes, cette mission permet d'aider **2 villageois** pour chaque forêt qui compose **la plus grande forêt** du plateau à la fin de la partie.
* L'image de **droite** est un exemple de **mission de culture**. Indiqué par le nombre de bûcherons, cette mission permet d'aider **3 villageois** pour chaque forêt qui est **sous la pluie (sans orage)** à la fin de la partie.

## Règles de distance

La météo est contrôlé par la position des **dés météo**, indiquant le coeur des nuages, ainsi que leur **valeur**, indiquant la taille de la zone affectée.
Par exemple, une valeur de **2** ![Weather die 2 icon](../images/icons/die_weather_2.svg) indique que toutes les îles qui sont à une distance de **2 OU MOINS** du dé météo sont **sous la pluie**.
Pour une valeur de **5** ![Weather die 2 icon](../images/icons/die_weather_2.svg), toutes les îles qui sont à une distance de **3** sont sous **la pluie (sans orage)** et toutes les îles qui sont à une distance de **2 OU MOINS** sont sous **l'orage**. Mais attention la distance est influencée par la nature du terrain.

La tuile sur laquelle se tient le dé est considéré à une distance de **0**, indépendemment du terrain de la tuile.
La distance d'une tuile adjacente est par contre dépendante du **terrain** de la tuile adjacente :
* Une **tuile vide** adjacente est à une distance de **1**.
* Une **île plaine** adjacente est à une distance de **1**.
* Une **île forêt** adjacente est à une distance de **2**.
* Une **île montagne** adjacente est à une distance de **3**.
La distance des tuiles plus éloigné du dé est calculé en cumulant les distance des tuiles adjacente et en sélectionnant la plus petite distance pour l'atteindre depuis le dé.

![Schéma de mise en place du jeu.](./images/schema_meteo_distance.svg)
*Exemple de la zone d'influence d'un dé météo ![Weather die 2 icon](../images/icons/die_weather_2.svg) à gauche et d'un dé météo ![Weather die 2 icon](../images/icons/die_weather_5.svg)à droite, en appliquant les règles de distance.*

Les mêmes règles de distance sont utilisés pour déterminer :
* les îles atteintes par la météo, 
* la porté maximal de **pilotage de montgolfière** (voir ci-dessous)
* et la porté maximal de **remorquage d'île** (voir ci-dessous).

## Déroulement du jeu

Une partie se compose de plusieurs tours que les joueurs joue l'un après l'autre dans le sens horaire.

Pendant son tour, le joueur effectue les actions suivantes dans l'ordre :
1. **Déploiement de la montgolfière**: lancer le **dé montgolfière** ![Balloon die icon](../images/icons/die_balloon.svg) sur le plateau (voir la section **subtilités du déploiement** pour plus de détails). La position où le dé s'arrête représente l'endroit où à atterrit votre montgolfière après le déploiement. Le nombre sur le dé représente le carburant restant pour continuer à piloter la montgolfière. Si la valeur du dé indique **le dirigeable** ![Balloon die blimp icon](../images/icons/die_balloon_blimp.svg), vous choisissez la face de votre dé **AVANT** de commencer l'action de **pilotage**.
2. **Pilotage du ballon**: déplacer le **dé montgolfière** **AU PLUS** jusqu'à la distance indiquée sur le dé (les **règles de distance** précédentes s'appliquent).
3. **Remorquage d'île:** si le dé a pu être amené sur une île pendant la phase de pilotage, retourner le **dé montgolfière** et déplacer cette île **AU PLUS** jusqu'à la distance indiquée par le nouveau nombre sur le dé (les **règles de distance** précédentes s'appliquent). L'île remorquée ne peut pas être déplacé sur une autre île mais uniquement sur un emplacement vide.
4. Le joueur **PEUT** ensuite effectuer **UNE** des actions suivantes s'il le souhaite :
	* **Prendre un bâtiment** : choisir et prendre n'importe quel bâtiment disponible de la **réserve commune de bâtiments**.
	* **Placer un bâtiment** : placer l'un de ses bâtiments sur une case disponible **adjacente au dé montgolfière** s'il en a un. Un bâtiment doit toujours être placé **adjacent à une île**.

![Schéma récapitulatif des action.](./images/schema_actions.svg)
*Schéma récapitulatif des actions.*

## Bâtiments

<img align="right" width="240" src="./images/schema_destruction_batiment.svg" alt="Exemple de destruction de batiment.">

Les bâtiments sont placés dans les trous rectangulaires entre les cases du plateau.

Un bâtiment **doit toujours être adjacent à une île**. À tout moment du jeu, si un bâtiment n'est plus adjacent à une île, le bâtiment est **détruit** et replacé dans la **réserve commune de bâtiments**.

Les bâtiments ont des effets différents
* la **muraille** empêche les deux îles adjacentes d'être remorquées. Deux cases séparés par un mur ne sont plus considérés comme adjacentes. La muraille agit donc comme une barrière pour la **météo**, le **pilotage de montgolfière** et les **régions**.
* le **château d'eau** fournit en eau les deux tuiles adjacentes.
* le **phare** protège les deux tuiles adjacentes de l'orage.

*Remarque: les murailles, empêchant les deux îles adjacentes d'être remorquées, sont donc indestructibles. Si une île est initialement adjacente à une muraille ou est amenée à proximité d'une muraille déjà placée, elle ne pourra plus être remorqué jusqu'à la fin de la partie!*

## Influencer la météo

La météo est déterminée au hasard au début de la partie, mais peut être modifiée au cours de celle-ci :
* un joueur peut frapper un **dé météo** en le visant pendant **le déploiement de la montgolfière**.
* un joueur peut modifier l'altitude d'un **dé météo**:
	- Si une île est remorquée sous un **dé météo** situé sur une case vide, le **dé météo** augmente sa valeur en fonction du type de **terrain** de l'île :
		* si c'est une **plaine**: +1
		* si c'est une **forêt**: +2
		* si c'est une **montagne**: +3
	- Si au contraire une île est remorquée d'en dessous un dé météo, le **dé météo** reste sur place mais sa valeur diminue de manière équivalente.

Lors des changements d'altitude, la valeur du dé est limité par sa valeur minimale (1 = symbole) et sa valeur maximale (6 = symbole).
		
*Remarque : Lorsque le **dé météo** se retrouve près des limites du plateau, il devient beaucoup plus stable donc difficile à changer lors du **déploiement de la montgolfière**.*

## Fin de la partie

La partie se termine au bout de **5** tours de jeu.

Basé sur la configuration finale du plateau, chaque joueur compte ensuite le nombre de villageois qu'y ont été aidé à travers leur missions.
Le joueur qui a aidé le plus de villageois est déclaré le meilleur **pluvionaute** du pays!

## Subtilités du déploiement de montgolfière

* Lors du déploiement de la montgolfière, la main du joueur ne doit jamais survoler le plateau.
* Si le **dé montgolfière** s'arrête entre plusieurs cases, alors le joueur une parmi celle-ci comme point de départ de pilotage. De même, si un dé météo s'arrête entre plusieurs cases après un lancer, le joueur actuel choisit une de ces cases où placer le dé météo.

* Si le dé montgolfière ne s'arrête pas sur le plateau, le déploiement est annulé et chaque dé météo est remis à sa position et à sa valeur initiale d'avant le lancer. Le joueur a alors une deuxième chance pour déployer son ballon à nouveau. S'il échoue à nouveau, il passe son tour.
* Si un dé météo sort du plateau, le joueur suivant le relance juste avant son tour.
* Un joueur ne peut pas bouger ni faire tourner le plateau. Il peut cependant se lever et tourner autour de la table si nécessaire pour faciliter le déploiement de sa montgolfière.
