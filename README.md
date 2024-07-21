#Notion de lancement local
Attention le code source de l'application contient beaucoup de mauvaise pratique et n'est pas du tout sécurisé.
##Prérequis
Serveur web (Apache, Nginx, etc.)
PHP 7.4 ou supérieur
Serveur de base de données MySQL



##Étapes 
1. Déplacer le code source vers votre serveur web local
2. Aller créer une nouvelle base de données nommé « gbs_appli_frais »
3. Copier coller le script « script.sql » pour importer les tables nécessaire 
4. Modifier les identifiants de connexion (« user » ou « mdp ») au besoin dans le ficher « class.pdogsb.php » dans le dossier « include » 
5. Lancer le serveur web
6. Vérifier  votre navigateur web à l'adresse « http://localhost ». L'application devrai fonctionner

###Les identifiants
Pour un visiteur sont « ad » comme Login et « ad » comme Mot de passe
Pour un comptable sont « bp » comme Login et «bp» comme Mot de passe
