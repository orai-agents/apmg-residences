# APMG || Residences

Site web professionnel pour APMG Residences - Foncière familiale spécialisée dans l'acquisition, la transformation et la valorisation de biens haut de gamme à Cannes.

## 🚀 Déploiement sur Vercel (GRATUIT)

### Étape 1 : Préparer le projet

Tous les fichiers sont prêts dans ce dossier.

### Étape 2 : Créer un compte Vercel

1. Allez sur [vercel.com](https://vercel.com)
2. Créez un compte gratuit (avec GitHub, GitLab ou email)

### Étape 3 : Déployer

**Option A : Via GitHub (recommandé)**
1. Créez un nouveau repository sur GitHub
2. Uploadez tous ces fichiers dans le repository
3. Sur Vercel, cliquez "New Project"
4. Importez votre repository GitHub
5. Cliquez "Deploy" (aucune configuration nécessaire)

**Option B : Via CLI Vercel**
```bash
npm install -g vercel
cd apmg-residences
vercel
```

**Option C : Via interface web (drag & drop)**
1. Compressez le dossier en .zip
2. Sur Vercel, utilisez l'option "Import Project"
3. Uploadez le .zip

### Étape 4 : Connecter votre nom de domaine

1. Achetez un domaine sur OVH, Gandi ou Namecheap (environ 12€/an)
2. Dans Vercel, allez dans Settings > Domains
3. Ajoutez votre domaine
4. Configurez les DNS chez votre registrar selon les instructions Vercel

## 📁 Structure du projet

```
apmg-residences/
├── index.html              # Page d'accueil
├── projets.html            # Liste des projets
├── qui-sommes-nous.html    # À propos
├── contact.html            # Contact
├── projet-saint-james.html # Projet 1
├── projet-antinea.html     # Projet 2
├── projet-le-cap.html      # Projet 3
├── projet-le-savoie.html   # Projet 4
├── styles.css              # Styles CSS
├── script.js               # JavaScript
└── images/                 # Dossier images (vide pour l'instant)
```

## ✨ Fonctionnalités

- ✅ Menu fixe semi-transparent
- ✅ Design responsive (mobile + desktop)
- ✅ Formulaire de contact
- ✅ Galeries photos projets
- ✅ SEO optimisé
- ✅ Chargement ultra-rapide
- ✅ 0€ d'hébergement (Vercel gratuit)

## 🎨 Personnalisation

### Changer les images

Les images actuelles utilisent les URLs Wix. Pour de meilleures performances :

1. Téléchargez les images originales depuis le site Wix
2. Placez-les dans le dossier `images/`
3. Remplacez les URLs dans les fichiers HTML

### Modifier les textes

Ouvrez les fichiers .html et modifiez directement le contenu.

### Changer les couleurs

Modifiez les variables CSS dans `styles.css` :

```css
:root {
    --color-bg: #ffffff;
    --color-text: #333333;
    --color-header-bg: rgba(80, 80, 80, 0.3);
}
```

## 📧 Formulaire de contact

Le formulaire affiche actuellement un message de confirmation simple.

Pour l'envoyer par email, utilisez un service gratuit comme :

### EmailJS (recommandé)
1. Créez un compte sur [emailjs.com](https://www.emailjs.com)
2. Configurez un service email
3. Modifiez `script.js` avec vos identifiants EmailJS

### Formspree
1. Créez un compte sur [formspree.io](https://formspree.io)
2. Remplacez le formulaire par leur code

## 💰 Coûts

- ✅ Hébergement Vercel : **0€** (gratuit à vie)
- ✅ Code et développement : **0€**
- 💳 Nom de domaine : ~12€/an (optionnel mais recommandé)

**Total : 12€/an** vs **144€+/an pour Wix !**

## 🔧 Support technique

Pour toute modification ou question, contactez le développeur.

## 📱 Réseaux sociaux

- WhatsApp : +33 (0)6 50 63 91 27
- Instagram : @apmg_residences

---

**Développé par Pauline - OR AI Agents**
Site moderne, rapide et professionnel pour APMG Residences
