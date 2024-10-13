# Documentation du projet

## Initialisation du dépôt

```bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit (bonne pratique)

```
Titre du commit

Description de notre commit avec les informations sur l'évolution du projet
```

## Envoyer un commit sur un dépôt distant

```bash
git add .
git commit -m "Tire du commit"
git push origin main
```

## Création d'une brache

```bash
git checkout -b NOM_BRACHE
```

Pour les bonnes pratique, on va intégrer la notion de revue de code, Pour cela, on va créer une branche, faire des modifications, les envoyes sur le dépôt distant, puis créer une pull request pour demander une revue de code.