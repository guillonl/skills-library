# Skills Library

> Ce repo est connecte a la plateforme **Skills Hub** — tout skill ajoute ici apparait automatiquement sur la plateforme en quelques minutes.

Bienvenue dans la collection partagee de skills Claude Code de l'equipe. C'est ici qu'on centralise tous nos skills, organises par metier et par projet client.

Pas besoin d'etre developpeur pour contribuer. Si tu sais creer un fichier sur GitHub, tu sais ajouter un skill.

---

## Comment ajouter un skill

### 1. Va dans le bon dossier

**Par metier :**
- `metiers/design-ui/` — Design UI
- `metiers/graphisme/` — Graphisme
- `metiers/ux-research/` — UX Research
- `metiers/motion/` — Motion

**Par projet client :**
- `projects/energir/` — Energir
- `projects/bell/` — Bell
- `projects/hydro-quebec/` — Hydro-Quebec
- `projects/desjardins/` — Desjardins
- etc.

### 2. Cree un nouveau fichier `.md`

Tu peux creer le fichier directement sur GitHub, ou uploader un fichier `.md` que tu as trouve en ligne.

Nomme-le en **kebab-case** (mots en minuscules separes par des tirets) :
- `mon-super-skill.md`
- `audit-accessibilite.md`
- `palette-generator.md`

> Astuce : tu peux aussi copier le fichier `SKILL_TEMPLATE.md` a la racine du repo comme point de depart.

### 3. Ajoute l'en-tete au tout debut du fichier

Colle ce bloc au debut de ton fichier, puis remplis les champs :

```
---
name: Nom du skill
description: Une courte description de ce que fait le skill
tags: [tag1, tag2, tag3]
author: Ton prenom
date: 2026-04-06
color: blue
---
```

**Couleurs disponibles :** `blue`, `gold`, `mint`, `coral`, `purple`, `teal`, `orange`, `silver`

### 4. Ajoute le contenu du skill

En dessous de l'en-tete (apres le deuxieme `---`), colle le contenu complet du skill. C'est le texte que Claude va utiliser comme instructions.

### 5. Commit et push

Commit ton fichier et push sur `main`. La plateforme Skills Hub se met a jour automatiquement — ton skill apparaitra en quelques minutes.

---

## Comment creer un nouveau projet (client)

1. Cree un nouveau dossier dans `projects/` — par exemple : `projects/bnc/`
2. Ajoute au moins un fichier `.md` de skill a l'interieur
3. Push — le nouveau projet apparait dans la barre laterale du Skills Hub

---

## Comment creer une nouvelle section metier

1. Cree un nouveau dossier dans `metiers/` — par exemple : `metiers/illustration/`
2. Ajoute au moins un fichier `.md` de skill a l'interieur
3. Push — la nouvelle section apparait dans la barre laterale du Skills Hub

---

## Utiliser le skill Claude Code (recommande)

Si tu utilises Claude Code, tu peux installer ce repo comme source de skills :

```
claude skill install github.com/guillonl/skills-library
```

Ensuite, dis simplement a Claude : **"Ajoute ce skill dans Design UI"** et colle le contenu. Claude va formater le fichier et le pousser pour toi.

---

## Structure du repo

```
skills-library/
  metiers/
    design-ui/          ← Skills de Design UI
    graphisme/          ← Skills de Graphisme
    ux-research/        ← Skills de UX Research
    motion/             ← Skills de Motion
  projects/
    energir/            ← Skills projet Energir
    bell/               ← Skills projet Bell
    hydro-quebec/       ← Skills projet Hydro-Quebec
    desjardins/         ← Skills projet Desjardins
  SKILL_TEMPLATE.md     ← Template a copier pour creer un skill
  README.md             ← Ce fichier
```

---

## Questions ?

Si tu n'es pas sur de ou placer un skill ou comment le formater, demande a l'equipe. On prefere un skill mal place qu'un skill jamais partage.
