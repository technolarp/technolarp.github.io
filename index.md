:construction: Projet en construction :construction:

# Présentation du Projet
***TechnoLarp*** est une solution “clef en main” visant à rendre accessible à tout organisateur de [Jeu de Role Grandeur Nature](https://fr.wikipedia.org/wiki/Jeu_de_r%C3%B4le_grandeur_nature) la possibilité d’intégrer dans ses événements des objets de jeu ou décors interactifs reposant sur des moyens électroniques. 

:package: En termes techniques, les dispositifs TechnoLarp se composent de :
* Un ou plusieurs microcontrôleur de type [esp8266](https://fr.wikipedia.org/wiki/ESP8266) (de type [wemos/lolin](https://www.wemos.cc/en/latest/d1/d1_mini.html)).
* D’un circuit imprimé (PCB) et de connecteurs soudés
* De périphériques d’entrée / sorties divers (boutons poussoirs, potentiomètre, capteurs, écran oled, afficheur 7 segments, leds RGB, …)

# Conception
Les dispositifs ***TechnoLarp*** seront conçus pour être :
* :bust_in_silhouette: **Faciles d’utilisation pour les organisateurs**
  *  :computer: **Aucune compétence en électronique ou en programmation requise** : Il sera possible d'adapter les dispositifs aux besoins de votre événement uniquement par des actions de configuration.
  *  :toolbox: Une fois les connecteurs soudés au PCB, aucune autre soudure n’est nécessaire (le déploiement d’un dispositif se limitera à brancher des câbles en suivant les instructions du manuel ou des vidéos explicatives)
  *  :books: L’ensemble des opérations de déploiement et d’utilisation des dispositifs TechnoLarp seront détaillés dans un manuel clair, exhaustif et illustré ainsi qu’un ensemble de capsules tutoriels-vidéo.
*  :crossed_swords: **Adaptés aux besoins et cas d’utilisation de la pratique du GN**
*  :bulb: **Autonomes** : Les dispositifs ***TechnoLarp*** seront conçus pour qu’une fois déployés les joueurs puissent interagir avant sans nécessiter d’action de la part d’un organisateur.
*  :bricks: **Robustes** : L’utilisation de systèmes électroniques dans le contexte d’un GN comportent de nombreux risques (exemples : chocs, absence d'alimentation électrique -> batteries, utilisation  des systèmes en extérieur). Ces risques seront pris en compte dès la conception.
*  :heavy_check_mark: **Résilients** : Les dispositifs ***TechnoLarp*** seront conçus pour prendre en compte la possibilité d’une défaillance et offrir deux moyens simples aux organisateurs de pouvoir agir :
   *  :satellite: Au travers d’un back office accessible en wifi via n’importe quel navigateur (défaillance dans le déroulement du scénario, reboot non prévu, …)
   *  :gear: Chaque composant est facilement remplaçable en cas de panne matérielle.
*  :euro: **Économiques** : Par souci de rendre les dispositifs ***TechnoLarp*** accessibles au plus grand nombre d’organisateurs nous resterons vigilants à choisir les composants & matières premières adaptées à notre besoin offrant le meilleur rapport qualité-prix.
*  :open_file_folder: **Open-Source** : L’ensemble des sources des différents logiciels composant la solution ***TechnoLarp***, des documentations et des fichiers de conception (plan de conception du PCB, fichiers permettant l'impression 3D des boitiers ...) seront diffusés sous licence open-source via les repository TechnoLarp. GitHub permettra également à notre communauté de nous remonter les bugs et nous suggérer de nouvelles fonctionalités.
*  :test_tube: **Modulaires** : Possibilité (pour les utilisateurs avancés) de créer de modules d’extension pour étendre les fonctionnalités des dispositifs de base.

# Structure
## L'équipe TechnoLarp
Avatar | Nom  | Rôle
------------ | ------------- | -------------
<img src="https://avatars.githubusercontent.com/u/84352095" width="100" height="100"> | [@marcelinDelcour](https://github.com/marcelinDelcour) | Porteur du projet & Responsable technique
<img src="https://avatars.githubusercontent.com/u/5512824" width="100" height="100"> | [@JosefRDA](https://github.com/JosefRDA) | Développeur & Responsable communication

## Eggrégore ASBL
![](Logo_SF_black_180.png) Le projet ***TechnoLarp*** est hébergé par l'association de Jeu de Role Grandeur Nature Belge Eggrégore ASBL.




