# 🚀 GUIDE COMPLET - LE MAS DU LUBERON ROUGE

## 📋 TABLE DES MATIÈRES
1. [Installation et Utilisation](#installation)
2. [Optimisation des Images](#images)
3. [Référencement SEO](#seo)
4. [Déploiement du Site](#deploiement)
5. [Intégration Google Maps](#google-maps)
6. [Maintenance et Mises à Jour](#maintenance)

---

## 📁 INSTALLATION ET UTILISATION {#installation}

### Structure du Projet
```
le-luberon-rouge/
├── index.html          # Page principale
├── css/
│   └── style.css      # Styles du site
├── js/
│   └── main.js        # JavaScript interactif
├── images/
│   ├── hero-bg.jpg    # Image de fond de la hero section
│   ├── villa-exterior.jpg
│   ├── suite1.jpg
│   ├── suite2.jpg
│   ├── chambre-enfants.jpg
│   ├── chambre-double.jpg
│   ├── chambre-modulable1.jpg
│   ├── chambre-modulable2.jpg
│   └── gallery/       # Photos pour la galerie
│       ├── exterior-1.jpg
│       ├── pool-1.jpg
│       ├── salon-1.jpg
│       ├── cuisine-1.jpg
│       ├── chambre-1.jpg
│       └── terrasse-1.jpg
├── sitemap.xml        # Plan du site pour Google
└── robots.txt         # Instructions pour les robots

```

### Première Étape : Ajouter vos Photos

**IMPORTANT** : Pour que le site fonctionne correctement, vous devez ajouter vos photos dans le dossier `images/`.

#### Photos Requises :
1. **hero-bg.jpg** - Photo principale de la villa (format paysage, 1920x1080px minimum)
2. **villa-exterior.jpg** - Vue extérieure de la villa
3. **suite1.jpg**, **suite2.jpg** - Photos des suites parentales
4. **chambre-enfants.jpg** - Photo de la chambre enfants
5. **chambre-double.jpg** - Photo de la chambre double
6. **chambre-modulable1.jpg**, **chambre-modulable2.jpg** - Photos des chambres modulables

#### Photos pour la Galerie (dossier `images/gallery/`) :
- **exterior-1.jpg** - Vue extérieure
- **pool-1.jpg** - Piscine
- **salon-1.jpg** - Salon
- **cuisine-1.jpg** - Cuisine
- **chambre-1.jpg** - Une chambre
- **terrasse-1.jpg** - Terrasse

> **Conseil** : Ajoutez autant de photos que vous le souhaitez dans le dossier `gallery/`. Le site les affichera automatiquement.

---

## 🖼️ OPTIMISATION DES IMAGES {#images}

### Pourquoi Optimiser ?
- Chargement plus rapide du site
- Meilleur référencement Google
- Moins de consommation de données pour les visiteurs

### Outils Gratuits pour Optimiser :

#### 1. **TinyPNG** (Recommandé)
- Site : https://tinypng.com/
- Glissez-déposez vos images
- Téléchargez les versions optimisées
- Réduction de 50-70% de la taille sans perte de qualité

#### 2. **Squoosh** (Google)
- Site : https://squoosh.app/
- Plus de contrôle sur la compression
- Comparaison avant/après en temps réel

#### 3. **ImageOptim** (Mac uniquement)
- Gratuit et très efficace
- Glissez-déposez vos images

### Tailles Recommandées :

| Type d'image | Largeur recommandée | Format | Poids max |
|-------------|-------------------|--------|-----------|
| hero-bg.jpg | 1920px | JPG | 300 KB |
| Photos chambres | 800px | JPG | 150 KB |
| Photos galerie | 1200px | JPG | 200 KB |
| Favicon | 180px | PNG | 20 KB |

### Comment Optimiser vos Photos :

1. **Redimensionner** (si nécessaire)
   - Utilisez Paint (Windows) ou Aperçu (Mac)
   - Ou un outil en ligne : https://www.iloveimg.com/resize-image

2. **Compresser**
   - Téléchargez sur TinyPNG
   - Téléchargez les versions optimisées

3. **Renommer**
   - Utilisez des noms descriptifs : `villa-exterieur-luberon.jpg`
   - Évitez les espaces et accents dans les noms de fichiers

4. **Remplacer**
   - Placez les images optimisées dans le dossier `images/`

---

## 🔍 RÉFÉRENCEMENT SEO - GUIDE COMPLET {#seo}

### Ce qui est déjà fait ✅

Le site est déjà optimisé avec :
- ✅ Meta tags SEO (title, description, keywords)
- ✅ Open Graph (partage Facebook, LinkedIn)
- ✅ Twitter Cards (partage Twitter)
- ✅ Schema.org (données structurées pour Google)
- ✅ Sitemap.xml (plan du site)
- ✅ Robots.txt (instructions pour les robots)
- ✅ Balises HTML sémantiques (h1, h2, article, section)
- ✅ Alt text sur toutes les images
- ✅ URLs propres et descriptives
- ✅ Site responsive (mobile-friendly)

### Actions à Faire Après Déploiement

#### 1. **Google Search Console** (ESSENTIEL)

##### Étape par étape :

1. **Créer un compte**
   - Allez sur : https://search.google.com/search-console/
   - Connectez-vous avec votre compte Google

2. **Ajouter votre propriété**
   - Cliquez sur "Ajouter une propriété"
   - Entrez votre URL : `https://www.leluberonrouge.com`

3. **Vérifier la propriété**
   - Méthode recommandée : Fichier HTML
   - Téléchargez le fichier de vérification
   - Uploadez-le à la racine de votre site
   - Cliquez sur "Vérifier"

4. **Soumettre le sitemap**
   - Dans le menu, cliquez sur "Sitemaps"
   - Ajoutez : `https://www.leluberonrouge.com/sitemap.xml`
   - Cliquez sur "Envoyer"

5. **Demander l'indexation**
   - Dans le menu, cliquez sur "Inspection de l'URL"
   - Entrez votre URL principale
   - Cliquez sur "Demander l'indexation"

#### 2. **Google My Business** (LOCAL SEO)

Vous avez déjà un établissement sur Google Maps ! Optimisons-le :

##### Actions à faire :

1. **Connectez-vous à Google My Business**
   - https://business.google.com/
   - Trouvez votre fiche "Le Mas du Luberon Rouge"

2. **Optimisez votre fiche**
   - ✅ Vérifiez l'adresse : `271H chemin de Saint Ferreol, 84460 Cheval-Blanc`
   - ✅ Ajoutez toutes vos photos (minimum 10 photos de qualité)
   - ✅ Catégorie principale : "Location de vacances" ou "Villa de vacances"
   - ✅ Catégories secondaires : "Hébergement", "Gîte"
   - ✅ Description : Utilisez les mots-clés importants
   - ✅ Horaires : Heures de contact / disponibilité
   - ✅ Site web : Lien vers votre nouveau site
   - ✅ Numéro de téléphone
   - ✅ Attributs : Piscine, WiFi, Parking, Climatisation, etc.

3. **Ajoutez un lien vers votre site**
   - Dans "Informations" → "Site web"
   - Collez l'URL de votre nouveau site

4. **Publiez régulièrement**
   - Utilisez les "Posts" pour annoncer :
     - Disponibilités
     - Promotions
     - Nouveautés
     - Photos saisonnières

5. **Répondez aux avis**
   - Répondez à TOUS les avis (positifs et négatifs)
   - Remerciez les clients
   - Montrez que vous êtes actif

#### 3. **Mots-Clés à Cibler**

##### Mots-clés principaux :
- Location vacances Luberon
- Villa Cheval-Blanc
- Mas Provence piscine
- Location villa Luberon 12 personnes
- Gîte Vaucluse avec piscine
- Maison vacances Luberon
- Location saisonnière Cheval-Blanc

##### Mots-clés longue traîne (plus spécifiques) :
- Location villa 5 chambres Luberon
- Maison vacances piscine privée Provence
- Gîte 12 personnes Cheval-Blanc
- Villa familiale Luberon avec piscine
- Location vacances Vaucluse près Avignon

##### Où les utiliser ?
- ✅ Déjà intégrés dans le code HTML (title, meta description)
- ✅ Dans vos publications Google My Business
- ✅ Dans les descriptions Abritel et PAP Vacances
- ✅ Sur vos réseaux sociaux

#### 4. **Backlinks (Liens Entrants)**

Plus votre site est référencé sur d'autres sites, mieux il sera classé sur Google.

##### Stratégies :

1. **Annuaires de location**
   - ✅ Abritel (déjà fait)
   - ✅ PAP Vacances (déjà fait)
   - Airbnb
   - Booking.com
   - HomeAway
   - TripAdvisor

2. **Offices de tourisme**
   - Office de Tourisme de Cheval-Blanc
   - Luberon Tourisme
   - Vaucluse Tourisme
   - Provence Tourisme

3. **Blogs et sites locaux**
   - Contactez des blogueurs voyage spécialisés Provence
   - Proposez un article invité sur votre région
   - Partenariats avec des sites touristiques locaux

4. **Réseaux sociaux**
   - Partagez votre site sur Facebook
   - Créez un compte Instagram dédié
   - Pinterest (idéal pour les locations de vacances)

#### 5. **Contenu Régulier** (Blog - À ajouter plus tard)

Pour améliorer le référencement à long terme, créez un blog :

##### Idées d'articles :
- "Top 10 des villages à visiter près de Cheval-Blanc"
- "Les meilleurs marchés provençaux du Luberon"
- "Que faire dans le Luberon en famille ?"
- "Routes des vins dans le Vaucluse"
- "Randonnées dans le Luberon : nos coups de cœur"

#### 6. **Performances du Site**

##### Testez votre site :

1. **Google PageSpeed Insights**
   - https://pagespeed.web.dev/
   - Entrez votre URL
   - Objectif : Score > 90/100

2. **Mobile-Friendly Test**
   - https://search.google.com/test/mobile-friendly
   - Vérifiez que votre site est bien optimisé mobile

3. **GTmetrix**
   - https://gtmetrix.com/
   - Analyse détaillée des performances

### Checklist SEO Complète

#### Avant le Déploiement ✅
- [x] Meta tags optimisés
- [x] Schema.org (données structurées)
- [x] Sitemap.xml
- [x] Robots.txt
- [x] Images avec attribut alt
- [x] Responsive design
- [x] URLs propres

#### Après le Déploiement (À FAIRE)
- [ ] Ajouter le site à Google Search Console
- [ ] Soumettre le sitemap à Google
- [ ] Vérifier et optimiser Google My Business
- [ ] Ajouter le site sur Bing Webmaster Tools
- [ ] Installer Google Analytics (optionnel)
- [ ] Demander des avis clients sur Google
- [ ] Créer des backlinks (annuaires, partenaires)
- [ ] Partager sur les réseaux sociaux

---

## 🌐 DÉPLOIEMENT DU SITE {#deploiement}

### Option 1 : Netlify (RECOMMANDÉ - Gratuit et Simple)

#### Avantages :
- ✅ 100% gratuit
- ✅ HTTPS automatique
- ✅ Déploiement en 5 minutes
- ✅ Nom de domaine personnalisé gratuit
- ✅ Performances excellentes

#### Étapes :

1. **Créer un compte**
   - Allez sur : https://www.netlify.com/
   - Cliquez sur "Sign up" (gratuit)

2. **Déployer votre site**
   - **Option A : Drag & Drop (Plus simple)**
     1. Sélectionnez TOUT le contenu du dossier `le-luberon-rouge`
     2. Glissez-déposez sur Netlify
     3. Votre site est en ligne en 30 secondes !
   
   - **Option B : Via GitHub (Plus professionnel)**
     1. Créez un compte GitHub
     2. Créez un nouveau repository
     3. Uploadez vos fichiers
     4. Connectez Netlify à GitHub
     5. Sélectionnez votre repository

3. **Configurer un nom de domaine personnalisé**
   
   **Si vous n'avez PAS encore de nom de domaine :**
   - Netlify vous donne un sous-domaine gratuit : `leluberonrouge.netlify.app`
   - Vous pouvez acheter un domaine plus tard

   **Si vous voulez acheter un nom de domaine :**
   - Achetez sur : https://www.ovh.com/ ou https://www.gandi.net/
   - Nom recommandé : `leluberonrouge.com` ou `leluberonrouge.fr`
   - Prix : 10-15€/an

   **Configuration du domaine personnalisé :**
   1. Dans Netlify, cliquez sur "Domain settings"
   2. Cliquez sur "Add custom domain"
   3. Entrez votre nom de domaine
   4. Suivez les instructions pour configurer les DNS

4. **Activer HTTPS**
   - Netlify active HTTPS automatiquement (certificat SSL gratuit)
   - Attendez quelques minutes après l'ajout du domaine

### Option 2 : GitHub Pages (Gratuit)

#### Avantages :
- ✅ 100% gratuit
- ✅ Simple si vous connaissez GitHub
- ✅ HTTPS gratuit

#### Étapes :

1. **Créer un compte GitHub**
   - https://github.com/
   - Créez un compte gratuit

2. **Créer un nouveau repository**
   - Cliquez sur "New repository"
   - Nom : `le-luberon-rouge`
   - Cochez "Public"
   - Cliquez sur "Create repository"

3. **Uploader vos fichiers**
   - Cliquez sur "uploading an existing file"
   - Glissez-déposez TOUS vos fichiers
   - Cliquez sur "Commit changes"

4. **Activer GitHub Pages**
   - Allez dans "Settings" du repository
   - Scrollez jusqu'à "GitHub Pages"
   - Source : Sélectionnez "main branch"
   - Cliquez sur "Save"

5. **Votre site est en ligne !**
   - URL : `https://VOTRE_NOM_UTILISATEUR.github.io/le-luberon-rouge/`

### Option 3 : Hébergement Classique (OVH, O2Switch, etc.)

Si vous avez déjà un hébergement web :

1. **Connectez-vous à votre hébergeur**
2. **Accédez au FTP** (FileZilla, WinSCP, ou gestionnaire de fichiers)
3. **Uploadez tous les fichiers** à la racine (`www/` ou `public_html/`)
4. **Configurez votre domaine** (si nécessaire)
5. **Votre site est en ligne !**

---

## 🗺️ INTÉGRATION GOOGLE MAPS {#google-maps}

### Récupérer l'ID de votre établissement Google Maps

1. **Trouvez votre fiche Google Maps**
   - Allez sur https://www.google.com/maps/
   - Recherchez "Le Mas du Luberon Rouge Cheval-Blanc"

2. **Récupérez l'URL partageable**
   - Cliquez sur "Partager"
   - Copiez le lien court
   - Exemple : `https://g.page/r/CabcdefGHIJ_kl`

3. **Mettez à jour le site**
   
   Dans le fichier `index.html`, trouvez cette ligne (ligne ~530) :
   ```html
   <a href="https://g.page/r/YOUR_GOOGLE_MAPS_ID" target="_blank" rel="noopener">
   ```
   
   Remplacez `YOUR_GOOGLE_MAPS_ID` par votre lien Google Maps.

### Obtenir une carte intégrée personnalisée

1. **Allez sur Google Maps**
2. **Recherchez votre adresse** : `271H chemin de Saint Ferreol, 84460 Cheval-Blanc`
3. **Cliquez sur "Partager" → "Intégrer une carte"**
4. **Copiez le code HTML**
5. **Remplacez la balise `<iframe>` dans index.html (ligne ~514)**

---

## 🔧 MAINTENANCE ET MISES À JOUR {#maintenance}

### Mises à Jour Régulières

#### Photos
- Ajoutez de nouvelles photos saisonnières (printemps, été, automne, hiver)
- Mettez à jour les photos de la galerie régulièrement

#### Informations
- Vérifiez que les informations sont à jour (tarifs, disponibilités, équipements)
- Mettez à jour le numéro de téléphone et l'email si nécessaire

#### Google My Business
- Publiez des posts mensuellement
- Ajoutez des photos de saison
- Répondez aux avis rapidement

### Suivi des Performances

#### Google Analytics (Optionnel)

Pour suivre le nombre de visiteurs :

1. **Créez un compte Google Analytics**
   - https://analytics.google.com/

2. **Créez une propriété**
   - Nom : "Le Mas du Luberon Rouge"
   - URL du site

3. **Récupérez le code de suivi**
   - Copiez le script fourni

4. **Ajoutez-le au site**
   - Collez le code juste avant `</head>` dans index.html

5. **Analysez vos statistiques**
   - Nombre de visiteurs
   - Pages les plus vues
   - Provenance des visiteurs
   - Durée des visites

### Sauvegardes

- **Sauvegardez régulièrement** tous vos fichiers
- Conservez une copie sur votre ordinateur
- Si vous utilisez GitHub : tout est automatiquement sauvegardé

---

## 📞 CONTACT & PERSONNALISATION

### Informations à Personnaliser

Dans le fichier `index.html`, remplacez :

1. **Numéro de téléphone** (ligne ~530)
   ```html
   <a href="tel:+33XXXXXXXXX">+33 X XX XX XX XX</a>
   ```
   Remplacez par votre vrai numéro.

2. **Email** (ligne ~526)
   ```html
   <a href="mailto:contact@leluberonrouge.com">contact@leluberonrouge.com</a>
   ```
   Utilisez votre email réel.

3. **Coordonnées GPS** (ligne ~58-59)
   ```json
   "latitude": "43.8167",
   "longitude": "5.0500"
   ```
   Vous pouvez obtenir les coordonnées exactes sur Google Maps.

---

## ✅ CHECKLIST FINALE

### Avant le Lancement
- [ ] Toutes les photos sont ajoutées et optimisées
- [ ] Les informations de contact sont à jour
- [ ] Le lien Google Maps est configuré
- [ ] Le site fonctionne correctement (testez sur mobile et desktop)
- [ ] Les liens Abritel et PAP Vacances sont corrects

### Après le Lancement
- [ ] Site déployé sur Netlify ou autre hébergeur
- [ ] Nom de domaine configuré (si applicable)
- [ ] Google Search Console configuré
- [ ] Sitemap soumis à Google
- [ ] Google My Business optimisé et lien vers le nouveau site ajouté
- [ ] Site partagé sur les réseaux sociaux
- [ ] Annonces Abritel et PAP Vacances mises à jour avec le nouveau lien

### Mensuel
- [ ] Vérifier Google Analytics
- [ ] Publier sur Google My Business
- [ ] Ajouter de nouvelles photos
- [ ] Répondre aux avis clients
- [ ] Vérifier les performances du site (PageSpeed)

---

## 🎉 FÉLICITATIONS !

Vous avez maintenant un site web moderne, optimisé pour le référencement et prêt à attirer des clients !

### Besoin d'Aide ?

Si vous avez des questions ou besoin d'assistance :
- Consultez ce guide
- Testez sur https://pagespeed.web.dev/
- Vérifiez sur https://search.google.com/test/mobile-friendly

**Bon courage et bonne chance avec vos locations ! 🏡**
