# Akieni Academy — Livrable 2 : Composant Carte Produit Premium

Bienvenue sur le dépôt de mon deuxième livrable dans le cadre de ma formation de **Développeur Web Fullstack** (Cohorte 2) à l'Akieni Academy.

Ce projet consiste à concevoir et intégrer un composant d'interface utilisateur moderne et esthétique : une **Carte Produit** (_Product Card_). L'objectif principal est de prouver une maîtrise absolue de la géométrie des éléments et du positionnement architectural traditionnel en CSS.

---

## 🎯 Objectifs du projet

- **Maîtrise du Modèle de Boîte :** Structurer les dimensions, les marges internes et externes de chaque élément avec précision.
- **Rigueur Sémantique :** Utiliser des balises HTML5 natives porteuses de sens pour garantir une accessibilité optimale.
- **Qualité d'Intégration :** Maintenir une indentation parfaite et un code propre, modulaire et exempt de styles en ligne.

---

## 🛠️ Contraintes Techniques Respectées

Pour ce livrable, les consignes d'intégration imposaient un niveau de contrainte technique particulièrement strict, visant à valider les fondamentaux du CSS :

| Contrainte              |   Statut    | Description                                                                                           |
| :---------------------- | :---------: | :---------------------------------------------------------------------------------------------------- |
| **Zéro Flexbox**        | 🚫 Interdit | Aucun usage de `display: flex` ni de ses propriétés associées.                                        |
| **Zéro CSS Grid**       | 🚫 Interdit | Aucun usage de `display: grid` pour l'architecture.                                                   |
| **Modèle de boîte pur** | ✅ Respecté | Alignements gérés uniquement via `display: block` / `inline-block`, `width`, `margin` et `padding`.   |
| **Box Sizing**          | ✅ Respecté | Utilisation systématique de `box-sizing: border-box` pour un contrôle mathématique exact des volumes. |
| **Zéro Style En Ligne** | ✅ Respecté | Centralisation de l'intégralité du design dans une feuille de style CSS externe.                      |

---

## 📂 Structure du Projet

L'architecture du dépôt est volontairement minimaliste et épurée pour répondre aux exigences de propreté attendues par l'inspecteur :

```text
.
├── index.html        # Structure HTML5 sémantique du composant
├── style.css         # Feuille de style CSS externe (Modèle de boîte classique)
└── README.md         # Documentation du projet
```
