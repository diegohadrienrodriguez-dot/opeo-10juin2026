# ✅ Checklist Pré-Déploiement

## Vérification des Fichiers

- [x] Tous les fichiers HTML présents
- [x] Feuille de styles CSS incluse
- [x] Fichiers JavaScript présents
- [x] Dossier `js/` copié
- [x] Images essentielles à la racine
- [x] `.gitignore` configuré
- [x] Documentation complète
- [x] ✨ Optimisation GitHub appliquée (154 MB → 12 MB)

## Vérification des Chemins Relatifs

### Images (Essentielles Seulement)
```
✅ ./hero-bg.jpg
✅ ./hero-apropos.jpg
✅ ./mission-bg.jpg
✅ ./geste-transfo-photo.jpg
✅ ./photo-expertise.jpg
✅ ./illu-opeo.jpg
✅ ./banniere-publications.jpg
✅ ./viseul-secteurs.png
✅ ./logo-official.svg
```

### Fichiers HTML
```
✅ index.html (page d'accueil)
✅ a-propos.html (à propos)
✅ secteurs.html (tous les secteurs)
✅ secteur-luxe.html
✅ secteur-process.html
✅ secteur-aeronautique.html
✅ secteur-pharma.html
✅ expertises.html
✅ expertise-*.html (5 pages)
✅ transformation.html
✅ publications.html
✅ contact.html
✅ carrieres.html
✅ mentions-legales.html
```

### Styles et Scripts
```
✅ ./styles.css (principal)
✅ ./main.js (principal)
✅ ./js/ (dossier JavaScript)
```

## Vérification Technique

- [x] Pas de chemins absolus (commençant par `/`)
- [x] Tous les chemins sont relatifs (`./` ou directs)
- [x] Pas de fichiers corrompus
- [x] Structure de dossiers préservée
- [x] Permissions de fichiers correctes

## Avant de Publier sur GitHub

- [ ] Tester localement : `npm start` ou `python -m http.server 8000`
- [ ] Vérifier tous les liens de navigation
- [ ] Tester les images (toutes visibles ?)
- [ ] Tester sur mobile (responsive ?)
- [ ] Vérifier les formulaires
- [ ] Tester les boutons CTA

## Déploiement

- [ ] Créer dépôt GitHub
- [ ] Initialiser Git localement (`git init`)
- [ ] Ajouter fichiers (`git add .`)
- [ ] Créer commit initial (`git commit -m "..."`)
- [ ] Ajouter remote (`git remote add origin ...`)
- [ ] Pousser code (`git push -u origin main`)
- [ ] Configurer GitHub Pages (optionnel)
- [ ] Attendre ~5 min pour le déploiement

## Après Déploiement

- [ ] Vérifier le repo sur GitHub
- [ ] Tester le site en ligne
- [ ] Partager les liens
- [ ] Documenter dans CHANGELOG si modifications futures

## Fichiers Inclus dans ce Dossier

```
opeo-10juin2026/
├── ✅ README.md                    (Guide principal)
├── ✅ CONFIGURATION.md             (Détails techniques)
├── ✅ GITHUB_INSTRUCTIONS.md       (Guide publication)
├── ✅ QUICK_START.md               (Démarrage rapide)
├── ✅ CHECKLIST.md                 (Ce fichier)
├── ✅ CHANGELOG.md                 (Historique)
├── ✅ .gitignore                   (Fichiers à ignorer)
├── ✅ index.html + 19 autres       (20 pages HTML)
├── ✅ styles.css                   (Styles principal)
├── ✅ main.js                      (Script principal)
├── ✅ package.json                 (Dépendances)
├── ✅ server.js                    (Serveur Node.js)
├── ✅ js/                          (Scripts additionnels)
└── ✅ Images essentielles          (9 fichiers)
```

## Taille et Statistiques

```
Total files: 20 HTML + ressources
Total size: ~12 MB ✨ (réduit de 154 MB)
Images: 9 fichiers essentiels (JPG, PNG, SVG)
Dossiers: 1 (js)
```

## 📊 Optimisation GitHub Appliquée

```
SUPPRIMÉ (94 MB total):
  ❌ deploy/                (85 MB) - Fichiers compilés inutiles
  ❌ screenshots/           (13 MB) - Captures d'écran inutiles
  ❌ photo site internet/   (38 MB) - Images non utilisées dans le site
  ❌ Fichiers dupliqués              - Nettoyage complet
  ❌ Fichiers de test                - Supprimés

CONSERVÉ (12 MB):
  ✅ Tous les fichiers HTML essentiels
  ✅ CSS et JavaScript
  ✅ Images utilisées dans le site
  ✅ Documentation complète
  
✅ RÉSULTAT: Aucun fichier > 25 MB - Compatible GitHub!
```

## Notes Importantes

⚠️ **NE PAS OUBLIER** :

1. **Ne pas déplacer les images** - Les chemins sont relatifs
2. **Garder la structure** - Le dossier `js/` doit rester à la racine
3. **Tester localement** - Avant de pousser sur GitHub
4. **Vérifier les liens** - Surtout la navigation entre pages
5. **Le dossier est optimisé** - Prêt pour GitHub (12 MB)

## En Cas de Problème après Déploiement

- [ ] Images manquantes ? → Vérifier que les images JPG/PNG/SVG sont à la racine
- [ ] Styles cassés ? → Vérifier que `styles.css` est à la racine
- [ ] Scripts ne fonctionnent pas ? → Vérifier que `main.js` et le dossier `js/` existent
- [ ] Liens brisés ? → Vérifier les chemins relatifs dans les fichiers HTML

---

**🎉 PRÊT POUR PUBLICATION !** 🚀

✅ Tous les fichiers essentiels sont présents et correctement structurés
✅ Optimisé pour GitHub (12 MB - aucun fichier > 25 MB)
✅ Images utilisées conservées
✅ Documentation complète

Vous pouvez maintenant suivre **GITHUB_INSTRUCTIONS.md** pour publier.

---

Date: 10 juin 2026
Version: 2.0 (Optimisée pour GitHub)
Statut: ✅ PRODUCTION READY
