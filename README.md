# BlogSymfony

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
