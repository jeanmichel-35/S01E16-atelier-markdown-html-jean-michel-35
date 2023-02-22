# S01E16-atelier-markdown-html

Notre entreprise a développé une super application qui permet de calculer la quantité d'ingrédients pour faire une pâte à crêpes parfaite !
Jusqu'à maintenant, les instructions pour l'installation et l'utilisation étaient en ligne sur le Github du projet, sous forme d'une fichier README.md

Mais aujourd'hui, l'entreprise souhaite mettre son application directement en ligne, et donc ajouter les instructions sur une page dédiée.

Votre mission, si vous l'acceptez, sera donc de migrer le fichier markdown `instructions.md` en HTML dans un nouveau fichier `index.html`.

Mais votre collègue est sympa, vu que vous venez d'arriver dans l'entreprise, il vous a préparé le travail en créant la base du fichier HTML. Il ne vous reste plus qu'à le remplir !

Vous pourrez donc trouver le fichier Markdown `instructions.md` et le fichier HTML `index.html` à la racine du dossier du projet.

Objectifs : 
* savoir lire un fichier Markdown :nerd_face:
* une première prise en main du HTML :partying_face:
* pouvoir retranscrire la syntaxe Markdown aux balises associées en HTML :eyes:
* utiliser Liveserver pour voir le rendu HTML
* demander de l'aide si on bloque ou si on a des questions :wink:


## Étape 1 - On prépare le projet

Ça devrait commencer à rentrer doucement pour cette étape, mais voici quelques rappels :
1. On commence par copier le lien SSH du repo
2. On ouvre son terminal dans le dossier où l'on souhaite cloner le repo (votre dossier de Saison 1 par exemple)
3. On tape la commande `git clone lien_ssh_du_repo` avec le lien SSH fraîchement copiée
4. Une fois le repo cloné, on se place directement dans le dossier du projet avec la commande `cd S01E16-atelier-markdown-html-pseudo_github`. On n'oublie pas que l'autocomplétion avec la touche `TAB` est là pour vous aider :wink:
5. Depuis le dossier du projet, on peut ouvrir VSCode avec la commande `code .`

## Étape 2 - On commence à bosser

Ensuite, on prend connaissance du fichier `instructions.md`.
Commencez par repérer les différentes balises utilisées.
Vous pouvez déjà repérer les balises HTML associées.

Une fois cette étape de "reconnaissance du terrain", ouvrez votre fichier `index.html` (toujours dans VSCode).

Une fois votre fichier HTML ouvert, vous pouvez démarrer Liveserver en cliquant sur le bouton "Go Live" situé tout en bas à droite.

![Liveserver](https://cdn.discordapp.com/attachments/564730692039081996/1045374726270374008/image.png)

Votre navigateur doit donc s'ouvrir, et une page qui affiche "Écrire ton code HTML ici" doit apparaître.

On repasse donc dans le fichier HTML, et on commence à écrire nos toutes premières balises :grin: (on pense à effacer la phrase d'indication de notre collègue au passage :wink: )

## Étape 3 - On envoie notre travail sur Github

Que l'on ait terminé le travail ou non, notre collègue a besoin de notre fichier à 15h pétante au plus tard, afin de le relire/compléter avant de le mettre en ligne sur le site.

Pour cela, vous connaissez la musique, on va donc le mettre en ligne sur Github.

Quelques rappels :
1. On commence par mettre nos fichiers modifiés en attente pour le prochain commit avec la commande `git add .`
2. On peut ensuite vérifier que le fichier est bien en attente avec la commande `git status`. Si le fichier apparaît en vert, c'est que c'est bon. S'il est en rouge, c'est qu'il y a eu un soucis a l'étape 1. Dans ce deuxième cas de figure, on n'hésite pas à faire appel à ses pairs ou à son collègue pour qu'il regarde :wink:
3. On peut désormais créer notre commit avec `git commit -m "Mon message de commit"`
4. Puis on envoie tout cela sur Github avec la commande `git push`


:warning: **OPTIONNEL**
## Étape Bonus - Le tableau 

En seconde partie du fichier `instructions.md`, on voit qu'il y a un tableau.
Notre collègue nous a indiqué que c'était peut-être encore un peu compliqué, mais que si on voulait tenter de le faire en HTML, cela lui ferait plaisir de jeter un œil.

Vous n'avez pas encore vu comment faire un tableau, mais votre collègue vous a envoyé quelques liens vers la documentation HTML qui pourraient vous aider.

* [La documentation MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)
* [Les tableaux](https://www.w3schools.com/html/html_tables.asp)

## Étape Bonus - Image

![Logo](logo-patakrep.png)

Si vous vous en sentez capable, essayez d’intégrer le logo de l’entreprise au début de la page html.

* [Les images html](https://developer.mozilla.org/fr/docs/Web/HTML/Element/Img)
