# 🚀 DÉPLOIEMENT NETLIFY - GUIDE ÉTAPE PAR ÉTAPE

## ❌ Problème : Page Blanche sur Netlify

Votre site https://lemasduluberonrouge.netlify.app/ affiche une page blanche.

**Cause :** Les fichiers n'ont pas été correctement uploadés sur Netlify.

---

## ✅ SOLUTION : Re-déploiement Correct

### Méthode 1 : Netlify Drop (FACILE - 2 MINUTES)

#### ÉTAPE 1 : Ouvrez le bon dossier

1. **Ouvrez l'Explorateur Windows** (icône dossier jaune)

2. **Naviguez vers :**
   ```
   C:\Users\borda\OneDrive\Documents\.git\le-luberon-rouge
   ```

3. **Vous devez voir :**
   ```
   📄 index.html
   📄 sitemap.xml
   📄 robots.txt
   📁 css
   📁 js
   📁 images
   📄 README.md
   📄 GUIDE.md
   (et d'autres fichiers)
   ```

#### ÉTAPE 2 : Sélectionnez TOUT le contenu

1. **Cliquez dans la fenêtre**
2. **Appuyez sur Ctrl + A** (tout sélectionner)
3. **Vous devez voir tous les fichiers et dossiers en surbrillance**

⚠️ **IMPORTANT :** Ne sélectionnez PAS le dossier "le-luberon-rouge" lui-même !
Sélectionnez seulement ce qu'il contient !

#### ÉTAPE 3 : Allez sur Netlify Drop

1. **Ouvrez votre navigateur**
2. **Allez sur :** https://app.netlify.com/drop
3. **Connectez-vous** si nécessaire

#### ÉTAPE 4 : Glissez-Déposez

1. **Gardez la fenêtre de l'Explorateur ouverte**
2. **Glissez tous les fichiers sélectionnés** vers la zone Netlify
3. **Lâchez** quand vous voyez "Drop to upload"

#### ÉTAPE 5 : Attendez le Déploiement

1. **Une barre de progression** apparaît
2. **Attendez** que ça devienne vert
3. **Netlify vous donne un lien** (ex: random-name-12345.netlify.app)

#### ÉTAPE 6 : Personnalisez le Nom (Optionnel)

1. **Cliquez sur** "Site settings"
2. **Cliquez sur** "Change site name"
3. **Entrez :** `lemasduluberonrouge`
4. **Sauvegardez**

Votre site sera accessible sur : https://lemasduluberonrouge.netlify.app

#### ÉTAPE 7 : Testez Votre Site

1. **Ouvrez le lien** donné par Netlify
2. **Appuyez sur Ctrl + F5** (rechargement complet)
3. **Vous devez voir** :
   - Header avec "Le Mas du Luberon Rouge"
   - Grande section hero (bannière)
   - Sections : Villa, Chambres, Équipements, etc.

---

## 🖼️ Illustrations Visuelles

### ❌ ERREUR COURANTE

```
Netlify
└── 📁 le-luberon-rouge
    ├── 📄 index.html
    ├── 📁 css
    └── 📁 js
```
**Résultat :** PAGE BLANCHE ❌

### ✅ BON DÉPLOIEMENT

```
Netlify (racine)
├── 📄 index.html
├── 📁 css
├── 📁 js
├── 📁 images
├── 📄 sitemap.xml
└── 📄 robots.txt
```
**Résultat :** SITE FONCTIONNE ✅

---

## 🔍 Vérifier le Déploiement

### Sur Netlify :

1. **Allez sur** https://app.netlify.com/
2. **Connectez-vous**
3. **Cliquez sur votre site** "lemasduluberonrouge"
4. **Cliquez sur** "Deploys"
5. **Cliquez sur le dernier déploiement** (en haut)
6. **Regardez la liste des fichiers**

### Vous DEVEZ voir à la racine :

```
✅ index.html
✅ sitemap.xml
✅ robots.txt
✅ css/
✅ js/
✅ images/
```

### Vous NE devez PAS voir :

```
❌ le-luberon-rouge/
    └── index.html
    └── css/
    └── ...
```

Si vous voyez un dossier `le-luberon-rouge/` à la racine, c'est FAUX !

---

## 🎥 Procédure en Vidéo (Texte)

**1. Ouvrir l'Explorateur**
→ Touche Windows + E

**2. Aller au bon dossier**
→ C:\Users\borda\OneDrive\Documents\.git\le-luberon-rouge

**3. Sélectionner tout**
→ Ctrl + A

**4. Ouvrir Netlify**
→ https://app.netlify.com/drop (dans un navigateur)

**5. Glisser-Déposer**
→ Faites glisser les fichiers sélectionnés vers Netlify

**6. Attendre**
→ Barre verte = OK !

**7. Tester**
→ Cliquez sur le lien donné
→ Ctrl + F5 pour recharger

---

## 🆘 MÉTHODE ALTERNATIVE : ZIP

Si le glisser-déposer ne fonctionne pas :

### ÉTAPE 1 : Créer un ZIP

1. **Allez dans le dossier** `le-luberon-rouge`
2. **Sélectionnez tout** (Ctrl + A)
3. **Clic droit** sur les fichiers sélectionnés
4. **Choisissez** "Envoyer vers" → "Dossier compressé"
5. **Nommez le ZIP** : `site.zip`

### ÉTAPE 2 : Uploader sur Netlify

1. **Allez sur** https://app.netlify.com/
2. **Cliquez sur** "Sites"
3. **Cliquez sur** "Deploy manually"
4. **Glissez le fichier** `site.zip`
5. **Attendez** le déploiement

⚠️ **IMPORTANT :** Le ZIP doit contenir les fichiers directement, PAS un dossier !

---

## 📞 VÉRIFICATION MANUELLE

### Test 1 : Fichier index.html existe ?

Allez sur : https://lemasduluberonrouge.netlify.app/index.html

- ✅ Si le site s'affiche = index.html est bien là
- ❌ Si erreur 404 = index.html n'est pas déployé

### Test 2 : Fichier CSS existe ?

Allez sur : https://lemasduluberonrouge.netlify.app/css/style.css

- ✅ Si vous voyez du code CSS = fichiers bien déployés
- ❌ Si erreur 404 = structure de dossier incorrecte

### Test 3 : Console Netlify

1. Sur Netlify, cliquez sur "Deploys"
2. Regardez s'il y a des erreurs en rouge
3. Cliquez sur "Deploy log" pour voir les détails

---

## ✅ CHECKLIST DE DÉPLOIEMENT

Avant de déployer :
- [ ] J'ai ouvert le dossier `le-luberon-rouge`
- [ ] J'ai sélectionné TOUT le contenu (pas le dossier lui-même)
- [ ] Je vois bien : index.html, css/, js/, images/, etc.
- [ ] Je ne vois PAS un dossier "le-luberon-rouge" dans ma sélection

Pendant le déploiement :
- [ ] J'ai glissé-déposé sur https://app.netlify.com/drop
- [ ] La barre de progression est verte
- [ ] Netlify me donne un lien

Après le déploiement :
- [ ] J'ai cliqué sur le lien
- [ ] J'ai appuyé sur Ctrl + F5
- [ ] Le site s'affiche correctement
- [ ] J'ai vérifié que index.html est à la racine (Deploys → dernier déploiement)

---

## 🎯 RÉSUMÉ EN 1 MINUTE

1. **Ouvrir :** `C:\Users\borda\OneDrive\Documents\.git\le-luberon-rouge`
2. **Sélectionner tout :** Ctrl + A
3. **Aller sur :** https://app.netlify.com/drop
4. **Glisser-Déposer**
5. **Attendre** (barre verte)
6. **Tester** le lien donné
7. **Ctrl + F5**

**C'EST TOUT !** 🚀

---

## ❓ Questions Fréquentes

### Q : Le site est toujours blanc après déploiement
**R :** Videz le cache : Ctrl + Shift + Delete → Effacer → Ctrl + F5

### Q : Je vois "Page not found"
**R :** Le fichier index.html n'est pas à la racine. Re-déployez correctement.

### Q : Les images ne s'affichent pas
**R :** C'est normal si vous n'avez pas ajouté vos propres photos. Le site fonctionne quand même.

### Q : Ça prend combien de temps ?
**R :** 30 secondes à 2 minutes maximum.

### Q : Je peux modifier le site après ?
**R :** OUI ! Modifiez les fichiers localement et re-déployez.

---

## 🆘 Besoin d'Aide Supplémentaire ?

Si le site est toujours blanc après avoir suivi ce guide :

1. **Prenez une capture d'écran** de :
   - La page Netlify "Deploys"
   - La liste des fichiers déployés
   - Le message d'erreur (s'il y en a)

2. **Vérifiez** :
   - Que vous avez sélectionné le CONTENU du dossier
   - Que index.html apparaît bien dans la liste des fichiers déployés
   - Qu'il n'y a pas de dossier "le-luberon-rouge" dans la structure

3. **Essayez la méthode ZIP** (expliquée ci-dessus)

---

**Suivez ce guide étape par étape et votre site fonctionnera ! 🎉**
