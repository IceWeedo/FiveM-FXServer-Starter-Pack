## - FiveM - FXServer Starter Pack
Pack FXServer pré-configuré pour Windows

## - Contenu du pack
* #### Base:
  * FXServer **Build 3404**
  * txAdmin **3.2.3**
  * Xampp **7.4.14**

* #### Ressources:
  * async **1.0.1**
  * mysql-async **3.3.2**
  * cron **1.0.0**
  * es_extended **V1 Final**
  * esx_menu_default **1.0.4**
  * esx_menu_list **1.0.2**
  * esx_menu_dialog **1.1.0**

## - Installation
* #### Base de données:
  * Télécharger l'archive [ici](https://github.com/IceWeedo/FiveM-FXServer-Starter-Pack/releases/latest)
  * Extraire l'archive à la racine de votre disque local **C:**
    * (C:/xampp)
    
  * Installer les redistribuables
    * (C:/xampp/_commonredist)
    
  * Exécuter xampp-control
    * (C:/xampp/xampp-control.exe)
    
  * Démarrer MySQL et Apache
  
  ![xampp](https://i.ibb.co/rvwWvnY/xampp.png)

* #### Serveur:
  * Télécharger l'archive [ici](https://github.com/IceWeedo/FiveM-FXServer-Starter-Pack/releases/latest)
  * Extraire l'archive à la racine de votre disque local **C:**
    * (C:/FXServer)

  * Modifier le fichier **server.cfg** avec vos informations: **Nom du serveur**, [Clé FiveM](https://keymaster.fivem.net), [Clé API Steam](https://steamcommunity.com/dev/apikey)
    * (C:/FXServer/server.cfg)

  * Ouvrire le port **30120** en **TCP/UDP** dans le pare-feu Windows et votre box internet
  * Exécuter run.bat
    * (C:/FXServer/run.bat)
 
## - Droit administrateur
* #### FXServer:
  * Connectez-vous au panel **txAdmin** [ici](http://localhost:40120/)
  
  
  * Cliquez sur votre nom dans la liste de droite
  
  ![CMD](https://i.ibb.co/rc9Qhj5/txadmin-id.png)
  
  * Dans le fichier **server.cfg** (C:/FXServer/server.cfg) section **# Add system admins** ajouter la ou les lignes suivante
  * Utilisateur Steam:
    * **add_principal identifier.steam:xxxxxxxxxxxxxx group.admin**
    
  * Utilisateur non-Steam:
    * **add_principal identifier.license:xxxxxxxxxxxxxxxxxxxxxxxxxxxx group.admin**
      
  ![CMD](https://i.ibb.co/LhFGN2P/servercfg-admin.png)
     
  * Redémarrer votre serveur

* #### ES eXtended:
  * Connectez-vous au panel **phpMyAdmin** [ici](http://localhost/phpmyadmin/)
  
  
  * Dans la base de données **es_extended** table **users** colonne **group** remplacer **user** par **superadmin**
  
  ![Alt Text](https://i.ibb.co/vw8PvvY/xampp-admin.png)

## - En jeu
* #### Touche:
  * Inventaire: **F2**
  * Console: **F8**
