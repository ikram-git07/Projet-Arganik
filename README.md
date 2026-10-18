Arganik

Site web d'une coopérative féminine d'huile d'argan de la vallée du Souss (Maroc). Projet réalisé en équipe en HTML et CSS, à partir de maquettes PDF qu'il fallait reproduire le plus fidèlement possible.

Pages
Accueil (Accueil.html) : présentation de la coopérative, chiffres clés, produits phares, impact social, avis clients.
Nos produits (nos-produits.html) : catalogue des produits.
Fiche produit (fiche-produit.html) : détail d'un produit, choix de la contenance, quantité, ajout au panier.
Traçabilité (Traçabilité.html) : recherche d'un lot, 6 étapes de fabrication, coopératrices, certifications.
Contact (contact.html) : coordonnées et formulaire de contact.

Toutes les pages partagent le même en-tête et le même pied de page.

Technologies

HTML5, CSS3 (Flexbox, Grid, media queries), Google Fonts (Playfair Display, Inter, Lato, Poppins) et Font Awesome pour les icônes.

Structure
Accueil.html
nos-produits.html
fiche-produit.html
Traçabilité.html
contact.html
style.css
Traçabilité.css
img/
icons/
Lancer le projet

Ouvrir le dossier dans VS Code et lancer un fichier HTML avec l'extension Live Server. Les dossiers img/ et icons/ doivent rester à côté des fichiers HTML. Une connexion Internet est nécessaire pour les polices et les icônes.

Ce que nous avons appris
Structurer une page avec les balises sémantiques (header, nav, main, section, footer).
Mettre en page avec Flexbox et Grid.
Positionner des éléments sur une image (badges, numéros) avec position: relative et absolute.
Rendre un site responsive avec les media queries, clamp() et object-fit.
Créer un menu burger sans JavaScript.
Comprendre pourquoi une règle CSS en écrase une autre (spécificité et ordre).
Reproduire une maquette en comparant le rendu avec le PDF.
Garder un CSS lisible et partager un style commun entre plusieurs pages.
Problèmes rencontrés
Une police du CSS n'était pas chargée dans le HTML. Solution : charger la même police dans le <link>.
Une faute dans un nom de classe cassait le style d'une image.
La propriété background écrasait background-image sur le bandeau d'accueil.
Équipe

Salma Aboueljad: Accueil
zakaria : Nos produits
Said Raya: Fiche produit
Badreddine ezzatami: Traçabilité
Arbaoui ikram: Contact
