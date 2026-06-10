# Site OPEO - 10 juin 2026

Ceci est la version complète du site internet OPEO, incluant tous les fichiers nécessaires au fonctionnement.

## 📁 Structure du Projet

```
opeo-10juin2026/
├── index.html                      # Page d'accueil
├── a-propos.html                   # Page à propos
├── secteurs.html                   # Page des secteurs
├── secteur-luxe.html              # Secteur Luxe
├── secteur-process.html           # Secteur Industrie de Process
├── secteur-aeronautique.html      # Secteur Aéronautique & Défense
├── secteur-pharma.html            # Secteur Pharmaceutique - Santé
├── expertises.html                # Page des expertises
├── expertise-*.html               # Pages des expertises individuelles
├── transformation.html             # Page transformation
├── publications.html               # Page publications
├── contact.html                    # Page contact
├── carrieres.html                  # Page carrières
├── mentions-legales.html          # Mentions légales
├── styles.css                      # Feuille de styles principale
├── main.js                         # JavaScript principal
├── server.js                       # Serveur Node.js
├── package.json                    # Dépendances Node.js
│
├── 📁 js/                          # Fichiers JavaScript additionnels
├── Images du site (*.jpg, *.png, *.svg)
│   ├── hero-bg.jpg
│   ├── hero-apropos.jpg
│   ├── mission-bg.jpg
│   ├── geste-transfo-photo.jpg
│   ├── photo-expertise.jpg
│   ├── illu-opeo.jpg
│   ├── banniere-publications.jpg
│   ├── viseul-secteurs.png
│   └── logo-official.svg
│
└── Documentation (*.md)
    ├── README.md
    ├── QUICK_START.md
    ├── GITHUB_INSTRUCTIONS.md
    ├── CONFIGURATION.md
    ├── CHECKLIST.md
    └── CHANGELOG.md
```

## 🚀 Démarrage

### Option 1 : Serveur Local (Node.js)
```bash
# Installer les dépendances
npm install

# Démarrer le serveur
npm start
# ou
node server.js
```

Le site sera accessible à `http://localhost:3000`

### Option 2 : Serveur Simple (Python)
```bash
# Python 3
python -m http.server 8000

# ou Python 2
python -m SimpleHTTPServer 8000
```

Le site sera accessible à `http://localhost:8000`

### Option 3 : Ouvrir directement
Double-cliquez sur `index.html` pour l'ouvrir dans votre navigateur.

## 🚀 Optimisation GitHub (10 juin 2026)

**Taille réduite de 154 MB → 12 MB** ✨

Le dossier a été optimisé pour GitHub en supprimant les fichiers inutilisés :
- ✅ Suppression du dossier `deploy/` (85 MB - fichiers compilés)
- ✅ Suppression du dossier `screenshots/` (13 MB - captures d'écran)
- ✅ Suppression du dossier `photo site internet/` (38 MB - images non utilisées)
- ✅ Suppression des fichiers dupliqués et fichiers de test

**Résultat:** Tous les fichiers essentiels sont présents, aucun fichier > 25 MB, prêt pour GitHub ! 🎉

## 📝 Modifications Récentes (10 juin 2026)

### Corrections des Pages Secteurs
- ✅ Breadcrumb navigation corrigée (affichait "Expertises › Supply Chain" partout)
- ✅ Numérotation "02" et "EXPERTISE 02/05" supprimée
- ✅ Tags des sous-secteurs mis à jour avec les vraies valeurs :
  - **Luxe** : Horlogerie et Joaillerie, Maroquinerie, Cosmétique
  - **Industrie de Process** : Chimie, Basic Materials et Métallurgie, Agroalimentaire
  - **Aéronautique & Défense** : Sous-traitance, OEM / MRO, Donneurs d'ordre
  - **Pharmaceutique – Santé** : Pharmaceutique, Technologie Médicale, BioPharmaceutique

### Ajout des CTA Buttons
- ✅ Deux boutons CTA ajoutés au sommet de chaque page secteur :
  - "Prendre rendez-vous →"
  - "Voir nos offres"
- ✅ Alignement vertical des boutons optimisé

### Sections Missions Réalisées
- ✅ Mises à jour avec des exemples spécifiques à chaque secteur
- ✅ Contenu générique remplacé par des cas concrets

## 🔧 Configuration

### Serveur Node.js (server.js)
```javascript
const PORT = 3000;
// Accès à tous les fichiers statiques du répertoire courant
```

### Chemins des Ressources
Tous les chemins sont **relatifs** pour assurer la compatibilité lors du déploiement :
- Images : `./photo site internet/` ou fichiers à la racine
- Styles : `./styles.css`
- Scripts : `./main.js` et `./js/`

## 📱 Responsive Design

Le site est optimisé pour :
- 📱 Mobile (320px et plus)
- 📱 Tablettes (768px et plus)  
- 💻 Desktop (1024px et plus)

## 🔐 Important

⚠️ **Ne pas déplacer les images** sans mettre à jour les chemins dans les fichiers HTML. Les chemins relatifs dépendent de la structure du dossier.

## 🌐 Déploiement

Pour publier sur GitHub Pages ou un autre service d'hébergement :

1. Assurez-vous que `index.html` est à la racine
2. Tous les chemins sont relatifs (`./ ` ou chemins sans slash initial)
3. Les images doivent rester dans leurs emplacements respectifs
4. Testez localement avant de déployer

## 📧 Support

Pour toute question sur le site OPEO, contactez l'équipe OPEO.

---

**Date de compilation** : 10 juin 2026  
**Version** : 2.0  
**Statut** : Production
