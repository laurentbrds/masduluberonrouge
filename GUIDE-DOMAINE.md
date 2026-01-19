# 🌐 GUIDE : Nom de Domaine Personnalisé

## 🎯 Situation Actuelle

**Votre site Netlify :** `https://lemasduluberonrouge.netlify.app/`

**Objectif :** Avoir une URL courte comme `leluberonrouge.com`

---

## ✅ OPTION 1 : Garder l'URL Netlify (GRATUIT)

### Avantages
- 100% gratuit
- Fonctionne immédiatement
- Parfaitement valide pour Google
- HTTPS automatique

### Pour Google Search Console

Utilisez cette URL exacte :
```
https://lemasduluberonrouge.netlify.app/
```

**Pas besoin de domaine personnalisé pour être référencé sur Google !**

---

## 💰 OPTION 2 : Acheter un Domaine (10-15€/an)

### Où Acheter ?

#### OVH (Recommandé - Français)
- Site : https://www.ovh.com/fr/
- Prix : 8-12€/an
- Support en français
- Interface simple

#### Gandi (Français)
- Site : https://www.gandi.net/fr
- Prix : 12-15€/an
- Très bonne réputation
- Support excellent

#### Namecheap (International)
- Site : https://www.namecheap.com/
- Prix : 8-10€/an
- En anglais
- Moins cher

---

## 📝 Étape par Étape : Acheter et Configurer

### ÉTAPE 1 : Vérifier la Disponibilité

1. Allez sur OVH ou Gandi
2. Cherchez : `leluberonrouge`
3. Vérifiez les extensions disponibles :
   - `.com` (international)
   - `.fr` (France)
   - `.net` (alternatif)

### ÉTAPE 2 : Acheter le Domaine

1. Ajoutez au panier
2. Créez un compte
3. Payez (carte bancaire ou PayPal)
4. Vous recevrez un email de confirmation

**⏰ Temps de propagation :** 24-48h pour que le domaine soit actif

---

### ÉTAPE 3 : Connecter à Netlify

#### Sur Netlify :

1. **Connectez-vous** à https://app.netlify.com/
2. **Cliquez** sur votre site
3. **Allez dans** "Domain settings"
4. **Cliquez** sur "Add custom domain"
5. **Entrez** votre domaine : `leluberonrouge.com`
6. **Cliquez** sur "Verify"

Netlify vous donnera des informations DNS à configurer.

---

#### Sur OVH (ou votre registrar) :

1. **Connectez-vous** à votre compte OVH
2. **Allez dans** "Noms de domaine"
3. **Cliquez** sur votre domaine
4. **Allez dans** "Zone DNS"
5. **Ajoutez** les enregistrements fournis par Netlify

**Enregistrements à ajouter :**

Pour `leluberonrouge.com` :
```
Type : A
Nom : @
Valeur : 75.2.60.5
```

Pour `www.leluberonrouge.com` :
```
Type : CNAME
Nom : www
Valeur : lemasduluberonrouge.netlify.app
```

---

#### Retour sur Netlify :

1. Attendez 5-10 minutes
2. Netlify vérifie automatiquement
3. HTTPS s'active automatiquement (certificat SSL gratuit)
4. Votre site est accessible sur `leluberonrouge.com` !

---

## 🔍 Google Search Console avec Domaine Personnalisé

### Si vous achetez un domaine

1. Attendez que le domaine soit actif (24-48h)
2. Allez sur Google Search Console
3. Ajoutez `https://leluberonrouge.com`
4. Vérifiez avec la balise HTML ou le fichier

**Important :** Ajoutez aussi les 2 versions :
- `https://leluberonrouge.com`
- `https://www.leluberonrouge.com`

---

## 🎯 Recommandation pour Vous

### Pour Commencer (Maintenant)

✅ **Utilisez l'URL Netlify** : `lemasduluberonrouge.netlify.app`
- Configurez Google Search Console avec cette URL
- Mettez cette URL sur Abritel, PAP Vacances, Google My Business
- Commencez à recevoir des visiteurs

### Plus Tard (Quand vous voulez)

💰 **Achetez un domaine** : `leluberonrouge.com`
- Choisissez un moment où vous êtes disponible
- Configurez tranquillement
- Google fera automatiquement la redirection

**Vous ne perdrez RIEN en référencement si vous changez d'URL plus tard !**

---

## ❓ Questions Fréquentes

### Q : Dois-je acheter un domaine tout de suite ?
**R :** NON ! L'URL Netlify fonctionne parfaitement. Achetez un domaine plus tard si vous voulez.

### Q : Google référence les sites .netlify.app ?
**R :** OUI ! Google référence tous les sites, peu importe l'URL.

### Q : Si j'achète un domaine plus tard, je perds mon référencement ?
**R :** NON ! Google suivra automatiquement la redirection.

### Q : Combien coûte un domaine ?
**R :** 8-15€ par AN (pas par mois).

### Q : Puis-je changer de domaine ensuite ?
**R :** OUI, mais ce n'est pas recommandé (perte de référencement).

---

## ✅ Configuration Google Search Console MAINTENANT

### Utilisez l'URL Netlify

1. Allez sur https://search.google.com/search-console/
2. Cliquez sur "Ajouter une propriété"
3. Choisissez "Préfixe d'URL"
4. Entrez : `https://lemasduluberonrouge.netlify.app/`
5. Choisissez la méthode "Balise HTML"
6. Copiez le code
7. Ouvrez `index.html`
8. Ajoutez le code dans la section `<head>` (après ligne 4)
9. Sauvegardez
10. Re-déployez sur Netlify
11. Retournez sur Google Search Console
12. Cliquez "Vérifier"

**✅ C'EST TOUT ! Votre site sera référencé sur Google !**

---

## 📊 Après la Vérification

### Dans Google Search Console :

1. **Soumettez le sitemap**
   - Cliquez sur "Sitemaps"
   - Ajoutez : `https://lemasduluberonrouge.netlify.app/sitemap.xml`
   - Cliquez "Envoyer"

2. **Demandez l'indexation**
   - Cliquez sur "Inspection de l'URL"
   - Entrez : `https://lemasduluberonrouge.netlify.app/`
   - Cliquez sur "Demander l'indexation"

3. **Attendez 3-7 jours**
   - Google va explorer votre site
   - Vous commencerez à apparaître dans les résultats de recherche

---

## 🎉 Résumé

### Maintenant
- ✅ Configurez Google Search Console avec `lemasduluberonrouge.netlify.app`
- ✅ Soumettez votre sitemap
- ✅ Commencez le référencement

### Plus Tard (Optionnel)
- 💰 Achetez `leluberonrouge.com` (ou .fr)
- 🔧 Configurez le domaine sur Netlify
- 🔄 Mettez à jour Google Search Console

**Vous n'avez PAS besoin d'un domaine personnalisé pour être sur Google !**

---

**Besoin d'aide pour configurer Google Search Console ? Suivez le guide ci-dessus ! 🚀**
