# Skills Library

Bibliothèque partagée de skills Claude Code pour l'équipe.
Connectée au [Skills Hub](https://skills-hub.vercel.app) — chaque skill ajouté ici apparaît automatiquement sur la plateforme.

---

## Ajouter un skill

### Option 1 : Avec Claude Code (recommandé)

Installe ce skill dans Claude Code :

```
claude skill install github.com/guillonl/skills-library/skills/add-skill
```

Ensuite, dis simplement à Claude :
- *"Ajoute ce skill dans Design UI"* + colle le contenu
- *"Va chercher ce skill : [lien web]"*
- *"Crée un skill à partir de cette page : [url]"*

Claude va le formater et le push automatiquement.

### Option 2 : Manuellement sur GitHub

1. Va dans le bon dossier (ex: `metiers/design-ui/`)
2. Crée un fichier `mon-skill.md`
3. Colle ce header au début :

```
---
name: Nom du skill
description: Ce que fait le skill en une ligne
tags: [tag1, tag2]
author: Ton prénom
date: 2026-04-06
color: blue
---
```

4. En dessous, colle le contenu du skill
5. Commit — c'est tout !

> Couleurs dispo : `blue`, `gold`, `mint`, `coral`, `purple`, `teal`, `orange`, `silver`

---

## Créer un nouveau projet client

Crée un dossier dans `projects/` :
```
projects/bnc/mon-skill.md
```

## Créer une nouvelle catégorie métier

Crée un dossier dans `metiers/` :
```
metiers/illustration/mon-skill.md
```

---

## Structure

```
metiers/          ← Skills par discipline
  design-ui/
  graphisme/
  ux-research/
  motion/

projects/         ← Skills par client
  energir/
  bell/
  desjardins/
  hydro-quebec/

skills/           ← Skills utilitaires (comme add-skill)
```
