---
layout: post
title: Installation server / client FTP _ Utilisation d'openssh accès serveur par clé 
---

#A faire#
- Noter toutes vos manipulations et documenter chaque commande utilisé dans un document texte que vous déposerez sur e-lyco au format pdf 
- Aucune impression écran permise dans le document
- format du document 
        Nom_prenom_TP_ubuntu.pdf 

#Objectifs:#
- Installation d'un poste de travail linux 
- Installation d'un serveur FTP sur le porte de travail linux 
- Installation d'une librarie 

#Prérequis:#
Utilisation de virtualbox pour l'installation du système d'exploitation Ubuntu ( poste de travail linux )
Utilisation de putty pour communiquer en ssh avec le poste de travail linux 

##Ubuntu##

Préparez une machine virtuelle permettant d'installer une distribution ubuntu avec un environement graphique
Configurer virtualbox pour pouvoir communiquer avec votre poste de travail linux depuis votre machine hôte windows
[Ubuntu 16.04](https://www.ubuntu.com/download/desktop)
[Ubuntu fr](https://doc.ubuntu-fr.org/debutant)
Recupérez l'image système iso puis vérifiez son [intégrité](https://doc.ubuntu-fr.org/tutoriel/comment_verifier_l_integrite_de_son_image_cd)

#Installation d'applications:#

##FTP##
Installation d'un serveur FTP sur le poste de travail Linux
[Serveur FTP Linux](https://openclassrooms.com/courses/creer-son-serveur-ftp)

Test de fonctionnement de votre serveur FTP par l'utilisation d'un client ftp depuis votre machine Windows

Installation d'un client FTP sur votre machine Windows
[Client FTP Windows - FileZilla ](https://filezilla-project.org/)
[Installation](https://wiki.seedbox.fr/index.php/Installer_un_client_FTP_pour_Windows_10)

Installation d'un serveur FTP sur le poste Windows 
[Serveur FTP Windows](https://www.supinfo.com/articles/single/2905-installation-configuration-serveur-ftp-filezilla)

Test de fonctionnement de votre serveur FTP par l'utilisation d'un client ftp depuis votre machine linux 
[Client FTP linux](https://doc.ubuntu-fr.org/ftp)

##Openssh###
Utilisation d'un client SSH sur windows
[putty](http://www.putty.org/)
[Client ssh Windows](http://marc.terrier.free.fr/docputty/)

Installation d'un serveur SSH sur ubuntu
[Openssh -- Procedure Ubuntu](https://doc.ubuntu-fr.org/ssh) 

Test du fontionnement du serveur SSH avec le client windows

