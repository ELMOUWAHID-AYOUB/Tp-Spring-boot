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

![Diagramme_de_classe](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/ff176204-46ab-4d4a-b5a3-d22c8d00dabb)

2 Chéma base de donnés :

![base_de_donnes](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/e5667175-987e-4271-b44d-1ca580b47b4b)

###  Etudiant :

![page](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/9081cab8-3715-47e4-93f9-5feb18b29a36)

###  1_Afficher :

![get](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/4a215f44-65c3-437c-a05d-e0d4f99c36cf)

![get_1](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/37491db9-20b8-4a1d-a9d0-89f8ffb1269b)

###  2_Ajouter :

![POST](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/655bf8e9-af75-4524-bb27-83c0477a81b4)

![POST_1](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/a4db24aa-c9c6-464b-b733-557ba3a4e5ab)


###  3_Supprimé :

![delete-filiere-by-student-Id_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/f7505129-99fa-4f67-b843-b88a3550ed09)

![delete-filiere-by-student-Id_2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/e17e580e-70dd-4d07-8a33-b4e2e4ab9067)

###  4-Get-filiere-by-student-Id:

![get-filiere-by-student-Id_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/363f0c33-cb83-4ec4-8dbf-ec08f725b093)

![get-filiere-by-student-Id_2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/d57495b0-2359-4e81-a7a8-398c0713a2a3)

###  5_Get-role-by-student-Id:

![get-role-by-student-Id_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/840fbf6c-3365-4b46-bcdb-52e54e72a373)

![get-role-by-student-Id-2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/cd71abc0-4102-42d6-bc16-a9a768bf3438)

###  6_Get-etudiantbyid:

![get_etudiantbyid_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/7652e7b8-1fa4-46ce-a4fc-47b52604c58b)

![get_etudiantbyid_2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/5fed9045-3f95-46c4-b66b-66113dd34c49)

###  Filiere :

![Capture d’écran 2023-11-05 001501](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/d7cc1dbc-8f10-4bc6-90c2-a3c58d2202eb)



###  1_Afficher :

![GET](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/48198413-a3af-40ed-849c-e977eb33bd4f)

![GET_1](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/34fa7bd6-fab1-480e-ae37-f6895811b19a)

![get_filiere_2](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/ba7922f5-3285-4997-a10f-eacec53fe3e4)

![get_filiere_1](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/553c1615-935b-4eee-a48d-609ee43c2722)


###  2_Ajouter :

![POST](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/83999317-727a-4e2f-962c-ad388ec07f78)

![POST_1](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/1dc39971-c333-4d2c-8a20-0eca1874318a)

![post_filiere_2](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/c588c6ba-84af-41f4-8078-185a8d5bb74e)

![post_filiere_1](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/8af76ead-a164-4d09-b8b5-b5a6d36e08de)


###  3-Modifié :


![put_filiere_1](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/82851c3d-1c71-44fb-9568-b96e8c02bbf1)

![put_filiere_2](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/4fc5ea91-1d1e-4324-80c0-a8cf9ea95b4c)

![patch_filiere_1](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/f9d88750-35bf-4ded-9c20-24168fe2b0e0)

![patch_filiere_2](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/acd7f973-a1c5-4ac7-8db3-2af0e33d1fe1)

###  4_Supprimé :

![DELET_filiere_1](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/b0fe82ba-ca24-4460-ad38-29ca245b15ae)

![DELET_filiere_2](https://github.com/ELMOUWAHID-AYOUB/JAVA_WEB_JSP/assets/130571009/41984bc6-a35c-44a1-a392-cc6087aba742)

###  5_Get-filierebyid:

![get_filiere_byid_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/470b868f-e108-4e6a-9670-4d72abcfe389)


###  Role :
![Capture d’écran 2023-11-05 001434](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/f9cc7e63-0d85-4044-af3e-69992a1362f6)

###  1_Afficher :

![get](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/4194d274-8bfe-4aff-a9dd-63afdb4351c8)



![get_role_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/b1a1bbd2-fedf-40d2-bf76-c9b07d8c6bab)


![get_role_2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/902391c6-e948-49a2-8635-6e6f5255ed4d)

###  2_Ajouter :



![POST](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/001307c4-01fd-4300-9dce-02bc5f861673)

![POST_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/7706ae2a-15b5-4cc5-9c78-7f041ff28ac0)


![post_etudiant_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/ae3e0a4b-91f8-4140-b826-ebf2ff3d3cb1)

![post_etudiant_2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/86ed981d-78a7-4828-8d81-af973efea749)


###  3-Modifié :


![put_role_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/407b0a88-64b7-4660-b8a9-8e6c6cd12958)

![put_role_2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/b4f8526f-8965-45ea-9aba-8d68169ca9b5)


![patch_role_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/d2278aa7-4a33-4834-8690-981fccbb1c44)

![patch_role_2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/1ac89179-24ca-407f-84cf-d300c183672f)





###  4_Supprimé :


![delete_role_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/86e20754-ba90-4ea0-8770-1beccaa2bf71)

![delete_role_2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/f72d91a7-8f3f-4413-8c32-c0e51e1b309f)



###  5_Get_rolebyid :


![get_rolebuid_1](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/6e6378ef-924a-4bd5-94e8-9740b0c828b7)

![get_rolebyid_2](https://github.com/ELMOUWAHID-AYOUB/Tp-Spring-boot/assets/130571009/4d465153-34b9-4c3c-8bf4-07f41ad2d089)


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

