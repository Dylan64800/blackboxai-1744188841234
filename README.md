# Lumina Beauté - Site Vitrine

## 🚀 Fonctionnalités
- Page d'accueil responsive avec Tailwind CSS
- Design élégant et moderne
- Optimisé pour le SEO
- Configuration prête pour la production

## 🛠 Installation développement
```bash
# 1. Cloner le dépôt
git clone https://github.com/votre-repo/lumina-beaute.git

# 2. Ouvrir dans le navigateur
open index.html  # ou python3 -m http.server 8000
```

## ⚡ Migration vers Tailwind en production
1. Installer les dépendances :
```bash
npm install -D tailwindcss postcss autoprefixer
```

2. Générer le CSS optimisé :
```bash
npx tailwindcss -i src/input.css -o dist/output.css --minify
```

## 📁 Structure
```
.
├── index.html          # Page principale
├── tailwind.config.js  # Configuration Tailwind
├── postcss.config.js   # Configuration PostCSS
├── src/
│   └── input.css       # CSS d'entrée
└── dist/
    └── output.css      # CSS de production
```

## 📝 Notes
- Le site utilise actuellement le CDN Tailwind en développement
- Pour la production, utiliser la version locale générée
