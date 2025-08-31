# 📄 CV - Projet Portfolio Personnel

Un CV moderne et responsive créé avec HTML5, SCSS et CSS Grid pour présenter un profil professionnel de manière élégante.

## ✨ Fonctionnalités

- **Design moderne** : Interface épurée et professionnelle
- **Responsive** : S'adapte parfaitement à tous les écrans
- **CSS Grid** : Layout avancé avec CSS Grid pour une structure flexible
- **SCSS** : Architecture modulaire avec variables et mixins
- **Animations** : Effets visuels subtils et élégants
- **Typographie** : Police Google Fonts (Muli) pour une meilleure lisibilité
- **Icônes** : Intégration FontAwesome pour les éléments visuels

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique et accessible
- **SCSS/Sass** : Préprocesseur CSS avec architecture modulaire
- **CSS3** : Grid Layout, Flexbox, Variables CSS, Animations
- **Responsive Design** : Media queries pour l'adaptation mobile
- **Parcel** : Bundler pour le développement (mentionné dans le code)

## 📁 Structure du projet

```
CV/
├── scss/                    # Fichiers SCSS source
│   ├── _animations.scss     # Animations et keyframes
│   ├── _base.scss          # Styles de base
│   ├── _classes.scss       # Classes utilitaires
│   ├── _media_queries.scss # Media queries responsive
│   ├── _reset.scss         # Reset CSS
│   ├── _utils.scss         # Utilitaires et helpers
│   ├── variables.scss      # Variables SCSS
│   └── style.scss          # Fichier principal SCSS
├── css/                    # CSS compilé
├── img/                    # Images du projet
├── index.html              # Page principale
└── package.json            # Configuration du projet
```

## 🚀 Installation et utilisation

### Prérequis
- Node.js (version 14 ou supérieure)
- npm ou yarn

### Installation
1. Clonez le repository :
```bash
git clone [URL_DU_REPO]
cd CV
```

2. Installez les dépendances :
```bash
npm install
```

### Développement
Pour démarrer le mode développement avec compilation SCSS en temps réel :
```bash
npm run sass
```

### Build de production
Pour compiler le SCSS en CSS optimisé :
```bash
npm run sass:build
```

## 🎨 Architecture SCSS

Le projet utilise une architecture SCSS modulaire et bien organisée :

- **Variables** : Définition centralisée des couleurs, espacements et typographie
- **Reset** : Normalisation des styles par défaut du navigateur
- **Base** : Styles de base pour les éléments HTML
- **Classes** : Classes utilitaires réutilisables
- **Animations** : Keyframes et transitions
- **Media Queries** : Gestion responsive centralisée
- **Utils** : Fonctions et mixins utilitaires

## 📱 Responsive Design

Le CV s'adapte automatiquement à différentes tailles d'écran :
- **Desktop** : Layout en grille avec sidebar et contenu principal
- **Mobile** : Layout vertical optimisé pour les petits écrans
- **Tablet** : Adaptation intermédiaire entre desktop et mobile

## 🎯 Sections du CV

- **Header** : Nom et titre professionnel avec dégradé
- **Photo** : Image de profil circulaire
- **Sidebar** : Informations de contact, éducation, compétences, langues et réseaux sociaux
- **Main** : Profil professionnel et expérience
- **Footer** : Informations complémentaires

## 🔧 Personnalisation

Pour personnaliser le CV :

1. **Modifiez le contenu** dans `index.html`
2. **Ajustez les couleurs** dans `scss/variables.scss`
3. **Modifiez les animations** dans `scss/_animations.scss`
4. **Adaptez le responsive** dans `scss/_media_queries.scss`

## 📝 Scripts disponibles

- `npm run sass` : Compilation SCSS en mode watch
- `npm run sass:build` : Build de production optimisé

## 🤝 Contribution

Ce projet est ouvert aux contributions. N'hésitez pas à :
- Signaler des bugs
- Proposer des améliorations
- Soumettre des pull requests

## 📄 Licence

Ce projet est sous licence ISC.

## 👨‍💻 Auteur

**Khaled** - Développeur web passionné

---

*Projet créé dans le cadre de la formation Dyma - HTML & CSS*
