# Gestion-de-projet-V2

Sujet B2 Gestion de projet
Planification et ordonnancement des tâches avec utilisation des outils utilisés dans les ateliers
Contexte

Notre entreprise conçoit et fabrique une nouvelle collection de chaussures de sport haut de gamme. Elle souhaite un magasin en ligne, administrable, de sa nouvelle collection pour permettre aux clients de commander et de se faire livrer.

Votre rôle est de planifier ce projet et de coordonner le travail des développeurs. L’équipe qui vous accompagne est composée seulement d’un dev backend et un dev frontend.

Cahier des charges du projet
 Application web accessible uniquement sur authentification.
Deux rôles d'utilisateurs :
Clients. Il peuvent :
Parcourir la collection de chaussures.
Commander des produits.
Voir l'historique de leurs commandes.
Voir leur profil.
Administrateurs. En plus des droits des clients, il peuvent administrer toutes les entités :
Gestion CRUD des clients.
Gestion CRUD des produits.

Product Backlog
Voici toutes les actions nécessaires à la réalisation de notre projet :

X : backend - Initialisation de la BDD (8h).
X : backend - Initialisation du code du projet (3h)
X : frontend - Initialisation du code du projet (3h)
backend - routes API à produire :
Pour les clientsgit
Verbe HTTP
Route HTTP
Action
Temps de réalisation

POST
/api/signin
X : Inscription sur l’app + test
12h

POST
/api/login
X : Connexion + test
8h

GET
/api/logout
X : Déconnexion + TEST
1h

GET
/api/products
X : Retourne liste des produits + TEST
8h

GET
/api/products/:id
X : Retourne un produit + TEST
3h

GET
/api/cart
X : Retourne le panier + TEST
3h

PUT
/api/cart
X : Ajoute un produit au panier + test
5h

PATCH
/api/cart
X : Modifie un produit du panier + TEST
5h

POST
/api/cart
X : Valide le panier + TEST
5h

GET
/api/orders
X : Retourne la liste des commandes + TEST
3h

GET
/api/orders/:id
X : Retourne une commande + TEST
5h

GET
/api/user/:id
X : Retourne le profil d’un utilisateur + TEST
3h

PATCH
/api/user/:id
X : Modifie mon profil utilisateur + test
5h

DELETE
/api/user/:id
X : Supprime mon compte utilisateur + TEST
5h


Pour les admins
Verbe HTTP
Route HTTP
Action
Temps de réalisation

POST
/api/products
X: Ajoute un produit + test
5h

PATCH
/api/products
X : Modifie un produit + test
5h

DELETE
/api/products
X : Supprime un produit + test
3h



frontend - Pages de l’application :

Route
Description
Temps de réalisation

/login
X : Authentification + test
8h

/
X : Barre de menu (+ logout) + test
5h

/
X : Accueil - liste tous les produits + test
5h

/error
X : Page 404 + test
1h

/products/:id
X : Affiche une fiche produit + test
5h

/cart
Affiche le panier + gestion des articles
12h

/orders
x : Affiche la liste des commandes + test
3h

/orders/:id
X : Affiche le contenu d’une commande + test
3h

/profile
X : Affiche mon profil utilisateur + test
5h

/crud/users
X : Page de gestion CRUD des users + test
20h

/crud/products
Page de gestion CRUD des users
20h



Bonus des bonnes pratiques
Ajout de tests sur les routes api (nécessite 3h par route)
Ajout de tests end-to-end (nécessite 5h par page)


Livrables attendus :
Une planification des tâches pour la réalisation du projet
Un dépôt git avec chaque tâche représentée par un commit
Initialiser un dépôt git sur Github
Un membre de votre équipe sera le dev backend, un autre le dev frontend. Chaque dev devra pusher les commits relatifs à son rôle dans l’ordre de votre planification. En lisant le dépôt, l’ordre des commit représente le travail effectué par les dev dans l’ordre où vous l’avez planifié.
Un speach de 8 min devant un jury qui explique votre démarche et présente votre projet.
Chaque membre de l’équipe devra parler un minimum
Vous serez évalué sur :
Savoir-être : implication et travail d'équipe
Savoir-faire :
respect du cahier des charges
aboutissement du projet présenté.
Bon ordonnancement
Bonne utilisation de git
Pitch : expression orale , distribution de la parole dans le groupe, respect du timing, pertinence du pitch pour la présentation du projet et sa compréhension.
Explication des éventuels problèmes, fonctionnalités manquantes, améliorations souhaitées.
