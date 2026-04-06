---
name: Accessibilité Bell
description: Standards d'accessibilité WCAG pour les interfaces Bell
tags: [a11y, wcag, bell]
author: Équipe UX
date: 2026-03-15
color: blue
---

Toutes les interfaces Bell doivent respecter les normes WCAG 2.1 niveau AA minimum. Cela inclut un ratio de contraste de 4.5:1 pour le texte normal et 3:1 pour le texte large (18px+ bold ou 24px+ regular), ainsi que pour les éléments interactifs.

Chaque élément interactif doit être navigable au clavier avec un indicateur de focus visible et un ordre de tabulation logique. Les formulaires requièrent des labels explicites, des messages d'erreur associés par aria-describedby, et des instructions claires pour chaque champ.

Les images et icônes nécessitent un texte alternatif descriptif (alt pour les images informatives, aria-hidden="true" pour les icônes décoratives). Les composants dynamiques (modals, accordéons, menus) doivent implémenter les patterns ARIA correspondants avec gestion correcte du focus trap.

Tester avec un lecteur d'écran (VoiceOver sur macOS, NVDA sur Windows) et l'outil axe DevTools avant chaque livraison. Documenter les résultats d'audit dans le rapport d'accessibilité du projet.
