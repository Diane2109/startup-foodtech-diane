# README de Startup FoodTech

## Qu'est-ce que c'est ?

Cette app Ruby on Rails est la landing page d'un restaurant gastronomique de kebab. Elle a été conçue par Diane.

L'intérêt de l'app est l'utilisation de Javascript et plus particulièrement de JQuery. Il y a un caroussel d'images ainsi qu'une tab qui permet d'afficher sur une même page la présentation, le menu et l'itinéraire du restaurant.

Bootstrap n'a pas été utilisé dans le but de réécrire soi-même en Javascript les fonctions permettant de coder le caroussel et le tab.

## Comment démarrer ?

Il suffit de cliquer sur ce lien pour voir l'app en production : https://startup-foodtech-diane.herokuapp.com/.

Sinon, il suffit de clone ou download le dossier et de run bundle install, une fois à l'intérieur.

Les versions de Ruby et Rails doivent être respectivement 2.5.1 et 5.2.1.

Les files html ont été divisés en sous-parties : une partie appelée _carroussel.html.erb_ et l'autre _tab.html.erb_. Elles sont appelées ensuite dans index grâce à render.
