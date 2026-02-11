# Portfolio Minimaliste - Site Web HTML/CSS

## 📋 Description

Site web complet en HTML et CSS pur (sans JavaScript) avec les fonctionnalités suivantes :
- Style minimaliste et élégant
- 5 pages (Accueil, À propos, Galerie, Vidéo, Contact)
- Effet parallaxe sur toutes les pages
- Carrousel de photos en CSS pur
- Vidéo en lecture automatique
- Système de changement de langue FR/EN
- Design 100% responsive
- Charte graphique cohérente

## 📁 Structure des fichiers

```
portfolio/
│
├── index-fr.html          # Page d'accueil (Français)
├── index-en.html          # Page d'accueil (Anglais)
├── about-fr.html          # Page À propos (Français)
├── about-en.html          # Page À propos (Anglais)
├── gallery-fr.html        # Page Galerie avec carrousel (Français)
├── gallery-en.html        # Page Galerie avec carrousel (Anglais)
├── video-fr.html          # Page Vidéo (Français)
├── video-en.html          # Page Vidéo (Anglais)
├── contact-fr.html        # Page Contact (Français)
├── contact-en.html        # Page Contact (Anglais)
├── styles.css             # Fichier CSS principal
└── README.md              # Ce fichier
```

## 🚀 Utilisation

1. **Ouvrir le site** : Double-cliquez sur `index-fr.html` ou `index-en.html` pour démarrer
2. **Navigation** : Utilisez la barre de navigation en haut pour naviguer entre les pages
3. **Changement de langue** : Cliquez sur FR/EN en haut à droite de chaque page

## ✨ Fonctionnalités détaillées

### 1. Effet Parallaxe
- Présent sur toutes les pages
- Utilise des transformations CSS 3D pures
- Crée une profondeur visuelle lors du scroll

### 2. Carrousel (Page Galerie)
- Navigation par flèches gauche/droite
- Navigation par points en bas
- 5 images avec légendes
- Transitions fluides en CSS
- **Aucun JavaScript requis !**

### 3. Vidéo automatique
- Lecture automatique (autoplay)
- En boucle (loop)
- Muet par défaut (muted) pour respecter les bonnes pratiques
- Titre affiché au-dessus

### 4. Changement de langue
- Bouton FR/EN fixe en haut à droite
- Toutes les pages dupliquées en français et anglais
- Navigation maintenue entre les versions linguistiques

### 5. Design Responsive
- Mobile : Menu vertical, grilles en 1 colonne
- Tablette : Adaptations intermédiaires
- Desktop : Affichage optimal sur grand écran

## 🎨 Charte graphique

**Palette de couleurs :**
- Primaire : #1a1a1a (Noir profond)
- Secondaire : #f5f5f5 (Gris clair)
- Accent : #2d2d2d (Gris foncé)
- Texte : #333 (Gris sombre)

**Typographie :**
- Police : Helvetica Neue, Arial, sans-serif
- Titres : Police fine (300), lettres espacées
- Corps de texte : Interligne généreux (1.8)

**Espacement :**
- Sections : 100px de padding vertical
- Grilles : 40-60px d'écart entre les éléments

## 🔧 Personnalisation

### Modifier les couleurs
Dans `styles.css`, modifie les variables CSS au début du fichier :
```css
:root {
    --primary-color: #1a1a1a;
    --secondary-color: #f5f5f5;
    --accent-color: #2d2d2d;
    /* ... */
}
```

### Changer les images
Dans les fichiers HTML, remplace les URLs Unsplash par tes propres images :
```html
<div class="parallax-bg" style="background-image: url('TON_IMAGE.jpg');"></div>
```

### Modifier la vidéo
Dans `video-fr.html` et `video-en.html`, remplace l'URL de la vidéo :
```html
<source src="TON_FICHIER_VIDEO.mp4" type="video/mp4">
```

## 📱 Responsive Breakpoints

- **Mobile** : < 480px
- **Tablette** : 481px - 768px
- **Desktop** : > 768px

## ⚡ Performance

- Images optimisées via Unsplash CDN
- CSS pur (pas de framework lourd)
- Transitions GPU-accélérées
- Chargement minimal

## 📝 Notes importantes

1. **Carrousel CSS pur** : Utilise des input radio cachés et des sélecteurs CSS avancés
2. **Parallaxe** : Fonctionne mieux sur desktop, réduit sur mobile pour les performances
3. **Vidéo** : Format MP4 pour compatibilité maximale
4. **Navigation** : Les liens sont relatifs, le site peut fonctionner localement

## 🎓 Concepts HTML/CSS utilisés

- **Flexbox** : Navigation, footer
- **Grid** : Grilles de fonctionnalités et compétences
- **CSS Variables** : Gestion des couleurs et styles
- **Pseudo-classes** : :hover, :focus, :checked
- **Animations** : @keyframes, transitions
- **Transformations 3D** : Effet parallaxe
- **Media queries** : Design responsive
- **Sélecteurs avancés** : Carrousel CSS

## 🌐 Compatibilité navigateurs

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Opera ✅

## 📌 Améliorations possibles (pour aller plus loin)

- Ajouter un menu hamburger pour mobile (nécessite JavaScript)
- Implémenter un système de formulaire fonctionnel (backend requis)
- Ajouter des animations au scroll (Intersection Observer API)
- Optimiser les images pour différentes tailles d'écran

---

**Projet réalisé en HTML5 et CSS3 pur**
Pas de frameworks, pas de JavaScript, juste du code natif ! 🎯
