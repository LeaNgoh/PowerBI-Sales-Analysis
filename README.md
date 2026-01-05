# 📊 Analyse de la Performance Globale - Global Superstore

## 📝 Description du projet
Ce projet présente un tableau de bord interactif réalisé avec **Power BI**. L'objectif est de transformer les données brutes de "Global Superstore" en insights stratégiques pour piloter la rentabilité mondiale.

## 📸 Aperçu du Dashboard
![Tableau de Bord Global Superstore]([Tableau de Bord de Performaces.png](https://github.com/LeaNgoh/PowerBI-Sales-Analysis/blob/main/Tableau%20de%20Bord%20de%20Performaces.png))


---

## 🚀 Fonctionnalités Techniques
* **Modélisation de données :** Nettoyage et préparation des données avec Power Query.
* **Indicateurs Avancés (DAX) :** Création d'une mesure personnalisée pour la **Marge %** :
  `Marge % = DIVIDE(SUM(Orders[Profit]), SUM(Orders[Sales]), 0)`
* **Analyse Temporelle :** Utilisation de la hiérarchie de dates pour suivre l'évolution mensuelle.
* **Visualisation Géographique :** Cartographie interactive des ventes mondiales.
* **Interactivité :** Intégration de segments (slicers) par Catégorie et Région pour un filtrage dynamique.

## 📈 Analyse des Résultats
* **Top 5 Produits :** Les smartphones (Apple et Cisco) dominent le chiffre d'affaires, marquant une forte dépendance au secteur technologique.
* **Corrélation Ventes/Profit :** L'analyse des courbes montre des pics en décembre, mais révèle des baisses de rentabilité en août, suggérant des coûts opérationnels ou des remises élevées durant cette période.
* **Géographie :** Identification des marchés à fort volume mais à faible marge, permettant de prioriser les actions d'optimisation logistique.

## 🛠️ Outils utilisés
* **Power BI Desktop**
* **Langage DAX**
* **Power Query**

---

## 📂 Installation et Utilisation
1. Clonez ce dépôt ou téléchargez le fichier `.pbix`.
2. Ouvrez le fichier avec **Power BI Desktop**.
3. Utilisez les filtres interactifs pour explorer les données par catégorie ou par zone géographique.
