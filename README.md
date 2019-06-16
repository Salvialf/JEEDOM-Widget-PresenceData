# PresenceData

Widget pour Jeedom permettant d'afficher une icône ainsi que les données de présence (date et heure arrivée/départ + durée) à partir d'une simple info binaire.

<img src="/icon.png" alt="visuel"/>

Pour passer le texte sous l'icône et donc opter pour une présentation verticale, il faut mettre le paramètre ayant pour nom "<i><b>vertical</b></i>" à la valeur '**1**'.

Pour cacher l'affichage de la durée, il faut positionner le paramètre ayant pour nom "<i><b>duree</b></i>" à la valeur '**0**'.

Il est également possible de spécifier la hauteur et la largeur de l'icône par l'ajout de paramètres optionnels "<i><b>hauteur</b></i>" & "<i><b>largeur</b></i>" ayant pour valeur la dimension souhaitée.

Le widget inclus un visuel par défaut de couleur verte en cas de présence ainsi qu'un autre visuel de couleur rose.  
La sélection de l'icône rose passe par l'ajout d'un paramètre optionnel ayant pour nom "<i><b>qui</b></i>" et pour valeur '**femme**':
<img src="/cmd.info.binary.PresenceData/femme_on.png" alt="icone rose" height=90px width=90px/>

Il est possible et même recommandé d'ajouter ses propres icônes dans le widget telles que les photos des membres du foyer (la même photo en couleur en cas de présence et en noir & blanc en cas d'absence par exemple).  
Le nommage des icônes est normalisé et doit respecter le format suivant: "<i><b>qui</b>_off.png</i>"=*Absence* & "<i><b>qui</b>_on.png</i>"=*Présence*.  
Pour ajouter vos icônes, sur la page du Widget, cliquer sur le bouton "Fichiers" tout en haut puis "choisir un fichier" et ajouter vos images une par une. 
