# Synthèse Datavisualisation Jeux Olympiques 2024

## Aperçu du Projet

Ce projet vise à exploiter des techniques de visualisation de données pour relever les défis liés à la gestion des infrastructures de transport en Île-de-France pendant les Jeux Olympiques et Paralympiques de 2024. Il met en lumière la densité du trafic, les heures de pointe et les solutions de mobilité durable, fournissant des informations exploitables pour les citoyens, les visiteurs et les opérateurs de transports publics.

---

## Fonctionnalités

### Objectifs

- Identifier les zones à fort trafic et les heures de pointe.
- Aider à planifier les déplacements des résidents et des visiteurs.
- Soutenir les opérateurs de transports publics dans leur prise de décision.
- Promouvoir des solutions de mobilité durable.

### Visualisations et Fonctionnalités

1. **Analyse des Temps et Distances de Déplacement**

   - Graphiques en anneau réalisés avec D3.js pour visualiser :
     - Les heures de déplacement.
     - Le total des kilomètres parcourus.
   - Effets interactifs au survol affichant les pourcentages et les valeurs pour des catégories comme les vélos, la marche et les bus.

2. **Carte Interactive**

   - Développée avec Leaflet, utilisant des données GeoJSON pour afficher dynamiquement les niveaux de congestion.

3. **Graphiques Dynamiques**

   - Graphiques en barres et en lignes avec des fonctionnalités avancées :
     - Zoom/brush pour se concentrer sur des plages de données spécifiques.
     - Basculer entre les graphiques en barres et en lignes.
     - Édition de données JSON avec mises à jour en temps réel.
     - Fonctionnalité d'exportation pour sauvegarder les graphiques au format PNG ou JPEG.

4. **Analyse de la Saturation des Transports**

   - Cartes thermiques créées avec D3.js pour visualiser la saturation des transports en Île-de-France.
   - Sliders et zones de brossage pour un filtrage temporel.

5. **Navigation et Design Réactif**
   - Navigation centralisée via `nav.html`.
   - Expérience utilisateur unifiée grâce à des éléments d'interface cohérents.

---

## Technologies

### Bibliothèques et Frameworks

- **Bootstrap 5** : Design réactif.
- **D3.js** : Visualisations interactives et animées.
- **Leaflet** : Cartes interactives avec données GeoJSON.

### Sources de Données

- Fichiers GeoJSON pour les données géographiques.
- Fichiers JSON dynamiques pour les modes de transport et les niveaux de congestion.

### Fonctionnalités Avancées

- Édition de données JSON en temps réel avec mises à jour des graphiques.
- Fonctionnalités de zoom et de brossage.
- Exportation des visualisations en PNG/JPEG.

---

## Aperçu Visuel

![Aperçu des Visualisations](gallery/17-teaser.png)

---

## Comment Utiliser

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/IIIAdamIII/DataVisualization.git
   ```
