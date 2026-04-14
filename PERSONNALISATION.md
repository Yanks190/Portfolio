# Guide de Personnalisation du Portfolio

## 📁 Structure des Fichiers

```
Portfolio/
├── index.html          ← Page d'accueil (MODIFIER ICI)
├── quiestce.html       ← Page "Qui suis-je" (MODIFIER ICI)
├── projets.html        ← Page des projets (MODIFIER ICI)
├── cv.html             ← Page CV détaillée (MODIFIER ICI)
├── veille.html         ← Page veille technologique (MODIFIER ICI)
├── stage.html          ← Page stage (MODIFIER ICI)
├── navbar.html         ← Navigation (MODIFIER ICI)
├── css/
│   ├── style.css       ← Styles principaux (MODIFIER ICI pour les couleurs)
│   └── cv.css          ← Styles spécifiques au CV
├── js/
│   ├── navbar.js       ← Script navigation
│   ├── main.js         ← Scripts principaux
│   └── projects.js     ← Filtrage des projets
└── images/
    └── CV.pdf          ← Votre CV en PDF (REMPLACER ICI)
```

## 🎨 Modifier les Couleurs

**Fichier : `css/style.css`** (lignes 7-15)

```css
:root {
    --primary-color: #6366f1;      /* Couleur principale (bleu/violet) */
    --secondary-color: #8b5cf6;    /* Couleur secondaire */
    --accent-color: #ec4899;       /* Couleur d'accent */
    --text-dark: #1f2937;          /* Texte sombre */
    --text-light: #6b7280;         /* Texte clair */
}
```

## 📝 Fichiers à Personnaliser

### 1. **index.html** - Page d'Accueil
- Ligne 18-19 : Titre et sous-titre hero
- Ligne 21 : Bouton "Voir mes projets"
- Ligne 22 : Lien téléchargement CV
- Ligne 38-41 : Texte "À propos"
- Lignes 72-111 : Cartes de projets (3 projets)
- Lignes 109-124 : Section contact (email, téléphone, réseaux)

### 2. **quiestce.html** - Qui suis-je
- Personnaliser votre parcours
- Ajouter vos compétences
- Modifier vos passions

### 3. **projets.html** - Projets
- Ajouter vos vrais projets
- Modifier les descriptions
- Ajouter des images dans `images/`
- Changer les technologies utilisées

### 4. **cv.html** - CV
- Lignes 37-38 : Nom et titre
- Lignes 43-47 : Coordonnées
- Lignes 54-75 : Formation
- Lignes 78-103 : Expérience professionnelle
- Lignes 106-132 : Compétences techniques
- Lignes 135-139 : Langues

### 5. **veille.html** - Veille Technologique
- Ajouter vos sources de veille
- Modifier les articles
- Personnaliser les sujets suivis

### 6. **stage.html** - Stage
- Informations entreprise
- Missions réalisées
- Technologies utilisées
- Compétences acquises

### 7. **navbar.html** - Navigation
- Ligne 4 : Nom dans le logo
- Lignes 8-27 : Liens de navigation

### 8. **images/CV.pdf**
- ⚠️ **REMPLACER** par votre propre CV en PDF

## 🖼️ Ajouter des Images

Placez vos images dans le dossier `images/` :
- Photo de profil : `images/profil.jpg`
- Images de projets : `images/projet1.jpg`, etc.
- Logo entreprise : `images/logo-entreprise.png`

## 🔗 Modifier les Liens

- **Réseaux sociaux** : Modifier les liens dans `index.html` (lignes 119, 123)
- **GitHub** : Ajouter vos liens GitHub dans les projets
- **Email** : Changer `email@example.com` partout

## 🚀 Pour Tester Localement

```bash
cd /home/test/Portfolio
python3 -m http.server 8000
```

Puis ouvrez : `http://localhost:8000/index.html`

## 💡 Astuces

1. **Couleurs** : Utilisez un outil comme [Coolors.co](https://coolors.co) pour choisir une palette
2. **Responsive** : Le design est déjà responsive, testez sur mobile
3. **SEO** : Modifiez les balises `<meta>` dans chaque fichier HTML
4. **Favicon** : Ajoutez `favicon.ico` dans la racine

## 📦 Déploiement

Pour mettre en ligne :
- **GitHub Pages** : Gratuit et simple
- **Netlify** : Glisser-déposer le dossier
- **Vercel** : Connecter votre repo GitHub

---

**Tous les fichiers sont maintenant dans Visual Studio Code !**
Modifiez-les comme vous le souhaitez ! 🎨

