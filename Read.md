# DevInte

- Ma première ligne
- Ma deuxième ligne
- Ma troisème ligne

1. 1er ligne 2. 2eme ligne
2. 3eme ligne

- Italique \*
  --- Souligné ---
  ** Gras **
  ~~ Barré ~~

> Ceci est une citation

| Nom     | Age | Ville |
| ------- | --- | ----- |
| Laurine | 22  | Lens  |
| Toto    | 58  | Lille |

## Commandes de bases de Git =

- git init - Crée un dépôt Git vide ou réinitialise un dépôt existant
  (Elle permet de convertir un projet existant, sans version en un dépôt Git ou d'initialiser un nouveau dépôt vide.)

- git add : Ajoute le contenu de fichiers à l’index

- git status : Montrer le statut de l’arbre de travail

- git commit : Permet de créer des versions d'un projet, enregistre les changements dans l'historique du projet.

- git remote : Permet de créer, d'afficher et de supprimer des connexions avec d'autres dépôts. Lié

- git pull : Permet de trouver les modifications. Permet de récupérer les modifications via un autre dépot

- git push : Met à jour les références distantes ainsi que les objets associés. Envoyer le code dans git hub

- git clone : Clone un dépôt dans un nouveau répertoire

- git add : Indexé un fichier

- git fetch : Cherche les modifications dans Git Hub sans modifier

(git commit -m “docs : add Jour04.md”
doc = document
feat = code)

git remote add origin https:// = Lié via l’adresse
(origin = le nom du depot)

git remote -v = Utilisée pour afficher les URL des dépôts distants associés à votre dépôt Git local. Elle vous permet de savoir vers où votre dépôt local est connecté pour pousser ou récupérer des modifications.

### Commande pour mettre de visual code a Git Hub

git init > Pour crée le dépot
git add README.md > Ajouter le ficher
git commit -m "first commit" > Créer un commit
git branch -M main > Renomer la branch en Main
git remote add origin https://github.com/********/*******.git
git push -u origin main
