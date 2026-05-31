# Borgen Industries – Site Web

Site officiel de **Borgen Industries**, fabricant de peintures en poudre (powder coating) au Maroc.

## 🌐 URL du site en ligne
**https://keurtiamine.github.io/borgen**

## 📁 Structure
```
borgen/
└── index.html    ← fichier unique, tout le site est dedans
```

## 🚀 Déploiement sur GitHub Pages (3 étapes)

1. **Créer le repo** sur github.com avec le nom exact **`borgen`**
2. **Uploader** uniquement ce fichier `index.html`
3. Aller dans **Settings → Pages → Branch: main → Save**

Le site sera disponible sur : `https://keurtiamine.github.io/borgen`

## 📄 Pages incluses
- Accueil
- Produits (6 gammes)
- Finitions & Couleurs (palette RAL + effets)
- Applications (6 secteurs)
- Certifications (ISO 9001 + qualité)
- Devis en ligne
- Contact

## ✏️ Personnalisation rapide

### Ajouter votre vrai logo
Remplacer dans `index.html` la section `.logo` par :
```html
<img src="logo.png" alt="Borgen" height="40"/>
```
Et uploader votre logo dans le repo.

### Connecter le formulaire de devis (recevoir les emails)
1. Aller sur [formspree.io](https://formspree.io) → créer un compte gratuit
2. Créer un formulaire → copier votre ID (ex: `xpzgkqab`)
3. Dans `index.html`, trouver `<button class="btn-primary form-submit">` et l'entourer de :
```html
<form action="https://formspree.io/f/VOTRE_ID" method="POST">
  ...boutons et champs...
</form>
```

## 📞 Contact Borgen
177, Ecoparc de Berrechid | +212 521 155 055 | info@borgen.ma
