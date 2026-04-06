---
name: Design System Énergir
description: Composants et tokens du design system Énergir
tags: [design-system, components, tokens]
author: Équipe Design
date: 2026-03-15
color: blue
---

Utiliser les composants standardisés du design system Énergir. Chaque composant possède des variantes documentées (primary, secondary, ghost, danger) et des tailles prédéfinies (sm, md, lg). Ne jamais créer de composant ad hoc si un équivalent existe dans le système.

Les design tokens sont organisés en trois niveaux : primitives (couleurs brutes, tailles), semantiques (couleur-action-primary, spacing-section), et composants (button-padding, card-border-radius). Toujours référencer les tokens sémantiques dans le code, jamais les valeurs brutes.

Les composants principaux incluent : Button, Input, Select, Card, Modal, Toast, Table, Badge, Avatar, et Navigation. Chacun supporte les thèmes clair et sombre, les états interactifs (hover, focus, active, disabled), et les variantes responsive.

Avant d'ajouter un nouveau composant, vérifier le registre existant et proposer une extension plutôt qu'une création. Documenter toute nouvelle variante dans Storybook avec des exemples d'utilisation et des guidelines d'accessibilité.
