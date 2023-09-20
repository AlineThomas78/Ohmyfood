# OhMyFood

### GitHub.io 

https://alinethomas78.github.io/Ohmyfood/

### GitHub :

https://github.com/AlineThomas78/Ohmyfood


## Installation : 

    npm init
    npm install 

#### Installation Sass :

2 méthodes existe : 

* Avec le terminal 

ou

*  Avec L'extension Live Sass Compiler (vsCode)

#### Avec terminal :

    npm install -g sass 
    sass styles.scss styles.css
    sass --watch styles.scss styles.css

#### package.json :

 Dans "scripts" rajouter : 

    "sass": "sass --watch ./sass/main.scss:./public/css/style.css"

### Lancer Sass :

    npm run sass

#### Avec Sass Compiler :

- Installer l'extension visual studio code : Live Sass Compiler 
<br>

- Puis clicquer sur watch Sass en bas de la barre visual studio code


## Introduction :

Troisième projet du parcours "Développeur web" chez OpenClassroom. L'objectif d'intégrer puis de dynamiser une page web avec des animations CSS en utilisant le préprocesseur Sass

## Objectifs :

Développer un site proposant le menu de 4 grands restaurants parisiens
Permettre la réservation en ligne et la composition de menus

## Livrables :


#### Pages à intégrer selon les maquettes :

- Page d'accueil
- Pages de menu (X4)

#### Animation :

#### Boutons

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
<br>

- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, unbouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol au lieu du clic.

#### Page d’accueil

- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,toute proposition est donc la bienvenue tant qu’elle est cohérente avec la chartegraphique du site.

#### Pages de menu

- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
<br>

- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser dela droite vers la gauche. Pour cette première version, l’effet peut apparaître au survolau lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni