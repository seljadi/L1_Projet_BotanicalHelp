# Cahier de bord


## Semaine 8/04: 
Première séance de projet, j’ai réussi à trouver une idée de projet mais personne avec qui me mettre donc je vais devoir travailler seule dessus, je sais pas trop comment tout ça va se dérouler.

## Semaine 15/04:
Cette semaine deuxième séance, On a eu la création du repository github avec uen introduction à github et début de réflexion du projet.

## Semaine 22/04 et 29/04: 
absente à cause de mon pied, j'ai pas du tout pu avancer mais j'ai fait ma présentation de mi projet.

## Semaine 6/05:
Lundi était fériée donc j'ai enfin pu faire ma présentation de mi projet le vendredi et j'ai pu enfin récupérer la carte programmable. J'avais pas pu vraiment avancer les dernières semaines vu que je ne l'avais pas.


## Semaine 13/05:
Cette semaine, modification du code afin d’avoir les valeur des capteurs intégrés à la carte programmable mais aussi du Maker soil moisture sensor. J’ai eu un problème ayant un Mac, il me faut un adapteur usb C afin de connecter la carte programmable à mon pc pour compiler le code. Mon adaptateur ou mon câble fonctionne pas du coup, il m’est impossible de recevoir les valeurs et voir ce que mes capteurs détectent. Aussi mon serveur node-red ne fonctionne plus depuis que j’ai installé le protocole pour envoyer les messages whatsapp, je n’arrive pas à les désinstaller en mode sans échec, je vais être obligée de le désinstaller et retelecharger.

## Semaine 20/05:
cahier de bord

Modification du code, utilisation du OTAA

Utilisation d’un pc différent mais je me retrouve toujours face à un problème pour compiler le code, je ne sais pas d’ou vient le problème. Aussi je n’arrive pas a lancer mode red sur le pc de la fac surement car je n’ai pas les droits d’admin car je suis un profil utilisateur étudiant. Le câble que j’utilisait permettait uniquement l’alimentation et non le transfert de données... J’ai essayé le changement de câble mais toujours dans l’incapacité d’uploader mon code sur la carte. Peut-être que c’est le pc?

J’ai enfin réussi à uploader mon code mais je ne sais pas pourquoi mais je reçois aucune payload sur TTN alors que tout est bon.
## Semaine 27/05:
cahier de bord

Cette semaine j’ai oublié ma carte chez moi, du coup j’ai du en emprunter une nouvelle et enfin la réception de payload sur TTN remarche mais cette fois ci node red veut pas se connecter à TTN donc je ne peux rien faire d’autre.

Mystère élucidé, le problème était le topic du serveur... Il était incorrect mais j’étais connectée dessus. J’ai reconfiguré le code d’envoi de message whatsAPP et je me suis faite harceler toutes les 10 secondes par le bot WhatsApp je dois changer ça avant demain, le jour de la présentation..

Aujourd’hui, présentation mais en f-modifiant le code, je suis passée de me faire harceler à ne plus rien recevoir. Le problème vient sûrement du bot, mais le prof a pu voir que ça avait fonctionné à un moment donné..
