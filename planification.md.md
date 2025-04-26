---
tags:
  - "#web"
  - "#projet"
  - "#html"
  - "#sass"
---
## Checklist Structure Projet

- [ ] Créer le dossier Projet
- [ ] Compléter la balise `<head>`
	- [ ] Changer l'attribut `lang` en `fr`
	- [ ] Remplir la balise `<title>` et `<meta description="">`
	- [ ] Trouver et intégrer la `favicon` (16x16px)
	- [ ] Lier ***Font Awesome***

## Checklist Fonts

### Télécharger la(les) font(s)

```embed
title: "Browse Fonts - Google Fonts"
image: "https://www.gstatic.com/images/icons/material/apps/fonts/1x/catalog/v5/opengraph_color.png"
description: "Making the web more beautiful, fast, and open through great typography"
url: "https://fonts.google.com/"
```

- [ ] Télécharger la(les) fonts
- [ ] Les déplacer dans le dossier `/assets/fonts`
- [ ] Appeler la(les) fonts dans le fichier `_settings.scss`

## Checklist Optimisation Images Web

### Préparer les fichiers images

```embed
title: "Squoosh"
image: "https://squoosh.app/c/icon-large-maskable-c2078ced.png"
description: "Squoosh is the ultimate image optimizer that allows you to compress and compare images with different codecs in your browser."
url: "https://squoosh.app/"
```

- [ ] Redimensionner les fichiers images.
- [ ] Les formatter.

> ***Tailles d'image recommandées***
> - Backgrounds : 1920x1080px
> - Illustrations importantes : 1080x720px
> - Petites illustrations : 800x533px ou 600x400px

> ***Formats recommandés***
> - `.webp` (recommandé)
> - `.jpg` (photos si `.webp` indisponible)
> - `.png` (transparence uniquement)

- [ ] Compresser les fichiers images.

> ***Poids cibles***
> Backgrounds : < 300 Ko
> Illustrations importantes : < 200 Ko
> Petites illustrations : < 100 Ko

- [ ] Donner un nom de fichier descriptif (ex: `background-ville-nuit.webp`).

### A l'intégration

- [ ] Remplir l'attribut `alt` avec une description détaillée.

## GitHub : ReadMe.md

### Template GitHub ReadMe.md
```markdown
## Optimisation des images

Toutes les images du projet suivent les bonnes pratiques :
- ***Redimensionnées*** selon leur usage :
  - Backgrounds : 1920×1080 px
  - Illustrations importantes : 1080×720 px
  - Petites illustrations : 800×533 px ou 600×400 px
- ***Formats adaptés*** : priorité au `.webp`, `.jpg` pour les photos, `.png` pour la transparence.
- ***Compression*** optimisée avec TinyPNG ou Squoosh pour un poids réduit sans perte de qualité.
- ***SEO*** renforcé :
  - Noms de fichiers descriptifs
  - Balises `alt` renseignées

```

### Mini Bannière GitHub
```markdown
![Optimisation des images](https://img.shields.io/badge/Images-Optimisées-0aa4d4?style=for-the-badge&logo=googlephotos&logoColor=white)
```
