# Mon Portfolio - CV en ligne

Portfolio personnel hébergé sur GitHub Pages.

## 🚀 Déploiement sur GitHub Pages

### Étapes pour publier votre site :

1. **Créer un repository GitHub**
   - Allez sur GitHub et créez un nouveau repository
   - Nommez-le `votre-username.github.io` (pour un site personnel)
   - Ou utilisez n'importe quel nom pour un site de projet

2. **Initialiser Git et pousser le code**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/votre-username/nom-du-repo.git
   git push -u origin main
   ```

3. **Activer GitHub Pages**
   - Allez dans les Settings du repository
   - Descendez jusqu'à "Pages"
   - Dans "Source", sélectionnez la branche `main` et le dossier `/ (root)`
   - Cliquez sur "Save"
   - Votre site sera disponible à : `https://votre-username.github.io/nom-du-repo/`

## 📝 Personnalisation

### Contenu à modifier :

1. **index.html**
   - Remplacez "Votre Nom" par votre nom
   - Modifiez les descriptions de sections
   - Ajoutez vos expériences professionnelles
   - Complétez vos projets
   - Mettez à jour vos informations de contact
   - Changez les liens des réseaux sociaux

2. **Images**
   - Créez un dossier `images/`
   - Ajoutez votre photo de profil : `images/profile.jpg`
   - Ajoutez des captures d'écran de vos projets : `images/project1.jpg`, etc.

3. **Couleurs et style**
   - Modifiez les variables CSS dans `css/style.css` (section `:root`)
   - Personnalisez les couleurs, polices, etc.

## 📁 Structure du projet

```
my_page/
├── index.html          # Page principale
├── css/
│   └── style.css      # Styles CSS
├── js/
│   └── script.js      # JavaScript interactif
├── images/            # Vos images (à créer)
│   ├── profile.jpg
│   ├── project1.jpg
│   ├── project2.jpg
│   └── project3.jpg
└── README.md          # Ce fichier
```

## 🎨 Fonctionnalités

- ✅ Design responsive (mobile, tablette, desktop)
- ✅ Navigation smooth scroll
- ✅ Animations au scroll
- ✅ Section À propos
- ✅ Compétences
- ✅ Timeline d'expérience
- ✅ Portfolio de projets
- ✅ Formulaire de contact
- ✅ Liens réseaux sociaux

## 🔧 Technologies utilisées

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- JavaScript (Vanilla)
- Font Awesome (icônes)

## 📱 Responsive

Le site s'adapte automatiquement à tous les écrans :
- Desktop (> 768px)
- Tablette (768px - 480px)
- Mobile (< 480px)

## 💡 Conseils

- Utilisez des images optimisées (format WebP, compression)
- Ajoutez un favicon personnalisé
- Testez votre site sur différents navigateurs
- Utilisez Google Analytics pour suivre les visites
- Ajoutez un fichier CNAME si vous utilisez un domaine personnalisé

## 📞 Support

Pour toute question sur la mise en place de GitHub Pages :
- [Documentation GitHub Pages](https://docs.github.com/fr/pages)
- [Guide complet GitHub Pages](https://pages.github.com/)

---

Bon courage avec votre portfolio ! 🚀
