# Solution : Gestion de branches GitHub

## Étapes à suivre

### 1. Créer un dépôt GitHub
- Accédez à [GitHub](https://github.com/)
- Cliquez sur **New repository**
- Nommez le dépôt **website-flow**
- Cochez "**Initialize this repository with a README**"
- Cliquez sur **Create repository**

### 2. Cloner le dépôt sur votre machine
```bash
# Remplacez USERNAME par votre nom d'utilisateur GitHub
git clone https://github.com/USERNAME/website-flow.git
cd website-flow
```

### 3. Créer et basculer sur la branche `cheese`
```bash
git checkout -b cheese
```

### 4. Modifier le fichier `README.md`
Ajoutez une liste de vos fromages à pizza préférés dans `README.md` :
```markdown
## Fromages à Pizza préférés
- Mozzarella
- Parmesan
- Gorgonzola
- Cheddar
- Emmental
```

### 5. Valider et pousser les modifications
```bash
git add README.md
git commit -m "Ajout de mes fromages à pizza préférés"
git push origin cheese
```

### 6. Créer une pull request sur GitHub
- Allez sur votre dépôt sur GitHub.
- Cliquez sur "Compare & pull request".
- Vérifiez les modifications et cliquez sur "Create pull request".
- Une fois validée, cliquez sur "Merge pull request".

### 7. Supprimer la branche `cheese`
```bash
git branch -d cheese
git push origin --delete cheese
```

### 8. Partager le lien du repo avec l'historique des commits
Votre lien final devrait ressembler à :
```text
https://github.com/USERNAME/website-flow/commits
```

