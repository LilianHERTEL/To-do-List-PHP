# Projet de Todo List en PHP

Projet de to-do list en PHP réalisé en deuxième année à l'IUT d'Informatique de l'Université Clermont-Auvergne (UCA).

### Auteurs
Hector PITEAU
Lilian HERTEL
Groupe 4

### Important :
Dans notre projet, nous utilisons un .htaccess qui nous permet de rediriger toutes les requêtes sur le fichier index.php.

### Fonctionnalités supplémentaires :
Possibilité de créer un compte.
Possibilité de voir, modifier ses informations de compte (pseudo, mot de passe).
Possibilité de supprimer son compte.
Possibilité de se connecter à un compte Admin
Voir les logs de la base de données en mode Admin
Possibilité de passer sa liste privée en publique et inversement.
Possibilité de glisser une todo d’une liste à une autre (drag-and-drop).
Possibilité de changer le titre d’une liste.

### Pseudo-fonctionnalités :
Quand le titre est trop long on peut y accéder avec un tooltip.
On peut visualiser ses listes privées avec un badge en haut de cette dernière.

### Répartition des tâches :

##### Lilian :
* visualisation des listes privées
* passer une liste publique/privée une liste, ajout d’un badge en haut des listes d’un user pour indiquer si liste privée ou publique
* user gateway créée, ensuite modifiée par nous deux
* drag and drop pour les todos d’une liste à l’autre
* factories
* gestion de la connexion à un user (beaucoup modifiée ensuite par nous deux)
* possibilité de se connecter à un compte admin, et la partie admin associée (modèles, gateway logs, triggers dans la base de données, gestion de l’affichage sur la page admin)
* pagination des TodoListes

##### Hector :
* gestion des comptes : créer un compte, voir les infos du compte et les modifier, supprimer son compte
* le front controller 
* gestion des routes avec le front controller
* changement du titre d’une liste
* tooltip pour voir le titre d’une liste
* Le ReturnEnum pour pouvoir gérer les résultats des différents traitements
* création de pages d’erreur (404, etc.) et redirections vers celles-ci
* classe validation (la classe a été ensuite modifiée pour ajouter des fonctions)
 
