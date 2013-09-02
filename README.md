Script forked from NicoLargo's Openvpnscripts.

This script allows to create a new user for OpenVPN


This Fork adds a choice to send the files to the user by mail or put in a web folder (/var/www/).

Don't forget to change the folder from openvpn (/etc/openvpn/confuser) and apache (for downloading the user's files).

I using mutt to send the files by mail. The script will check and/or install it if needed.

(but you can change it:))


----------------------------------------------------

Fork du script de NicoLargo

Ce script permet de créer un nouvel user pour OpenVPN

Il ajoute un choix permettant d'envoyer les fichiers de configuration directement par mail ou les 
déplacer dans un dossier d'apache pour un download direct par l'user.

N'oubliez pas de changer les répertoires d'openvpn et d'apache et aussi le port dans le script.

J'utilise mutt pour envoyer le fichier. Le script va vérifier et installer si besoin

(mais vous pouvez modifier le programme utilisé bien sur :))
