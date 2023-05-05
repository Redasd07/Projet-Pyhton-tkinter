
# Application de gestion de stock

Cette application a été développée en Python en utilisant le module SQLite pour la gestion de la base de données et tkinter pour l'interface graphique.

## Réalisé par

- [@NourBeny](https://www.github.com/NourBeny)
- [@Redasd07](https://www.github.com/Redasd07)


## Installation

* Clonez ce dépôt dans votre dossier de projet.
* Assurez-vous que Python est installé sur votre machine.


    
## Configuration
Pour configurer la base de données: 
* ouvrez le fichier create_db.py et modifiez les informations de connexion à votre base de données.
* Exécutez le script pour créer la base de données en exécutant la commande suivante : python create_db.py.
## Utilisation
Pour lancer l'application, exécutez le fichier login.py.
* Connectez-vous en utilisant votre nom d'utilisateur et votre mot de passe ou créez un nouveau compte en cliquant sur "S'inscrire".
* Utilisez les différents menus pour ajouter, afficher, modifier et supprimer des produits, des catégories, des employés et des fournisseurs.
* Cliquez sur "Déconnexion" pour vous déconnecter de l'application.
## Fonctionnalité
L'application offre des fonctionnalités pour gérer vos produits, catégories, employés et fournisseurs.
* **Authentification et autorisation :** l'application dispose d'un système de login et sign up pour gérer les accès aux différentes fonctionnalités de l'application. Les utilisateurs doivent s'authentifier pour accéder à leur compte.
![image](https://drive.google.com/uc?export=view&id=16c9XZTpcWNOFJ3QTci8iDXiRdu1oeBCt)

![image](https://drive.google.com/uc?export=view&id=10b7_DYsz32OsvMl3Lrutuxi2wZF1oBNy)
* **Interface utilisateur :** l'application dispose d'une interface utilisateur conviviale qui permet aux utilisateurs de naviguer facilement dans l'application. L'interface utilisateur est implémentée dans le fichier dashboard.py.
![image](https://drive.google.com/uc?export=view&id=1mPVMbPeIuw8MkbpFXlXUyR0JE4R4FEAj)

* **Gestion des employés :** le fichier employees.py permet aux utilisateurs d'ajouter, afficher, modifier, supprimer, effacer et rechercher des employés dans la base de données.
![image](https://drive.google.com/uc?export=view&id=10mog2tqaQ1He6YbbKpK65GNqxGsgWRGP)

* **Gestion des fournisseurs :** le fichier fournisseurs.py permet aux utilisateurs d'ajouter, afficher, modifier, supprimer, effacer et rechercher des fournisseurs dans la base de données.
![image](https://drive.google.com/uc?export=view&id=1zmt07zLLNB02XuBqrrFCgn3sKZGG_A9h)

* **Gestion des catégories :** le fichier categorie.py permet aux utilisateurs d'ajouter, afficher et supprimer des catégories dans la base de données.
![image](https://drive.google.com/uc?export=view&id=1tN_TQw8erKqgCYDee0IewCvE6eprTnUs)

* **Gestion des produits :** le fichier produit.py permet aux utilisateurs d'ajouter, supprimer, afficher, modifier, effacer et rechercher des produits dans la base de données.
![image](https://drive.google.com/uc?export=view&id=17PmMjcpApdEZBYzoQECDxIB6x1bcsO2R)

* **Déconnexion :** l'application dispose d'une fonctionnalité de déconnexion qui permet aux utilisateurs de se déconnecter de leur compte.
## Fichiers Python
* login.py - Contient la classe Login pour l'authentification des utilisateurs.
* signup.py - Contient la classe Signup pour l'inscription de nouveaux utilisateurs.
* dashboard.py - Contient la classe Interface pour l'interface principale de l'application.
* produit.py - Contient les fonctions pour ajouter, supprimer, afficher, modifier, effacer et rechercher des produits.
* categorie.py - Contient les fonctions pour ajouter, afficher et supprimer des catégories de produits.
* create_db.py - Contient le script pour créer la base de données.
* employee.py - Contient les fonctions pour ajouter, afficher, modifier, supprimer, effacer et rechercher des employés.
* fournisseurs.py - Contient les fonctions pour ajouter, afficher, modifier, supprimer, effacer et rechercher des fournisseurs.
## FAQ

####  De quoi ai-je besoin pour exécuter cette application?

 Pour exécuter cette application, vous aurez besoin d'un ordinateur exécutant le système d'exploitation Windows, Linux ou macOS, ainsi que les packages Python tkinter, sqlite et Pillow installés sur votre système.

#### Comment puis-je installer les packages Python requis pour exécuter cette application?

Vous pouvez installer les packages requis en utilisant l'outil de gestion de packages Python appelé pip. 

Pour installer tkinter, sqlite et Pillow, ouvrez une invite de commande et exécutez les commandes suivantes:

    pip install tkinter
    pip install sqlite
    pip install Pillow



## Feedback

Si vous avez des commentaires, veuillez nous contacter àgeststock@gmail.com

