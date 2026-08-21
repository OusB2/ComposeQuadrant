# Quadrant Jetpack Compose

Une application Android développée avec **Jetpack Compose** affichant quatre quadrants de couleurs différentes. Chaque quadrant présente une description synthétique d'un composable fondamental de Compose.

---

##  Aperçu

L'écran est divisé de manière égale en 4 quadrants (2 rangées, 2 colonnes) utilisant les modificateurs de poids (`weight`).

- **Haut-Gauche (Rose très clair `#EADDFF`)** : Text composable
- **Haut-Droite (Violet clair `#D0BCFF`)** : Image composable
- **Bas-Gauche (Violet moyen `#B69DF8`)** : Row composable
- **Bas-Droite (Violet très doux `#F6EDFF`)** : Column composable

---

##  Notions et Concepts Appliqués

- **Mise en page avec `Column` et `Row`** : Structuration de l'écran en grille 2x2.
- **Modifier `.weight(1f)`** : Répartition égale de l'espace disponible verticalement et horizontalement.
- **Marge intérieure (`padding`)** : Respect des consignes de 16dp pour chaque quadrant et sous le titre.
- **Alignement du contenu** : Centrage vertical et horizontal via `Arrangement.Center` et `Alignment.CenterHorizontally`.
- **Mise en forme du texte** : Utilisation de `FontWeight.Bold` pour les titres et `TextAlign.Justify` pour le corps de texte.
