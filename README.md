# Exercice-02-Active-Directory

Apres avoir installé Windows Server 2022, j'ai renommé le serveur et fixé son adresse IP.<br>
Ensuite j'ai créé un dossier sur le bureau (nommé "Script"), à l'intérieur j'ai créé un fichier Utilisateurs.csv, un fichier Utilisateurs_AD.ps1 et un fichier Install_AD.ps1.

J'ai exécuté Install_AD via Powershell <br>
Ensuite j'ai exécuté le fichier Utilisateurs_AD.ps1 

Une fois les 2 scripts exécutés, j'ai vérifié sur une machine cliente Windows 10 jointe au domaine en me connectant avec un utilisateur de l'AD, et j'ai vérifié que ça m'obligeait bien a changer de mot de passe a la première connexion. 
