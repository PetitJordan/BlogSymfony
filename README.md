# BlogSymfony

Blog dans lequel on peut visualiser plusieurs ou un article, en créer ou en modifier un. Ces articles ont été générées grâce à la librairie faker dans une fixture appropriée.
Fonctionnalités de connexion et deconnexion. On peut également créer un commentaire sur l'article de son choix si on est connecté à l'application. Toutes les données sont stockées en BDD MySQL.


## Installer les modules
```
composer require symfony/webpack-encore-bundle
composer require fzaninotto/faker
composer require api
composer require admin
composer require lexik/jwt-authentication-bundle 
composer require server --dev
```

## URL
```
Une fois les commandes exécutées et un :
symfony server:start 

le projet devrait fonctionner et être accessible à l'adresse : 
127.0.0.1:8000
```

## URL de nos fonctionnalités
```
# Article 
127.0.0.1:8000/blog
127.0.0.1:8000/blog/{id}
127.0.0.1:8000/blog/new
127.0.0.1:8000/blog/{id}/edit

# Login
127.0.0.1:8000/inscription
127.0.0.1:8000/connexion
127.0.0.1:8000/deconnexion

```
