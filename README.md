# Tp-Spring-boot

### I Introduction :

  Spring Boot est un projet de Spring Framework qui vise à simplifier le processus de configuration et de déploiement des applications basées sur Spring. Il fournit un ensemble d'outils et de conventions permettant de démarrer rapidement des applications basées sur Spring avec un minimum de configuration manuelle. Spring Boot facilite également le développement en offrant des fonctionnalités telles que l'auto-configuration, qui permet à l'application de configurer automatiquement des composants en fonction des dépendances ajoutées.
 
### II Technologies Utilisées :


Java: Java est un langage de programmation polyvalent et orienté objet largement utilisé pour développer diverses applications allant des applications de bureau aux applications Web en passant par les applications mobiles. Il est apprécié pour sa portabilité, sa robustesse, sa sécurité et sa facilité d'utilisation.

MySQL : MySQL est un système de gestion de base de données relationnelle open source populaire. Il est largement utilisé pour stocker, organiser et gérer de grandes quantités de données de manière efficace et fiable. Il offre une grande stabilité, une bonne performance et une large gamme de fonctionnalités, en faisant un choix populaire pour de nombreux types d'applications.

Hibernate : Hibernate est un framework de mapping objet-relationnel (ORM) en Java qui simplifie considérablement la communication entre une application Java et une base de données relationnelle. Il permet aux développeurs de travailler avec des objets Java au lieu de requêtes SQL directes, ce qui rend le processus de persistance des données plus simple et plus flexible.

  Spring Boot : Spring Boot  est un projet de Spring Framework qui vise à simplifier le processus de configuration et de déploiement des applications basées sur Spring. Il fournit un ensemble d'outils et de conventions permettant de démarrer rapidement des applications basées sur Spring avec un minimum de configuration manuelle. Spring Boot facilite également le développement en offrant des fonctionnalités telles que l'auto-configuration, qui permet à l'application de configurer automatiquement des composants en fonction des dépendances ajoutées.

JPA : JPA (Java Persistence API) est une spécification Java qui décrit une interface de programmation pour gérer la persistance des données dans des applications Java. Elle fournit un moyen standard pour les développeurs d'écrire des applications Java qui peuvent gérer des données relationnelles de manière persistante. JPA simplifie l'interaction avec les bases de données relationnelles en fournissant une interface de programmation orientée objet pour effectuer des opérations de base de données. 

Swagger :Swagger est un ensemble d'outils open source qui aide les développeurs à concevoir, créer, documenter et consommer des services web RESTful. Il fournit des outils pour générer automatiquement la documentation de l'API, ce qui facilite la compréhension et l'utilisation des services web par d'autres développeurs. Swagger permet de décrire la structure et les fonctionnalités des API REST de manière claire et concise.

 ### III Fonctionnalités du projet :

 Opérations CRUD (Create , Delete ,update) pour etudiant:

   1_L'utilisateur dispose de plusieurs fonctionnalités pour gérer les etudiants dans le système. Tout d'abord, il peut ajouter une nouvelle etudiant en spécifiant des détails tels que firstname , lastname , telephone et l'utilisateur peut supprimer définitivement une etudiant spécifique, ce qui entraînera la suppression complète et permanente de toutes les données associées à cette machine dans le système , et en fin il peut modifié les deférentes champs de l'étudiant.

  2_Opérations CRUD (Create , Delete ,update) pour role:

   L'utilisateur dispose de plusieurs fonctionnalités pour gérer les roles dans le système. Tout d'abord, il peut ajouter un nouvelle role en spécifiant des détails tels que le nom de role  et l'utilisateur peut supprimer définitivement un role spécifique, ce qui entraînera la suppression complète et permanente de toutes les données associées à ce role dans le système , et en fin il peut modifié les deférentes champs de role.

  3_Opérations CRUD (Create , Delete ,update) pour filiere: 

 L'utilisateur dispose de plusieurs fonctionnalités pour gérer les filieres dans le système. Tout d'abord, il peut ajouter une nouvelle filiere en spécifiant des détails tels que code , nom  et l'utilisateur peut supprimer définitivement une filiere spécifique, ce qui entraînera la suppression complète et permanente de toutes les données associées à cette machine dans le système,et en fin il peut modifié les deférentes champs de filiére.

   4_D'autre fonctionalité:
  
Affichez les etudiants d'un filiere.

Afiches les roles d'un étudiants.

Trouvé un étudiant ,filiére ,role by id.

Affichez tous les etudiants ,filiéres ,roles.

###  Base de donnes et Digrammme de classe :

1  Digramme de classe :



2 Chéma base de donnés :

###  Etudiant :

###  1_Afficher :

###  2_Ajouter :

###  3-Modifié :

###  4_Supprimé :

###  Filiere :

###  1_Afficher :

###  2_Ajouter :

###  3-Modifié :

###  4_Supprimé :

###  5_Les etudiants d' un filiere :

###  Role :

###  1_Afficher :

###  2_Ajouter :

###  3-Modifié :

###  4_Supprimé :

###  comment exécuter le projet 

Etape1:

utiliser la commande suivante si Git est installé : git clone <lien-du-projet>.
Sinon, vous pouvez télécharger l'archive du projet et extraire son contenu sur votre ordinateur.
Ouvrez le projet  dans votre environnement de développement.

Etape2:

Creé une base de donnes SCHOOL 11 .

Exécutez la projet.

Etape3:

Une fois que l'application  est lancée, vous devriez tapez localhost:8088/swagger-ui/index.htm  et voir une page web de swagger conviviale avec des fonctionnalités pour manipulez les défferents champs de filiere , students et role .
Utilisez les fonctionnalités appropriées pour gérer les entites  en fonction de vos besoins.

###  Conclusion :

 ce projet de gestion d'étudiant , filiére, role , développé en utilisant Hibernate, Java MySQL ,spring-boot , vise à faciliter la procédure de réservation des ressources. Son page web swagger conviviale, pour améliorer l'efficacité des opérations.

