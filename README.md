# Étude Départementale - Landes (40)
Ce projet propose une analyse territoriale du département des Landes (40), à travers deux thématiques principales : la santé (médecins généralistes) et l'éducation (présence de CFA – Centres de Formation d’Apprentis). L’étude a été réalisée via Power BI, en croisant plusieurs jeux de données issus de sources publiques (INSEE, BPE...).

## 🧠 Objectifs
- Évaluer la dotation médicale des communes du département.
- Identifier les zones sous-dotées en médecins généralistes.
- Analyser la répartition territoriale des CFA.
- Déterminer les besoins potentiels d’implantation de CFA selon la population 18–24 ans.

## 📌 Données utilisées
- Liste des équipements géolocalisés pour le département (commerce, santé, sport...) $\large{→}$ $\textit{BPE_Departement_landes.xlsx}$
- Référentiel des gammes d'équipements $\large{→}$ $\textit{BPE_gammes_equipements_2023.xlsx}$
- Population par commune et par tranche d’âge (source INSEE) $\large{→}$ $\textit{Population_landes_corrige.xlsx}$
- Fichier géographique des communes (coordonnées) $\large{→}$ $\textit{REF_GEO.xlsx}$

## 🛠 Méthodologie
- Préparation des données dans Power BI : nettoyage, jointures, enrichissement.
- Calculs d’indicateurs personnalisés :
  - Médecins pour 1000 habitants
  - Écart à la moyenne départementale
  - Niveau de dotation médicale (échelle : très sous-dotée → bien dotée)
  - Besoin en CFA (calculé à partir du nombre d’habitants 18–24 ans)
- Création de visuels interactifs :
  - Filtres dynamiques (par commune)
  - Cartes : répartition des médecins, implantations de CFA
  - Tableaux croisés : synthèse par commune
  - Indicateurs clés encadrés pour lisibilité

## 🧾 Résultats
- Inégalités de dotation médicale identifiées entre communes.
- Mise en évidence de zones potentiellement prioritaires pour l’implantation de nouveaux CFA.
- Interface claire et ergonomique, pensée pour l’analyse territoriale décisionnelle.

## ✨ Points forts
- Visualisation conviviale pour des utilisateurs non techniques.
- Explication claire des indicateurs utilisés (cf. Démarche_Projet.docx).
- Découpage thématique par page : Santé / Éducation.
- Démarche complète : de la collecte à la modélisation, jusqu’à l’interprétation des résultats.

## 📁 Fichiers principaux
| Nom du fichier                  | Description                              |
| ------------------------------- | ---------------------------------------- |
| `Etude_Departement_Landes.pbix` | Rapport Power BI interactif final        |
| `Démarche_Projet.docx`          | Note explicative de la méthodologie      |
| `*.xlsx`                        | Données sources utilisées pour l’analyse |

## 🖥 Aperçu du rapport
![Aperçu de la page Santé](sante.png)

## 🔧 Améliorations possibles
- Utilisation de données actualisées / ouvertes en ligne via API.
- Calcul de dotation relative via méthodes statistiques (écarts-types, percentiles).
- Intégration d’indicateurs socio-économiques supplémentaires (revenus, emploi...).




