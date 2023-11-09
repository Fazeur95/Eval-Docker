
  # Évaluation docker

MZEBLA Faouizi & GOMES VITORINO Marvin

## Connexion à la machine virtuelle
Nous allons nous connecter à la machine virtuelle via la fonction SSH. Nous utiliserons la même machine virtuelle que pour l'évaluation précédente.

![](https://cdn.discordapp.com/attachments/751435338911711284/1167448442986041448/image.png)

Nous utilisons la commande scp pour copier nos fichier locaux vers la machine virtuelle.

![](https://cdn.discordapp.com/attachments/751435338911711284/1172132341402058783/image.png)


## Gestion des images
  ### Création du fichier de build des images
   Nous allons crée un fichier docker-compose.build.yml pour créer toute nos images a partir des Dockerfile fournit dans l'énoncé.
   Voici le fichier : 
   ![](https://cdn.discordapp.com/attachments/751435338911711284/1172133161396871228/image.png)

Une fois le fichier créer et envoyé sur la machine virtuelle nous executons cette commande (sur la machine virtuelle) : 

![](https://cdn.discordapp.com/attachments/751435338911711284/1172133688398581840/image.png)

   ### Création des tags des images
   
   
