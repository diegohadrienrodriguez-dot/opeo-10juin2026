# 🚀 Quick Start - Lancer le Site Localement

## En 30 Secondes

### Option 1: Python (Le Plus Simple)
```bash
cd /Users/diego/Desktop/opeo-10juin2026
python -m http.server 8000
```
Puis ouvrez : http://localhost:8000

### Option 2: Node.js
```bash
cd /Users/diego/Desktop/opeo-10juin2026
npm install
npm start
```
Puis ouvrez : http://localhost:3000

### Option 3: Double-Cliquez
Double-cliquez sur `index.html` et le site s'ouvre dans votre navigateur.

---

## Vérifications Après Lancement

✅ **La page d'accueil s'affiche**
- Logos visibles
- Images du héro chargées
- Texte bien formaté

✅ **Les images s'affichent**
- Photos du site internet
- Logos (SVG)
- Images de fond

✅ **La navigation fonctionne**
- Cliquez sur les liens du menu
- Les pages se chargent correctement
- Les breadcrumbs s'affichent bien

✅ **Testez les Secteurs**
- Allez sur https://localhost:8000/secteurs.html
- Cliquez sur chaque secteur
- Vérifiez que les breadcrumbs sont corrects :
  - Secteurs › Luxe
  - Secteurs › Industrie de Process
  - Secteurs › Aéronautique & Défense
  - Secteurs › Pharmaceutique – Santé

✅ **Vérifiez les CTA Buttons**
- En haut de chaque page secteur
- "Prendre rendez-vous →" 
- "Voir nos offres"

---

## Dépannage

### Erreur "Port déjà utilisé"
```bash
# Python: Utilisez un port différent
python -m http.server 9000
# Puis allez à http://localhost:9000

# Node.js: Modifiez server.js
```

### Les images ne s'affichent pas
- Assurez-vous que le dossier `photo site internet/` est présent
- Vérifiez que les images sont à la racine (logo-*.svg, hero-bg.jpg, etc.)
- Rechargez la page (Ctrl+F5 ou Cmd+Shift+R)

### Les styles ne s'appliquent pas
- Vérifiez que `styles.css` est à la racine
- Rechargez le cache du navigateur (Ctrl+Shift+Delete)
- Vérifiez que le fichier CSS n'est pas vide

### Les liens ne fonctionnent pas
- Assurez-vous que tous les fichiers .html sont à la racine
- Vérifiez les noms des fichiers (minuscules/majuscules)
- Cherchez dans la console du navigateur (F12) pour les erreurs

---

## Avant de Pousser sur GitHub

Cochez ces éléments avant de publier :

```
☐ Page d'accueil s'affiche correctement
☐ Toutes les images se chargent
☐ Navigation entre pages fonctionne
☐ Logos visibles
☐ Styles appliqués correctement
☐ Pages secteurs affichent les bons breadcrumbs
☐ CTA buttons visibles en haut des pages secteurs
☐ Formulaires fonctionnent (si applicable)
☐ Site responsive (testez sur mobile)
☐ Pas d'erreurs dans la console (F12)
```

---

## Après Vérification

Vous êtes prêt à publier ! Suivez :
**GITHUB_INSTRUCTIONS.md**

---

## Points de Repère

| Fichier | URL Locale |
|---------|-----------|
| Accueil | http://localhost:8000 |
| Secteurs | http://localhost:8000/secteurs.html |
| Secteur Luxe | http://localhost:8000/secteur-luxe.html |
| Secteur Process | http://localhost:8000/secteur-process.html |
| Secteur Aéronautique | http://localhost:8000/secteur-aeronautique.html |
| Secteur Pharma | http://localhost:8000/secteur-pharma.html |
| Expertises | http://localhost:8000/expertises.html |
| À Propos | http://localhost:8000/a-propos.html |
| Contact | http://localhost:8000/contact.html |
| Carrières | http://localhost:8000/carrieres.html |

---

## Raccourcis Clavier

| Raccourci | Action |
|-----------|--------|
| F12 | Ouvrir Developer Tools |
| Ctrl+Shift+R | Vider le cache et recharger |
| Cmd+Shift+R | (Mac) Vider le cache et recharger |
| Ctrl+Shift+K | Console (développeur) |

---

**Vous êtes prêt ! 🎉**

Lancez le serveur, testez le site, et publiez sur GitHub quand tout fonctionne.
