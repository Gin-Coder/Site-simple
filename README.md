# Gincoder Multi-Service - Site Web Vitrine

Site web vitrine professionnel pour présenter les services de création de sites web et QR codes personnalisés.

## 🚀 Déploiement sur GitHub Pages

### Méthode 1 : Via l'interface GitHub
1. Créez un nouveau repository sur GitHub
2. Uploadez tous les fichiers du projet
3. Allez dans **Settings** > **Pages**
4. Sélectionnez la branche `main` (ou `master`) comme source
5. Le site sera disponible à l'adresse : `https://votre-username.github.io/nom-du-repo/`

### Méthode 2 : Via Git en ligne de commande
```bash
git init
git add .
git commit -m "Initial commit - Site Gincoder Multi-Service"
git branch -M main
git remote add origin https://github.com/votre-username/nom-du-repo.git
git push -u origin main
```

Puis activez GitHub Pages dans les paramètres du repository.

## 📁 Structure du projet

```
projet_vente/
├── index.html          # Page principale
├── style.css           # Styles CSS
├── script.js           # JavaScript pour interactions
├── README.md           # Ce fichier
└── assets/
    └── logo.svg        # Logo du service
```

## 🖼️ Images

Les images utilisées proviennent d'Unsplash (libres de droits). Si vous souhaitez utiliser vos propres images :

1. Placez vos images dans le dossier `assets/`
2. Mettez à jour les chemins dans `index.html` :
   - `hero-business.jpg` → Image pour la section hero
   - `qr-scan.jpg` → Image de personne scannant un QR code
   - `smartphone-interaction.jpg` → Image d'interaction avec smartphone

### Remplacement des images Unsplash

Actuellement, les images sont chargées depuis Unsplash. Pour utiliser des images locales :

1. Téléchargez les images dans `assets/`
2. Remplacez les URLs dans `index.html` par les chemins relatifs :
   ```html
   <!-- Avant -->
   <img src="https://images.unsplash.com/photo-..." alt="...">
   
   <!-- Après -->
   <img src="assets/hero-business.jpg" alt="...">
   ```

## 🎨 Personnalisation

### Couleurs
Les couleurs principales sont définies dans `style.css` via les variables CSS :
- `--color-primary` : Vert WhatsApp (#25D366)
- `--color-dark` : Noir (#1F1F1F)
- `--color-white` : Blanc (#FFFFFF)

### Contenu
Modifiez le contenu directement dans `index.html` :
- Textes des sections
- Coordonnées de contact
- Lien WhatsApp (actuellement : 50933377934)

## 📱 Responsive

Le site est entièrement responsive et optimisé pour :
- Mobile (320px+)
- Tablette (768px+)
- Desktop (968px+)

## ⚡ Performance

- Images avec lazy loading
- CSS et JavaScript minifiables
- Pas de dépendances externes lourdes
- Fonts Google optimisées avec preconnect

## 📝 Notes

- Le bouton "Commander le service" dans la hero section fait défiler jusqu'à la section CTA
- Le bouton WhatsApp ouvre directement WhatsApp avec un message pré-rempli
- Toutes les animations sont légères pour une meilleure performance

## 📄 Licence

Ce projet est créé pour Gincoder Multi-Service. Tous droits réservés.

