# Présentation de fonctionnalités Git non ou peu couvertes par le cours

## Les alias de commandes
Les alias de commandes permettent de créer des raccourcis pour des commandes Git longues ou souvent utilisées, ce qui peut accélérer le travail.

### Exemple
Pour créer un alias pour la commande `git status`, vous pouvez utiliser la commande suivante :
```bash
git config --global alias.st status

# La commande git bisect

La commande git bisect permet de trouver rapidement quel commit a introduit un bug en procédant par recherche binaire.

### Exemple
Pour commencer une recherche binaire sur un bugg:

git bisect start

