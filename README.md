# Portfolio Web

Site web portfolio professionnel inspiré de la structure du portfolio [zinedineamor](https://github.com/zinedineamor/portfolio).

## Structure du Projet

```
Portfolio/
├── index.html          # Page d'accueil
├── quiestce.html       # Page "Qui suis-je"
├── projets.html        # Page des projets
├── cv.html             # Page CV
├── veille.html         # Page veille technologique
├── stage.html          # Page stage
├── navbar.html         # Navigation réutilisable
├── css/
│   ├── style.css       # Styles principaux
│   └── cv.css          # Styles spécifiques au CV
├── js/
│   ├── navbar.js       # Gestion de la navigation
│   ├── main.js         # Scripts principaux
│   └── projects.js     # Filtrage des projets
└── images/             # Dossier pour les images
```

## Fonctionnalités

- **Design moderne et responsive** : Interface adaptée à tous les écrans
- **Navigation fluide** : Menu de navigation avec hamburger sur mobile
- **Filtrage de projets** : Système de filtres pour les projets
- **Animations** : Transitions et animations au scroll
- **Pages complètes** : 
  - Accueil avec présentation
  - Qui suis-je avec compétences
  - Projets avec filtres
  - CV détaillé
  - Veille technologique
  - Stage et expériences

## Personnalisation

### Modifier les couleurs
Éditez les variables CSS dans `css/style.css` :
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... */
}
```

### Ajouter vos projets
Modifiez `projets.html` pour ajouter vos projets dans la section `.projects-container`.

### Modifier les informations personnelles
- **index.html** : Section hero et contact
- **quiestce.html** : Informations personnelles
- **cv.html** : Curriculum vitae complet

## Utilisation

1. Ouvrez `index.html` dans votre navigateur
2. Ou utilisez un serveur local :
   ```bash
   # Avec Python
   python -m http.server 8000
   
   # Avec Node.js (http-server)
   npx http-server
   ```

## Technologies Utilisées

- HTML5
- CSS3 (Variables CSS, Grid, Flexbox)
- JavaScript (Vanilla)
- Font Awesome (Icônes)

## Notes

- Les images doivent être ajoutées dans le dossier `images/`
- Personnalisez les liens sociaux dans les sections contact
- Ajoutez vos propres projets et expériences

## Licence

Libre d'utilisation et de modification.

