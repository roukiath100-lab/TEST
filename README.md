# MG Consulting Group - Site Web

Site web professionnel pour MG Consulting Group, cabinet de conseil en Analyse Financière, Stratégie et Intelligence Économique en Afrique de l'Ouest.

## Fonctionnalités

- Design moderne et corporate avec palette Bleu Roi + Or/Sable
- Navigation fluide avec menu responsive
- 5 sections principales :
  - Accueil (Hero + Présentation)
  - Nos Expertises (5 piliers détaillés)
  - Notre Approche
  - Ressources & Veille
  - Contact avec formulaire
- Bouton WhatsApp flottant pour contact direct
- Animations et effets visuels modernes
- Totalement responsive (mobile, tablette, desktop)

## Installation

Aucune installation requise ! Il suffit d'ouvrir le fichier `index.html` dans votre navigateur.

### Méthode 1 : Double-clic
Double-cliquez sur le fichier `index.html`

### Méthode 2 : Serveur local (recommandé)
Si vous avez Python installé :
```bash
# Python 3
python -m http.server 8000

# Puis ouvrez http://localhost:8000 dans votre navigateur
```

## Structure des fichiers

```
website/
├── index.html      # Page principale
├── styles.css      # Styles CSS
├── script.js       # JavaScript pour interactivité
└── README.md       # Ce fichier
```

## Personnalisation

### Couleurs
Les couleurs sont définies dans `styles.css` via des variables CSS :
- `--bleu-roi`: #1e3a8a (Couleur principale)
- `--or`: #d4af37 (Couleur accent)
- `--sable`: #f4e4c1 (Couleur secondaire)

### Contacts
Les informations de contact sont dans `index.html` :
- Email: abdelamad@yahoo.com
- Téléphone France: +33 06 02 86 97 48
- WhatsApp Bénin: +229 61 01 28 14

### Formulaire de contact
Le formulaire redirige vers WhatsApp avec un message pré-rempli. Pour utiliser un système d'envoi d'email, vous devrez ajouter un backend (PHP, Node.js, etc.)

## Technologies utilisées

- HTML5
- CSS3 (avec variables CSS et animations)
- JavaScript Vanilla (pas de dépendances)
- Google Fonts (Montserrat + Playfair Display)
- SVG pour les icônes

## Compatibilité

- Chrome, Firefox, Safari, Edge (versions récentes)
- Responsive : Mobile, Tablette, Desktop
- Pas besoin de connexion internet (sauf pour les polices Google Fonts)

## Support

Pour toute question : abdelamad@yahoo.com
