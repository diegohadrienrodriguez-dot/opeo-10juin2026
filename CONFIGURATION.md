# Configuration du Site OPEO

## Informations Générales

- **Nom du projet** : Site OPEO
- **Date de mise à jour** : 10 juin 2026
- **Type** : Site statique HTML/CSS/JS
- **Framework** : Vanilla JS (pas de framework)

## Chemins des Ressources

Tous les chemins utilisent des **chemins relatifs** pour maximiser la compatibilité :

### Images
```
Photos du site: ./photo site internet/
Images racine: ./logo-*.svg, ./hero-bg.jpg, etc.
```

### Styles
```
Principal: ./styles.css
Inlined: Certains styles sont directement dans les fichiers HTML
```

### JavaScript
```
Principal: ./main.js
Modules: ./js/
```

## Pages Principales

| Page | URL | Description |
|------|-----|------------|
| Accueil | `index.html` | Page d'accueil principale |
| À Propos | `a-propos.html` | Qui sommes-nous + Équipe |
| Secteurs | `secteurs.html` | Tous les secteurs disponibles |
| Secteur Luxe | `secteur-luxe.html` | Page dédiée au secteur Luxe |
| Secteur Industrie de Process | `secteur-process.html` | Page dédiée à l'Industrie de Process |
| Secteur Aéronautique | `secteur-aeronautique.html` | Page dédiée à l'Aéronautique & Défense |
| Secteur Pharma | `secteur-pharma.html` | Page dédiée au Pharmaceutique - Santé |
| Expertises | `expertises.html` | Liste des 5 expertises |
| Expertise Digital | `expertise-digital.html` | Détails expertise Digital |
| Expertise Excellence | `expertise-excellence.html` | Détails expertise Excellence |
| Expertise R&D | `expertise-rd.html` | Détails expertise R&D |
| Expertise Stratégie | `expertise-strategie.html` | Détails expertise Stratégie |
| Expertise Supply Chain | `expertise-supply-chain.html` | Détails expertise Supply Chain |
| Transformation | `transformation.html` | Transformation OPEO |
| Publications | `publications.html` | Articles et cas d'études |
| Contact | `contact.html` | Formulaire de contact + Experts |
| Carrières | `carrieres.html` | Offres d'emploi |
| Mentions Légales | `mentions-legales.html` | Conditions légales |

## Optimisations Appliquées

### Performance
- ✅ Images optimisées (JPG pour photos, SVG pour logos)
- ✅ CSS minifié en production
- ✅ Lazy loading des images (où applicable)

### SEO
- ✅ Structure HTML sémantique
- ✅ Meta tags présents sur toutes les pages
- ✅ Breadcrumb navigation structurée

### Accessibilité
- ✅ Contraste de couleurs conforme WCAG
- ✅ Navigation au clavier fonctionnelle
- ✅ Alt text sur les images

## Corrections du 10 Juin 2026

### Bug Fixes - Pages Secteurs

1. **Breadcrumb Navigation** ✅
   - Avant : Affichait "Expertises › Supply Chain" sur TOUTES les pages secteur
   - Après : Affiche maintenant le bon secteur (Luxe, Process, etc.)
   - Fichiers modifiés : `secteur-luxe.html`, `secteur-process.html`, `secteur-aeronautique.html`, `secteur-pharma.html`

2. **Suppression de la Numérotation** ✅
   - Avant : Affichait "02" en fantôme et "EXPERTISE 02 / 05"
   - Après : Supprimé complètement
   - Impact : Pages plus propres et sans numérotation confuse

3. **Tags Sous-Secteurs** ✅
   - Avant : Texte générique (e.g., "Sub-Sector Label")
   - Après : Vrais sous-secteurs spécifiques à chaque secteur
   - **Luxe** : Horlogerie et Joaillerie, Maroquinerie, Cosmétique
   - **Process** : Chimie, Basic Materials et Métallurgie, Agroalimentaire
   - **Aéronautique** : Sous-traitance, OEM / MRO, Donneurs d'ordre
   - **Pharma** : Pharmaceutique, Technologie Médicale, BioPharmaceutique

4. **CTA Buttons** ✅
   - Ajout de deux boutons CTA au haut de chaque page secteur
   - Bouton 1 : "Prendre rendez-vous →" (style `.btn-rdv`)
   - Bouton 2 : "Voir nos offres" (style `.btn-ghost`)
   - Alignement vertical optimisé

5. **Sections Missions Réalisées** ✅
   - Contenu remplacé par des exemples réels et secteur-spécifiques
   - **Luxe** : Maroquinerie Haut Gamme, Joaillerie Internationale, etc.
   - **Process** : Industrie Chimique, Agroalimentaire, etc.
   - **Aéronautique** : Constructeur Aéronautique, MRO, etc.
   - **Pharma** : Fabrication Pharmaceutique, Biotechnologie, etc.

## Variables CSS Importantes

```css
--primary-color: #1a1a1a (Noir)
--secondary-color: #f5f5f5 (Gris clair)
--accent-color: (À vérifier dans styles.css)
--font-primary: Arial, sans-serif
--font-secondary: Georgia, serif (pour les titres)
```

## Dépendances

```json
{
  "express": "4.x ou similaire",
  "node": "14+ recommandé"
}
```

## Déploiement Recommandé

### GitHub Pages
```bash
git init
git add .
git commit -m "Initial commit - OPEO website"
git remote add origin https://github.com/your-repo/opeo-site.git
git push -u origin main
```

Configurez dans les paramètres GitHub Pages pour servir depuis `main` branch.

### Netlify
```bash
npm install netlify-cli -g
netlify deploy
```

### Vercel
```bash
npm install vercel -g
vercel
```

## Points d'Attention

⚠️ **IMPORTANT** :
1. Ne pas modifier les chemins des images
2. Ne pas supprimer les fichiers SVG (logos)
3. Tester sur mobile après tout changement
4. Vérifier les liens internes lors du déploiement

## Support & Modifications Futures

Pour ajouter :
- Nouvelles pages : Créer `nom-page.html` et lier depuis le menu de navigation
- Nouvelles images : Les placer dans `photo site internet/` et référencer correctement
- Nouveaux styles : Ajouter dans la balise `<style>` de chaque page ou dans `styles.css`

---

**Mise à jour** : 10 juin 2026  
**Par** : Claude Assistant (OPEO Project)
