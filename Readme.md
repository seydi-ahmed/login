# login(2e projet de la branche sysadmin de zone01 dakar)
## changer le mot de passe
- simple
    - sudo passwd
    - saisir le mot de passe actuel
    - entrez  le nouveau mot de passe
- root
    - sudo passwd root
    - saisir le mot de passe actuel
    - entrez le nouveau mot de passe

## effacer la console par un raccourci clavier
- ctrl + L

## afficher l'historique des commandes en utilisant 5 frappes ou moins (avec autocomplétion)
- histo + tabulation + entrée

## se déconnecter avec un raccourci clavier
- ctrl + D

## vérifier la coonectivité internet avec ping
- ping google.com

## trouver l'inode d'un fichier
- ls -i chemin_du_fichier
    - permet de retrouver le chemin d'un fichier à partir de d'un numéro (méta donné du fichier)
    - find ~/Documents/login -inum INODE

## afficher l'id de l'utilisateur actuel
- id
    - uid : identifiant unique de l'utilisateur dans le systéme
    - gid : identifiant dans le groupe principal
    - groups : l'ensemble des groupes dans lequel il appartient

## trouver le PID d'un programme (ex. bash)
- pgrep bash
    - PID : Process Identifier (un identifiant accordé à un processus en cours)
5b92b
## developer
- Name: Mouhamed DIOUF
- email: diouf.mouhamed3@ugb.edu.sn