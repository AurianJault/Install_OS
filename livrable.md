---
title: Dossier d'étude et de choix des solutions
---

| Besoin                                                                             | Nombre d'outils différents demandés | Logiciels proposés |
| ---------------------------------------------------------------------------------- | :----------------------------------:| -------------------|
| Avoir des Gestionnaires de bureau/fenêtre (dont un qui vous plaise)                | 4                                   |xfce4,gnome,i3,fluxbox|
| Avoir deux utilisateurs: vous et "stagiaire"                                       |                                     |Fais|
| Compiler un programme C                                                            | 2                                   |Gcc, Borland C++Compiler|
| Regarder les pages de man de la libC                                               | 2                                   |`man libc`, https://man.developpez.com/man7/libc/|
| Lancer un `make`                                                                   |                                     |Fais |
| Éditer du code source                                                              | 4                                   |Visual studio code, Atom, Sublimetext,notepad++ |
| Déboguer du code                                                                   | 2                                   |GDB,ElectricFence |
| Naviguer sur le Web                                                                | 2                                   |Firefox,chromium |
| Éditer une image matricielle (png...)                                              | 2                                   |Gimp,Krita |
| Éditer une image vectorielle (svg)                                                 | 1                                   |inkscape |
| (Dé)Compresser les formats `targz` et `7z` et `rar`                                | 1                                   |`tar`,7z,RAR  |


### Gestion des paquets

* Installer un logiciel:  `sudo apt-get install Nom_du_paquet`.
* Désinstaller un logiciel : `sudo apt-get remove Nom_du_paquet --purge`.
* Faire une recherche sur les paquets disponible : `apt-cache search KEYWORD` ou `aptitude`-> Paquets non installés.
* Faire une mise à jour : `apt-upgrade`
* Lister les fichiers installés par un paquets : `dpkg -L Nom_Du_Paquet.` ou `apt-file list Nom_du_paquet`
* Rechercher quel paquet contient un fichier donné : `apt-file search Nom_du_Fichier` ou `dpkg -S Nom_du_Fichier`
            * si le paquet n'est pas installé. : https://www.debian.org/distrib/packages ou `apt-get install Nom_Du_Paquet -s`
### Réseau
* Pouvoir se connecter sur une autre machine avec `ssh`: `ssh [identfiant]@[ip]` (ex: ssh aujault@192.168.127.34)
* Permettre à une autre machine de se connecter sur la vôtre :
* Installer un serveur web capable de lire vos pages perso (`userdir`) :

### Sauvegardes
* Faire une archive d'un répertoire (et de ses sous répertoires) : `tar -czvf monArchive.tar.gz répertoire`
* Copier l'archive sur une clé USB : 
* Copier l'archive via `scp` : 

### Services 
* Savoir démarrer/stopper un service : `services Nom_du_servie STATUT`
* Savoir en vérifier l'état : `systemctl status --full -n 1000`
* Savoir afficher les messages d'erreur : `journalctl`

### Divers

* restreindre les droits de "stagiaire" : useradd -m stagiaire




