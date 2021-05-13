# Tuto Giteub
## Initialiser un projet
Pour initialiser un projet 

```bash
git init
```

## Ajouter à la Stagging zone
Pour valider son code, la zone avant un commit

```bash
# Ajouter un fichier
git add <nom_du_fichier>

# Ajouter tout les fichiers
git add .
```

Pour vérifier que ta zone de validation :

```bash
git status
```

# Commit

## Pour sauvegarder la zone de validation dans un commit

```bash
git commit -m <nom de la modif>
```

## Pour naviguer entre les commits

```bash
git checkput <hash>>
```

## Pour visualiser tous les commits

```bash
## --oneline pour afficher un commit par ligne
git log --oneline
```

# Branche

## Pour créer une nouvelle branche

```bash
git branch <nomDeBranche>
## Pour voir toutes les branches
git branch
```

## Pour pointer vers une branche

```bash
git checkout <nomDeBranche>
```