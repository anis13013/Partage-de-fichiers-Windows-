# Partage-de-fichiers-Windows-

## Configuration Serveur : 
---

Ton serveur de fichiers est correctement installé et configuré / Préparation du partage (C'est la permission de partage (share permissions), pas NTFS. Elle doit être large, car le contrôle fin se fait en NTFS aprés.)
![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Serveur/Capture.PNG)

---

Résultat de la préparation du partage 

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Serveur/resultat%20conf%20file%20shared.PNG)

---

Configuration du dossier de partage, toujours laisser les permissions aux users en Read-Execute-ListFolders-contents-Read pour filtrer avec le contrôle NTFS directement !

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Serveur/propri%C3%A9t%C3%A9%20dossier_entreprise.PNG)

---

Modification du dossier RH, **faire de même avec le compte Directions**. La même démarche pour chaques comptes 
 - Dossier RH : accés RH & Direction
 - Dossier Compta : accés Compta & Direction
 - Dossier Direction : accés Direction 

( POUR RH ) 
![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/RH/Capture.PNG)
( POUR COMPTA ) 
![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Compta/Capture.PNG)

---

Le partage "Docs" est accessible depuis le réseau

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Serveur/pw%20Get-SmbShare.PNG)


---
---

## Côte Client RH : 

Tes commandes PowerShell pour lister les partages et mapper le lecteur réseau fonctionnent correctement

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/RH/mappe%20%2B%20verif.PNG)

---
RH n'a pas accés aux autres dossiers

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/RH/dossier%20directions.PNG)

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/RH/Capture1.PNG)

---

Accés à son répertoire

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/RH/Capture2.PNG)

---
---

## Côte Direction : 

Tes commandes PowerShell pour lister les partages et mapper le lecteur réseau fonctionnent correctement

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Direction/Capture.PNG)

Le compte Direction a accés à tous les dossiers : 

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Direction/Capture1.PNG)

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Direction/Capture2.PNG)

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Direction/Capture3.PNG)


---

# Côté Comptabilité : 

Tes commandes PowerShell pour lister les partages et mapper le lecteur réseau fonctionnent correctement

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Compta/Capture1.PNG)

Les accés restreints 

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Compta/Capture2.PNG)

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Compta/Capture3.PNG)

L'accés 

![image](https://github.com/anis13013/Partage-de-fichiers-Windows-/blob/8604f0f48ac4d66bdf48e064afaea7b00a0cb9db/v2/Compta/Capture4.PNG)




