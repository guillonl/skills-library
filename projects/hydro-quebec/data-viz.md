---
name: Data Visualization HQ
description: Guidelines de visualisation de données pour Hydro-Québec
tags: [dataviz, charts, hydro-quebec]
author: Équipe Data
date: 2026-03-15
color: teal
---

Les visualisations de données Hydro-Québec privilégient la clarté et la précision. Utiliser des graphiques en barres pour les comparaisons, des courbes pour les tendances temporelles, et des graphiques en aires empilées pour les compositions évolutives. Éviter les camemberts sauf pour 2-3 segments maximum.

La palette de données suit une progression séquentielle du bleu clair au bleu foncé pour les valeurs continues, et une palette catégorielle de 6 couleurs distinctes pour les séries multiples. Chaque couleur doit rester différenciable en niveaux de gris pour l'impression.

Chaque graphique doit inclure : un titre descriptif (pas de titre générique comme "Graphique 1"), des axes clairement labellisés avec unités, une légende positionnée de manière cohérente, et des annotations pour les points de données remarquables (pics, anomalies, seuils).

Implémenter les graphiques avec D3.js ou Recharts selon le contexte technique. Assurer l'accessibilité avec des descriptions textuelles alternatives, la navigation clavier entre les points de données, et un tableau de données accessible en alternative au graphique visuel.
