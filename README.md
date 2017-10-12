# modeEmploiGithub

## Etapes à suivre

+ 1 Sur le site Github, une fois connecté vous avez un petit plus en haut à droite. Cliquez et choisissez New repository (sert à créer le dossier).Donnez lui un nom. Exemple modeEmpoiGithub

+ 2 Cloner ce fichier dans votre ordinateur.
  + Sur le site copier le lien (le gros bouton vert clone or download)
  + dans la console il faut que vous soyez dans le bon fichier. tapez **cd /opt/lampp/htdocs** (moi je souhaite qu'il soit dans mon htdocs mais à vous de choisir le lieu qui vous convient. Si c'est le bureau par exemple tapez cd Desktop
  + dans la console tapez la commande: **git clone "leLienQueVousVenezDeCopier"** . Le dossier modeEmploiGithub est maintenant dans votre htdocs.

+ 3 Créer une branche si vous le souhaitez. dans la console tapez la commande : **git branch nomDelaBranche**
+ 4 Vous mettre sur votre branche : **git checkout nomDeLaBranche**
+ 5 Vérifiez que vous êtes bien sur votre branche : **git status** 
+ 6 Dans le dossier modeEmploiGithub (dans votre htdocs) rajoutez un fichier/un dossier exemple index.html
+ 7 Envoyez ce fichier sur votre github: 
  + dans la console faites **git add nomDuFichierArajouter** dans ce cas-ci : **git add index.html.** Si vous souhaitez envoyer plusieurs fichiers/dossiers d'un seul coup la commande est : **git add .**
  + faites **git status.** Normalement votre fichier est écrit en vert pour signaler que cette étape est bonne.
  + faites un commit. Le commit peut être considéré comme un commentaire qui explique ce que vous venez de faire. Ainsi vos partenaires sauront de quoi il s'agit. La commande : **git commit -m "j'ai rajouté un fichier index.html"**
  + faites **git status** pour vérifier. Maintenant au lieu d'etre vert c'est blanc.
 + 8 Dernière étape (ouf) :). Nous allons définitivement envoyer ce fichier sur le site de github. Pour ce faire il faut "pusher". La commande : **git push** (envoie tout sur la branche master) ou **git push -u origin master** (envoie tout sur la branche master aussi) ou **git push -u origin NomDeVotreBranche** (envoie tout sur votre branche).
 +9 Merger les branches (les fusionner) : il faut etre sur la branche master **git branch origin master".** N'oubliez pas de verifier que vous êtes dessus avec un git init. Ensuite tapez la commande : **git merge nomDeLaBranche**
 
 Reccupérer les dossiers chez vous : 
 + 9 git pull
 
 A savoir
 **git branch -d nomDeLaBranche** : pour "deleter"/ effacer une branche.
 **git log** : voir l'historique de vos commits.
 
