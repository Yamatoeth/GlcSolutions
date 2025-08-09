# GLC Solutions - Corporate Website

Un site web moderne et responsive pour GLC Solutions, développé avec React et Tailwind CSS.

## 🚀 Fonctionnalités

- ✅ Design responsive avec menu mobile hamburger
- ✅ Navigation fluide avec scroll smooth
- ✅ Formulaire de contact fonctionnel avec validation
- ✅ Animations et transitions élégantes
- ✅ Optimisé pour l'accessibilité (ARIA, focus)
- ✅ SEO optimisé avec meta tags
- ✅ Performance optimisée

## 🛠 Technologies utilisées

- **React 18** - Framework JavaScript
- **Tailwind CSS** - Framework CSS utilitaire
- **Vite** - Build tool moderne et rapide
- **ESLint** - Linting pour la qualité du code

## 📦 Installation

```bash
# Installer les dépendances
npm install

# Démarrer le serveur de développement
npm run dev

# Construire pour la production
npm run build

# Prévisualiser la build de production
npm run preview
```

## 🎨 Améliorations apportées

### UX/UI
- Menu hamburger responsive pour mobile
- Transitions fluides et animations hover
- Focus states pour l'accessibilité
- Icônes dans les cartes de services
- Footer enrichi avec liens sociaux
- Effets visuels sur les cartes portfolio

### Fonctionnalités
- Formulaire de contact avec gestion d'état
- Validation des champs requis
- États de chargement pour l'envoi
- Navigation mobile optimisée

### Performance & SEO
- Meta tags optimisés
- Preconnect pour les images externes
- Structure HTML sémantique
- Optimisation des images

## 📱 Responsive Design

Le site est entièrement responsive avec des breakpoints optimisés :
- Mobile : < 768px
- Tablet : 768px - 1024px  
- Desktop : > 1024px

## 🔧 Configuration

Le projet utilise :
- Vite pour le build et le développement
- Tailwind CSS pour le styling
- PostCSS pour le traitement CSS
- ESLint pour la qualité du code

## 📝 Structure du projet

```
/
├── src/
│   ├── main.jsx          # Point d'entrée React
│   └── index.css         # Styles Tailwind
├── index.jsx             # Composant principal
├── index.html            # Template HTML
├── vite.config.js        # Configuration Vite
├── tailwind.config.js    # Configuration Tailwind
└── package.json          # Dépendances
```

## 🚀 Déploiement

### Développement local
```bash
npm run build
```

Les fichiers optimisés seront générés dans le dossier `dist/`.

### GitHub Pages

Pour déployer automatiquement sur GitHub Pages :

1. Aller dans les **Settings** du repository
2. Section **Pages** 
3. Source : **GitHub Actions**
4. Le workflow automatique se déclenchera à chaque push sur `main`

Le site sera disponible à : `https://yamatoeth.github.io/GlcSolutions/`

### Déploiement manuel

Vous pouvez aussi déployer manuellement avec :
```bash
npm run build
# Puis upload du dossier dist/ vers votre hébergeur
```

## 🤝 Contribution

1. Fork le projet
2. Créer une branche feature (`git checkout -b feature/amelioration`)
3. Commit les changements (`git commit -m 'Ajout d'une fonctionnalité'`)
4. Push la branche (`git push origin feature/amelioration`)
5. Ouvrir une Pull Request

## 📄 License

Ce projet est sous licence MIT.
