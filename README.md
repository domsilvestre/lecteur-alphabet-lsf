# Lecteur de l'alphabet de la langue des signes française (LSF)

Une application web qui reconnaît, avec ta webcam, les lettres de l'alphabet de la langue des signes française, et qui écrit le mot épelé à l'écran.

**Version de test.** Elle n'a pas encore été testée par une personne sourde ou qui pratique la LSF. Elle reconnaît seulement l'alphabet, lettre par lettre : ce n'est pas un traducteur de la langue des signes, qui a sa grammaire, ses mouvements et les expressions du visage.

## L'utiliser

Essaie-la en ligne : https://domsilvestre.github.io/lecteur-alphabet-lsf/ , ou télécharge `index.html` et ouvre-le directement. Dans les deux cas, utilise Chrome, Edge ou Firefox, autorise la caméra, puis épelle un mot devant la webcam.

La détection tourne dans ton navigateur : aucune image ne quitte ton ordinateur, et il n'y a ni compte ni serveur qui reçoit tes images. En ligne, la page est seulement hébergée par GitHub Pages. Dans les deux cas, les bibliothèques de détection de la main (MediaPipe, de Google) sont chargées depuis internet au démarrage.

Si une lettre est mal reconnue, tu peux la réapprendre en montrant ta main quelques secondes. Un mode test permet aussi de charger une vidéo ou des images à la place de la caméra.

## D'où vient cette app

Elle a été créée pour un défi filmé sur la chaîne YouTube de Dominique Silvestre : une heure donnée à plusieurs IA, avec la même consigne, pour créer la même application, sans aucune correction humaine. Cette version est celle de **Claude Fable 5.2**, publiée telle qu'elle est sortie au bout de l'heure, avec une seule correction faite après le défi : la caméra s'éteint maintenant bien si le détecteur de main ne se charge pas.

- **La vidéo YouTube dédiée au défi** : [Fable 5.2 vs Opus 5.5 vs Gemini 4 : 1h pour coder une app LSF](https://youtu.be/F_Pq3q3EvNE). On y voit les apps de chaque IA testées en direct.
- Les repères de la main ont été mesurés par l'IA sur les photos de l'alphabet LSF de [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:French_Sign_Language) (fichiers « LSF LettreX.jpg », licence CC BY-SA 3.0).

## Le reprendre

Ce projet n'est pas maintenu : il reste tel qu'il est sorti du défi. Tu peux le copier et l'améliorer librement (licence MIT).

## Noxcod

Ce projet est proposé par [Noxcod](https://noxcod.com), le studio de Dominique Silvestre, qui conçoit des applications et des agents IA pour les entreprises et les associations. Tu as un projet comme celui-ci ? [Écris-nous](https://noxcod.com).

## Licence

Code sous licence MIT (voir `LICENSE`).
