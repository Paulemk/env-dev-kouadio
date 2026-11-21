# Aide-mémoire du terminal Linux

## Se déplacer

| Commande | Ce qu'elle fait               | Exemple    |
| -------- | ----------------------------- | ---------- |
| `pwd`    | Affiche le dossier où je suis | `pwd`      |
| `cd`     | Change de dossier             | `cd ~/dev` |
| `ls`     | Liste le contenu d'un dossier | `ls -la`   |
| `clear`  | Efface l'écran du terminal    | `clear`    |

## Fichiers et dossiers

| Commande | Ce qu'elle fait                    | Exemple          |
| -------- | ---------------------------------- | ---------------- |
| `mkdir`  | Crée un dossier                    | `mkdir docs`     |
| `touch`  | Crée un fichier vide               | `touch a.txt`    |
| `cp`     | Copie un fichier                   | `cp a.txt b.txt` |
| `mv`     | Déplace ou renomme un fichier      | `mv a.txt c.txt` |
| `rm`     | Supprime un fichier                | `rm b.txt`       |
| `rm -r`  | Supprime un dossier et son contenu | `rm -r docs`     |

## Lire et chercher

| Commande | Ce qu'elle fait                   | Exemple                 |
| -------- | --------------------------------- | ----------------------- |
| `cat`    | Affiche le contenu d'un fichier   | `cat README.md`         |
| `less`   | Lit un long fichier page par page | `less README.md`        |
| `head`   | Affiche les premières lignes      | `head -n 5 README.md`   |
| `tail`   | Affiche les dernières lignes      | `tail -n 5 README.md`   |
| `grep`   | Cherche un mot dans un fichier    | `grep Ubuntu README.md` |
| `find`   | Cherche un fichier par son nom    | `find . -name "*.md"`   |
| `wc`     | Compte lignes, mots, caractères   | `wc -l README.md`       |
| `echo`   | Affiche un texte                  | `echo "Bonjour"`        |

## Informations système

| Commande         | Ce qu'elle fait                | Exemple          |
| ---------------- | ------------------------------ | ---------------- |
| `whoami`         | Affiche mon nom d'utilisateur  | `whoami`         |
| `lsb_release -d` | Affiche la version d'Ubuntu    | `lsb_release -d` |
| `nproc`          | Donne le nombre de processeurs | `nproc`          |
| `free -h`        | Affiche la mémoire             | `free -h`        |
| `history`        | Liste les commandes tapées     | `history`        |
| `man`            | Ouvre le manuel d'une commande | `man ls`         |

## Branches

- `git branch` : afficher les branches.
- `git switch nom-branche` : changer de branche.
- `git switch -c nom-branche` : créer une branche et basculer dessus.
- `git merge nom-branche` : fusionner une branche dans la branche actuelle.
- `git branch -d nom-branche` : supprimer une branche.
