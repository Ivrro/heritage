# Héritage

Héritage est un site e-commerce réalisé dans le cadre du projet de fin d'année de 5 éléves de la classe MPWD 2 d'Efficom.

## Installation

Si vous lisez ceci c'est que vous avez réussit à cloner le projet, GG.

Une fois celà fait, il va vous falloir récupérer dans le dossier **wp-content/dump** la dernière version de la BDD (essayez de dater vos dumps).

Maintenant que vous avez récupéré la BDD, il faut lier votre code à cette dernière, pour celà vous devez modifier le fichier **wp-config-sample.php** et modifier les lignes suivantes avec vos propres infos :


```
## wp-config-sample.php

// ** MySQL settings - You can get this info from your web host ** //
/** The name of the database for WordPress */
define( 'DB_NAME', 'database_name_here' );

/** MySQL database username */
define( 'DB_USER', 'username_here' );

/** MySQL database password */
define( 'DB_PASSWORD', 'password_here' );

/** MySQL hostname */
define( 'DB_HOST', 'localhost' );

/** Database Charset to use in creating database tables. */
define( 'DB_CHARSET', 'utf8' );

/** The Database Collate type. Don't change this if in doubt. */
define( 'DB_COLLATE', '' );
```

Quand c'est fait et là ATTENTION : **renomez le fichier en wp-config.php**.


## Connexion

Pour se connecter :

Login: admin  
Mdp: admin_mpwd

Pensez à vous créer un utilisateur afin qu'on ai tous le notre.


## Pousser des modifications (à venir)