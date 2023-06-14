# CRUD-arangoDB

## Étape 1: Télécharger et installer ArangoDB

Rends-toi sur le site officiel d'ArangoDB (https://www.arangodb.com/) et télécharge la version adaptée à Windows.
Lance le programme d'installation téléchargé et suis les instructions pour installer ArangoDB sur ton système.

## Étape 2: Démarrer le serveur ArangoDB

Après l'installation, lance ArangoDB depuis le menu de démarrage de Windows.
Attends que le serveur démarre. Par défaut, il utilisera le port 8529.

## Étape 3: Accéder à l'interface web d'ArangoDB

Ouvre ton navigateur web préféré.
Dans la barre d'adresse, entre l'URL suivante : http://localhost:8529/.
L'interface web d'ArangoDB devrait s'afficher. Connecte-toi avec les identifiants par défaut (nom d'utilisateur : "root", sans mot de passe).

## Étape 4: Créer une base de données

Une fois connecté à l'interface web, clique sur "Database" dans la barre de navigation supérieure.
Clique sur le bouton "Add Database" pour créer une nouvelle base de données.
Donne un nom à ta base de données et clique sur "Save" pour la créer.

## Étape 5: Créer une collection

Dans la barre de navigation supérieure, clique sur "Collections".
Clique sur le bouton "Add Collection" pour créer une nouvelle collection.
Donne un nom à ta collection et sélectionne la base de données dans laquelle tu souhaites la créer. Clique sur "Save" pour créer la collection.

## Étape 6: Créer un CRUD
Maintenant que nous avons une base de données et une collection, nous pouvons créer les opérations CRUD.

Pour créer un document (Create), clique sur le bouton "Documents" dans la barre de navigation supérieure, puis sur "Create Document".

Dans la zone de texte JSON, saisis les données du document que tu souhaites créer et clique sur "Save".

Pour lire un document (Read), utilise la fonctionnalité "Documents" de l'interface web. Tu peux utiliser des filtres pour afficher uniquement les documents qui correspondent à certains critères.

Pour mettre à jour un document (Update), sélectionne le document que tu souhaites modifier dans la vue "Documents". Modifie les valeurs souhaitées et clique sur "Save".

Pour supprimer un document (Delete), sélectionne le document dans la vue "Documents" et clique sur "Delete".
