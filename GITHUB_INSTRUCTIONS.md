# Instructions pour Publier sur GitHub

## Prérequis

- Git installé sur votre ordinateur : https://git-scm.com/
- Un compte GitHub : https://github.com/

## Étapes de Publication

### 1. Initialiser le Dépôt Git

```bash
cd /Users/diego/Desktop/opeo-10juin2026
git init
```

### 2. Ajouter les Fichiers

```bash
git add .
```

### 3. Créer le Commit Initial

```bash
git commit -m "Initial commit - OPEO website v2.0 (10 juin 2026)

- Fixed breadcrumb navigation on sector pages
- Updated sub-sector tags with correct values
- Removed ghost numbering from pages
- Added CTA buttons to sector pages
- Updated missions sections with real examples"
```

### 4. Créer un Dépôt sur GitHub

1. Allez sur https://github.com/new
2. Entrez le nom du dépôt : `opeo-site` (ou votre choix)
3. Cochez "Public" pour que ce soit visible publiquement
4. Cliquez "Create repository"

### 5. Ajouter la Branche Distante

```bash
git remote add origin https://github.com/VOTRE_USERNAME/opeo-site.git
git branch -M main
```

Remplacez `VOTRE_USERNAME` par votre nom d'utilisateur GitHub.

### 6. Pousser le Code

```bash
git push -u origin main
```

## Option : GitHub Pages (Hébergement Gratuit)

Si vous avez poussé sur GitHub, vous pouvez héberger le site gratuitement :

### Configuration

1. Allez sur le dépôt GitHub
2. Cliquez sur **Settings** → **Pages**
3. Sous "Source", sélectionnez la branche `main`
4. Sauvegardez

Votre site sera accessible à : `https://votre-username.github.io/opeo-site`

(Attendez quelques minutes pour que GitHub Pages construise et déploie le site)

## Fichier .gitignore (Déjà Inclus)

Le fichier `.gitignore` à la racine empêche l'envoi de :
- `node_modules/` (les dépendances peuvent être réinstallées)
- Fichiers système (`.DS_Store`, `Thumbs.db`)
- Fichiers de sauvegarde (`.bak`, `*~`)

## Commandes Utiles

### Vérifier l'état
```bash
git status
```

### Voir l'historique
```bash
git log
```

### Annuler des changements locaux
```bash
git checkout -- .
```

### Voir les changements non commitées
```bash
git diff
```

## Workflow Futur

Lors de prochaines modifications :

```bash
# Apporter les modifications aux fichiers

# Voir ce qui a changé
git status

# Ajouter les modifications
git add .

# Créer un commit
git commit -m "Description des changements"

# Pousser vers GitHub
git push
```

## Exemples de Bonnes Descriptions de Commit

```
✅ Fix breadcrumb on sector pages
📝 Update missions section with real examples  
🎨 Improve button alignment on mobile
🐛 Fix navigation links on pharma page
✨ Add new CTA buttons to top of sector pages
```

## En Cas de Problème

### Erreur d'authentification
```bash
# Pour HTTPS avec token (recommandé)
git remote set-url origin https://YOUR_TOKEN@github.com/USERNAME/opeo-site.git

# Ou configurez SSH : https://docs.github.com/en/authentication/connecting-to-github-with-ssh
```

### Désactiver l'authentification 2FA si problème
1. Utilisez un **Personal Access Token** : https://github.com/settings/tokens
2. Utilisez le token à la place du mot de passe

### Besoin de repartir de zéro ?
```bash
rm -rf .git
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/USERNAME/opeo-site.git
git push -u origin main
```

## Partager le Lien

Une fois publié, partage ce lien :
```
https://github.com/votre-username/opeo-site
```

Ou le lien en direct du site (si GitHub Pages) :
```
https://votre-username.github.io/opeo-site
```

## Documentation Supplémentaire

- README.md - Instructions pour lancer le site localement
- CONFIGURATION.md - Détails techniques et structure
- Tous les fichiers HTML commentés

---

**Bon déploiement ! 🚀**
