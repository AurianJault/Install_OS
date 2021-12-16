# Notice d'installation

## Table des matières
* Téléchargement de l'iso debian
* Création de la clé bootable
* Démarrer l'Installation
* Installation de debian
* Installation des différents paquets nécessaires

## Téléchargement de l'iso débian
* Pour une installation à partir d'une clé USB, il faut que cette dernière soit Formatée (vide) et une capacité minimale de 2go.
* Télécharger l'iso débian à cette adresse : https://www.debian.org/download

## Création de la clé bootable
# Nous allons créer la clé bootable avec le fichier .iso télecharger précédemment.
*  Installer un programme de création de clé USB de démarrage (exemple : UNetbootin, supporté sur Windows, Mac OS X et Linux)
* Une fois lancer, sélectionner __Débian__ pour la distribution et __Stable_NetInstall_x64__ pour la version
* Chosisissez ensuite, votre fichier .iso télécharger plutôt et sélectionnez dans le menu déroulant l'extantion __ISO__
* Sélectionner en bas le nom de votre clé USB, puis clioquez sur __ok__ en bas de la fenêtre.

## Démarrer l'Installation
* Une fois arriver à cette étape redémarrer votre ordinateur, Si vous n'arrivez pas à accéder au menu de démarrage ou au BIOS, il faut redémarrer en maintenant enfoncée une certaine touche ( f1, f2, ou f10). Si vous ces touches ne fonctionnent pas, allez alors sur Internet avec les références de votre configuration et voyez quelles touches permettent d'entrer dans ces menus.
*  Sélectionner l'onglet boot Menu, votre clé USB sera identifiable par le nom de sa marque, sélectionner et pressez le touche __enter__
# Le début de l'installation vas alors commencer !

## Installation de debian
* à vous de choisir l'installation graphique ou non ( il n'y a aucun changement pour le suite de l'installation, mais vous installe le gestionnaire de fenêtre __GNOME__ si vous choisissez la première option )
* Utiliser les flèches de votre clavier afin de sélectionner la langue de votre choix 
* pareil pour la géolocalisation et la disposition du clavier
* Entrez le nom le nom de la machine. C'est le nom qui apparaît lors des accès réseaux à ce PC.
* De-même pour le groupe de travail ou domaine
# paramètrage des utilisateurs
*  Entrez et valider le mot de passe pour l'utilisateur root* (Le root : c'est l'utilisateur administrateur qui peut modifier le système)
* puis on créé l'utilisateur standard avec le nom, choisir le nom que vous désirez et indiquer par la suite le mot de passe de votre choix
# Partitionnement du disque
* Sélectionner comme type de partition __Assisté - le plus grand espace disponible__
* Sélectionner le disque de votre choix où installer Linux
* Choisisser si vous voulez tout dans une seule partition ou séparer le /home. ( __tout dans une seule partition__ dans notre cas )
# L'installation du système vas alors commencer
* Une fois l'installation terminé, choisissez __non__ a la question : "faut-il analyser un autre CD ou DVD ?"
* Choisissez l'emplacement géographique (france)
* Ensuite on choisit le miroir Debian, c'est le serveur de dépôt d'où les paquets seront téléchargés (Vous pouvez laisser celui par défaut)
* Indiquer si la connexion doit s'effectuer à travers un proxy. (Dans notre cas entrez : https://[[utilisateur][:mot-de-passe]@]193.49.118.36:8080)
# La configuration de l'outil de gestion des paquets vas alors ce faire.
* choisissez si vous voulez participer à l'étude sur l'utilisation des paquets ( ceci n'as aucun impacte sur l'installation )
* Enfin, sélectionnez les différent environnement de bureau souhait ( GNOME et XFCE ), cliquez sur __continuer__ puis sélectionnez le gestionaire graphique de session par défault
# Votre ordinateur vas alors redémarrer et vous pourrez sélectionner le boot Debian, puis vous connecter à votre session
