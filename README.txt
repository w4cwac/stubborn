Projet Symfony Stubborn - Guide d'installation



  Cloner le dépôt github dans un répertoire local.

  Utiliser `composer install` dans le terminal afin d'installer les dependances nécessaires au projet.

  Dans le fichier .env changer la base de donner pour `DATABASE_URL="mysql://root:@127.0.0.1:3306/stubborn_test?`.

  Créer la base de donnée avec la commande `symfony console doctrine:database:create`.

  Charger la structure de la BDD avec la commande `symfony console doctrine:migrations:migrate`.

  Migration des fixtures `symfony console doctrine:fixtures:load`.


3/ Lancer le serveur symfony 

  Taper la commande `symfony server:start`


 
 
