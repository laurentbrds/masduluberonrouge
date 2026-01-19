# 📸 GUIDE : Ajouter des Photos à la Galerie

## ✅ Bonne Nouvelle : PAS DE LIMITE !

Vous pouvez ajouter **autant de photos que vous voulez** dans la galerie !

J'ai déjà mis 22 photos dans le code comme exemple. Vous pouvez en ajouter 50, 100, ou plus !

---

## 🎯 Comment Ajouter une Photo

### Méthode Simple (Copier-Coller)

1. **Ouvrez `index.html`** avec Notepad ou un éditeur de texte

2. **Trouvez la section galerie** (cherchez `<!-- AJOUTEZ ICI VOS PROPRES PHOTOS`)

3. **Copiez ce modèle :**

```html
<div class="gallery-item" data-category="CATEGORIE">
    <img src="images/gallery/NOM-DE-VOTRE-PHOTO.jpg" alt="Description de la photo" loading="lazy">
    <div class="gallery-overlay">
        <span>Titre affiché</span>
    </div>
</div>
```

4. **Personnalisez :**
   - Remplacez `CATEGORIE` par : `pool`, `exterior`, `interior`, `bedroom`, `bathroom`
   - Remplacez `NOM-DE-VOTRE-PHOTO.jpg` par le nom de votre fichier
   - Remplacez `Description de la photo` par une vraie description
   - Remplacez `Titre affiché` par le texte qui apparaîtra sur l'image

5. **Sauvegardez** le fichier

---

## 📋 Exemple Concret

### Vous voulez ajouter une photo de votre piscine nommée `piscine-vue-ciel.jpg`

**Ajoutez ce code dans la galerie :**

```html
<div class="gallery-item" data-category="pool">
    <img src="images/gallery/piscine-vue-ciel.jpg" alt="Piscine avec reflet du ciel bleu" loading="lazy">
    <div class="gallery-overlay">
        <span>Piscine vue d'en haut</span>
    </div>
</div>
```

---

## 🗂️ Liste des Photos Actuelles (22 photos)

Voici les photos déjà dans le code (vous devez ajouter ces fichiers dans `images/gallery/`) :

### Extérieur (6 photos)
- `exterior-1.jpg`
- `exterior-2.jpg`
- `exterior-3.jpg`
- `terrasse-1.jpg`
- `terrasse-2.jpg`
- `cuisine-ete.jpg`

### Piscine (3 photos)
- `pool-1.jpg`
- `pool-2.jpg`
- `pool-3.jpg`

### Intérieur (4 photos)
- `salon-1.jpg`
- `salon-2.jpg`
- `cuisine-1.jpg`
- `cuisine-2.jpg`

### Chambres (5 photos)
- `chambre-1.jpg`
- `chambre-2.jpg`
- `chambre-3.jpg`
- `chambre-4.jpg`
- `chambre-5.jpg`

### Salles de bain (2 photos)
- `salle-bain-1.jpg`
- `salle-bain-2.jpg`

### Ambiance (2 photos)
- `detail-1.jpg`
- `coucher-soleil.jpg`

---

## 🎨 Catégories Disponibles

Utilisez ces catégories dans `data-category=""` :

- **`exterior`** - Vues extérieures, façade, jardin
- **`pool`** - Piscine, transats, plage immergée
- **`interior`** - Salon, salle à manger, cuisine
- **`bedroom`** - Chambres
- **`bathroom`** - Salles de bain, salles d'eau
- **`detail`** - Détails de décoration
- **`ambiance`** - Photos d'ambiance, coucher de soleil

---

## 📝 Noms de Fichiers Recommandés

### Bonnes Pratiques :
✅ `piscine-coucher-soleil.jpg`
✅ `chambre-parentale-principale.jpg`
✅ `terrasse-repas-exterieur.jpg`

### À Éviter :
❌ `IMG_1234.jpg` (pas descriptif)
❌ `Ma Photo.jpg` (espaces et majuscules)
❌ `piscine été 2025.jpg` (caractères spéciaux et espaces)

---

## 🚀 Processus Complet

### 1. Préparez vos Photos
- [ ] Renommez vos photos (sans espaces, sans accents)
- [ ] Compressez-les avec https://tinypng.com/
- [ ] Placez-les dans `le-luberon-rouge/images/gallery/`

### 2. Ajoutez-les au Code
- [ ] Ouvrez `index.html`
- [ ] Cherchez `<!-- AJOUTEZ ICI VOS PROPRES PHOTOS`
- [ ] Copiez-collez le modèle pour chaque photo
- [ ] Personnalisez chaque bloc
- [ ] Sauvegardez

### 3. Testez
- [ ] Double-cliquez sur `index.html`
- [ ] Vérifiez que toutes les photos s'affichent
- [ ] Cliquez sur les photos pour tester le lightbox

### 4. Déployez
- [ ] Re-uploadez sur Netlify (glissez-déposez le dossier complet)
- [ ] Vérifiez sur le site en ligne

---

## 💡 Astuces Pro

### Ajouter 10 Photos Rapidement

1. Nommez vos photos : `villa-1.jpg`, `villa-2.jpg`, ..., `villa-10.jpg`

2. Copiez-collez ce code 10 fois et changez juste les numéros :

```html
<div class="gallery-item" data-category="exterior">
    <img src="images/gallery/villa-1.jpg" alt="Villa Le Mas du Luberon Rouge" loading="lazy">
    <div class="gallery-overlay">
        <span>Vue 1</span>
    </div>
</div>

<div class="gallery-item" data-category="exterior">
    <img src="images/gallery/villa-2.jpg" alt="Villa Le Mas du Luberon Rouge" loading="lazy">
    <div class="gallery-overlay">
        <span>Vue 2</span>
    </div>
</div>

<!-- ... continuez jusqu'à 10 -->
```

---

## 🎯 Combien de Photos Recommandées ?

### Minimum (site basique) : 10-15 photos
- 3-4 photos extérieures
- 3-4 photos de la piscine
- 2-3 photos des espaces de vie
- 2-3 photos des chambres

### Idéal (site complet) : 25-35 photos
- 5-6 photos extérieures
- 5-6 photos de la piscine
- 4-5 photos des espaces de vie
- 5-6 photos des chambres
- 2-3 photos des salles de bain
- 3-4 photos d'ambiance

### Maximum : PAS DE LIMITE !
Ajoutez autant de photos que vous voulez. Le site gérera automatiquement la galerie.

---

## ❓ Questions Fréquentes

### Q : Mes photos ralentissent le site ?
**R :** Seulement si elles ne sont pas compressées. Utilisez TinyPNG pour les optimiser.

### Q : Quel ordre pour les photos ?
**R :** L'ordre dans le code HTML = l'ordre d'affichage. Mettez vos meilleures photos en premier.

### Q : Puis-je supprimer des photos ?
**R :** Oui ! Supprimez simplement le bloc `<div class="gallery-item">...</div>` correspondant.

### Q : Puis-je organiser par catégorie ?
**R :** Les catégories sont déjà dans le code (`data-category`). Si vous voulez ajouter des filtres, je peux vous montrer comment.

---

## ✅ Checklist Finale

Avant de redéployer :
- [ ] Toutes mes photos sont dans `images/gallery/`
- [ ] Toutes mes photos sont compressées (< 200 KB chacune)
- [ ] J'ai ajouté le code pour chaque photo dans `index.html`
- [ ] Chaque photo a un `alt` descriptif
- [ ] J'ai testé en local (double-clic sur index.html)
- [ ] Tout s'affiche correctement

---

**Voilà ! Vous pouvez maintenant avoir une galerie avec 100+ photos si vous voulez ! 📸**
