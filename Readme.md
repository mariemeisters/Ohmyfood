# Projet 3 - Openclassroom - Ohmyfood

Dynamiser une page WEB avec des animations CSS.

## Compétences évaluées
<ul>
  <li>Mettre en œuvre des effets CSS graphiques avancés</li>
  <li>Assurer la cohérence graphique d'un site web</li>
  <li>Mettre en place son environnement Front-End</li>
  <li>Mettre en place une structure de navigation pour un site web</li>
  <li>Utiliser un système de gestion de versions pour le suivi du projet et son hébergement</li>
</ul>

## Identité 

Ohmyfood! est une entreprise de commande de repas en ligne. Notre concept permet aux
utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les
restaurants car leur menu est préparé à l’avance. Plus de perte de temps à consulter la carte
!
### Cible

Classes moyennes et supérieures, connectées et souvent pressées, souhaitant déguster des
produits de qualité.

## Contenu des pages

### Page d'accueil
<ul>
  <li>Affichage de la localisation des restaurants. À terme il sera possible de choisir sa
localisation pour trouver des restaurants proches d’un certain lieu.</li>
  <li>Une courte présentation de l’entreprise.</li>
  <li>Une section contenant les 4 menus sous forme cartes. Au clic sur la carte,
l’utilisateur est redirigé vers la page du menu.</li>
</ul>

### Pages de menu
<ul>
  <li>4 pages contenant chacune le menu d’un restaurant.</li>
</ul>

### Footer
<ul>
  <li>Le footer est identique sur toutes les pages.</li>
  <li>Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.</li>
</ul>

### Header
<ul>
  <li>Le header est présent sur toutes les pages.</li>
  <li>Sur la page d’accueil, il contient le logo du site.</li>
  <li>Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.</li>
</ul>

## Effets graphiques et animations

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser
les animations ou transitions CSS, pas de JavaScript ni de librairie.

### Boutons
<ul>
  <li>Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.</li>
  <li>L’ombre portée devra également être plus visible.</li>
  <li>Bouton "J'aime" en forme de coeur, se remplie progressivement au clic, peut ce remplir au survol sous la version desktop. Page d'acceuil</li>
</ul>


### Page d’accueil

<ul>
  <li>Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur
cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à
3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
graphique du site.</li>
</ul>

### Pages de menu

<ul>
  <li>À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
“Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.</li>
  <li>Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension. Un exemple de l’effet attendu est fourni.</li>
</ul>

### Polices

<ul>
  <li>Logo et titres: Shrikhand</li>
  <li>Texte: Roboto</li>
</ul>

### Couleurs

<ul>
  <li>Primaire: #9356DC (violet)</li>
  <li>Secondaire: #FF79DA (rose)</li>
  <li>Tertiaire: #99E2D0 (vert)</li>
</ul>

### Compatibilités
La cible étant les personnes connectées et pressées, le site sera développé en utilisant
l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées.</br>
Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires,
leur mise en page est libre.
<ul>
<li>L’ensemble du site devra être responsive sur mobile, tablette et desktop.</li>
<li>Les pages devront passer la validation W3C en HTML et CSS sans erreur.</li>
<li>Le site doit être parfaitement compatible avec les dernières versions desktop de
Chrome et Firefox.</li>
</ul>