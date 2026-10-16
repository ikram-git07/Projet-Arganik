Arganik

Site web de 5 pages pour Arganik, une coopérative féminine qui produit de l'huile d'argan, de l'amlou, du miel et des savons artisanaux (région du Souss-Massa).

Projet fait en équipe (5 personnes) en 5 jours, du 12/10/2026 au 16/10/2026, dans le cadre de la formation Développeur Web et Web Mobile.

Liens
Site en ligne : [lien]
Planification (Trello / GitHub Projects) : [lien]
Présentation : [lien]
Maquette Figma : [lien]
Le projet

Le client voulait un site pour vendre ses produits en direct et montrer d'où vient chaque flacon d'huile. On devait intégrer la maquette Figma (fournie seulement en desktop) et faire nous-mêmes la version mobile.

Les pages
Accueil (index.html) : hero, chiffres clés, produits phares, impact, étapes de fabrication, témoignages
Nos produits (Nos-produits.html) : catégories, filtres, 8 cartes produits, pagination
Fiche produit (Fiche_produit.html) : galerie, achat, passeport terroir, avis, produits similaires
Traçabilité (Traçabilité.html) : vérification d'un lot, 6 étapes de fabrication, coopératrices, certifications
Contact (contactez-nous.html) : formulaire, coordonnées, FAQ

Le header et le footer sont les mêmes sur les 5 pages.

Technologies utilisées
HTML5 (balises sémantiques : header, nav, main, section, article, footer)
CSS3 avec Flexbox (et un peu de Grid)
Responsive en mobile-first (media queries)
Git et GitHub (Git Flow)
Trello pour répartir les tâches
Font Awesome pour les icônes, Google Fonts pour les polices

Pas de JavaScript, le cahier des charges ne le demandait pas.

Répartition du travail
[Nom] : page [page] + [header ou footer]
[Nom] : page [page] + [header ou footer]
[Nom] : page [page] + [header ou footer]
[Nom] : page [page] + [header ou footer]
[Nom] : page [page] + [header ou footer]
Comment on a travaillé avec Git
Une branche main (version finale) et une branche develop (là où on regroupe le travail)
Chacun créait sa propre branche feature/... à partir de develop
Quand une partie était finie, on faisait une Pull Request vers develop et un autre membre la relisait avant le merge
À la fin, une Pull Request de develop vers main
Difficultés
Les conflits Git quand deux personnes modifiaient le même fichier (par exemple le header)
Garder le même header et footer sur toutes les pages
Le menu : le lien de la page active ne gardait pas sa couleur, seulement au clic (:focus). On a ajouté une classe active
Les noms de fichiers avec accents et majuscules (Traçabilité.html) qui peuvent poser problème une fois le site en ligne
Adapter la maquette en mobile, surtout les sections qui alternent en desktop et qui s'empilent en mobile
Ce qu'on a appris
Utiliser les balises sémantiques HTML5 au lieu de mettre des div partout
Faire des mises en page avec Flexbox
Travailler en mobile-first et faire un site responsive
Utiliser Git Flow : branches, Pull Requests, résoudre des conflits
Travailler en équipe et répartir les tâches avec Trello
Valider son code avec le validateur W3C
Expliquer son code à l'oral
Captures d'écran

Desktop : [captures]

Mobile : [captures]

Lancer le projet
git clone [lien du dépôt]
