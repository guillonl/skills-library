---
name: Patterns Mobile Desjardins
description: Patterns de navigation et d'interaction mobile pour Desjardins
tags: [mobile, patterns, desjardins]
author: Équipe Mobile
date: 2026-03-15
color: green
---

Les interfaces mobiles Desjardins suivent une architecture de navigation par onglets (bottom tab bar) avec un maximum de 5 items. La navigation principale utilise les icônes standardisées du design system avec labels textuels toujours visibles — jamais d'icônes seules.

Les interactions tactiles respectent les zones de confort : boutons principaux en bas de l'écran (zone du pouce), actions destructives protégées par une confirmation modale, et gestes de swipe uniquement en complément d'actions visibles (jamais comme seul moyen d'interaction).

Les formulaires mobiles utilisent le clavier approprié par type de champ (numérique pour les montants, email pour les adresses), le remplissage automatique quand possible, et la validation en temps réel avec messages inline. Les étapes longues sont découpées en flux multi-écrans avec indicateur de progression.

Optimiser pour les performances mobiles : lazy loading des images, squelettes de chargement pour les listes, et mise en cache agressive des données fréquemment consultées. Tester sur les appareils de référence (iPhone SE, iPhone 15, Samsung Galaxy A54) avec des connexions réseau simulées (3G, 4G).
