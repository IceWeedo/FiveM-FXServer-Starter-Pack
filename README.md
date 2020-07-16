## FiveM - FXServer Starter Pack
Pack FXServer pré-configuré pour Windows

## - Base
* FXServer Build 2430
* Xampp 7.4.7

## - Resources
* mysql-async 3.3.1
* async 1.0.1
* es_extended - 1.2.0 Final
* esx_menu_default 1.0.3
* esx_menu_list 1.0.1
* esx_menu_dialog 1.1.0
* nb_menuperso 2.5.0
* gcphone 2.21.0

## - Installation
### Base de données:
* Télécharger l'archive [ici](https://www.google.com)
* Extraire l'archive à la racine de votre disque local C:
  (C:\xampp)
* Installer les redistribuables
  * (xampp\commonredist\vcredist\)
* Exécuter xampp-control
  (xampp\xampp-control.exe)
* Démarrer MySQL et Apache
  (Start)
  
### Serveur:
* Télécharger l'archive [ici](https://www.google.com)
* Extraire l'archive à la racine de votre disque local C:
  (C:\FXServer)
* Modifier le fichier server.cfg avec vos informations: Nom du serveur, Clé FiveM, API Steam...
  * (FXServer\server-data\server.cfg)
* Ouvrire le port 30120 en TCP/UDP dans le pare-feu Windows et votre box internet
* Lancer run.bat
  * (FXServer\server-data\run.bat)
