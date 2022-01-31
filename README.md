# ModOAP - Détection de doublons images

Ce script permet de détecter des doublons au sein d'un corpus d'images situé sur un Google Drive.

Le corpus doit être présenté sous forme d'un dossier Google Drive contenant directement l'ensemble des images

Le script génère un fichier txt listant les doublons repérés, et propose de visualiser ces doublons dans une cellule du carnet.

Le script implémente la version CNN de la bibliothèque Imagededup : https://github.com/idealo/imagededup (Tanuj Jain and Christopher Lennan and Zubin John and Dat Tran, 2019)

Il doit être lancé dans un environnement d'exécution GPU : Exécution -> Modifier le type d'exécution -> GPU

Ce carnet nécessite de synchroniser un compte Google Drive.
