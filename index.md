# ATELIER PRATIQUE : CHOISIR LE BON TYPE DE GRAPHIQUE DANS GOOGLE SHEETS

**Auteur :** Ali Houssene Silahi  
**Contact :** silahi.alihoussene@gmail.com  
**Jeu de données :** `Ventes_mensuelles_TechNova.csv`

[📥 Télécharger le guide de Visualisation en PDF](https://raw.githubusercontent.com/silahi/google-sheet-charts/main/GUIDE_DE_VISUALISATION.pdf)

## Objectif général

Apprendre à **visualiser des données efficacement** dans Google Sheets en choisissant le **type de graphique adapté** à chaque situation.


## Matériel requis

* Google Sheets (connexion internet)
* Jeu de données “TechNova” (fourni ci-dessous)
* 30 à 45 minutes selon le niveau

## Étape 1 : Mise en place des données

### 1️⃣ Crée un nouveau fichier Google Sheets

Nom du fichier →
`Atelier_Graphiques_TechNova_[ton_nom]`

### 2️⃣ Importer les les données suivantes dans la **feuille “Données” :**

[📥 Ventes_mensuelles_TechNova.csv](https://raw.githubusercontent.com/silahi/google-sheet-charts/main/Ventes_mensuelles_TechNova.csv)

| Mois      | Ordinateurs | Téléphones | Tablettes | Accessoires | Dépenses marketing | Satisfaction client (sur 10) |
| --------- | ----------- | ---------- | --------- | ----------- | ------------------ | ---------------------------- |
| Janvier   | 1200        | 950        | 500       | 300         | 700                | 8.2                          |
| Février   | 1300        | 1050       | 600       | 350         | 750                | 8.5                          |
| Mars      | 1450        | 980        | 700       | 380         | 780                | 8.7                          |
| Avril     | 1600        | 1100       | 800       | 420         | 800                | 8.8                          |
| Mai       | 1550        | 1200       | 850       | 450         | 820                | 9.0                          |
| Juin      | 1700        | 1250       | 900       | 460         | 830                | 9.1                          |
| Juillet   | 1800        | 1300       | 950       | 500         | 850                | 9.3                          |
| Août      | 1750        | 1280       | 920       | 490         | 860                | 9.2                          |
| Septembre | 1900        | 1400       | 1000      | 530         | 880                | 9.4                          |
| Octobre   | 2000        | 1500       | 1100      | 550         | 900                | 9.5                          |
| Novembre  | 2100        | 1600       | 1200      | 600         | 950                | 9.6                          |
| Décembre  | 2500        | 1800       | 1500      | 700         | 1000               | 9.8                          |

---

## Étape 2 : Comprendre la structure d’un graphique

Dans Google Sheets, quand tu crées un graphique, tu verras souvent deux éléments essentiels dans l’onglet “Configurer” de l’éditeur de graphique :

- **X-axis (axe des abscisses)**
- **Series (séries de données)**

Ce sont les deux piliers de la structure du graphique.

* **X-axis (axe X)** → C’est ce qu’on appelle l’axe des catégories ou axe X.Il affiche les valeurs descriptives ou les catégories sur l’axe horizontal. Ce sont les étiquettes de ton graphique : des mois, des noms, des années, des produits, etc.
* **Series** → Les séries de données (axe Y). Ce sont les valeurs numériques que tu veux tracer sur ton graphique.

Chaque série représente un ensemble de données à afficher : 
Chaque série peut être une courbe, une barre, une aire, etc.

🧩 *Règle simple :*

- Axe X = ce qu’on compare
- Series = ce qu’on mesure


## Étape 3 : Créer les graphiques selon les objectifs

Crée **une nouvelle feuille par type de graphique** :
Comparaison | Évolution | Répartition | Relation


### 3.1 – Comparer des catégories

**Objectif :** Comparer les ventes des produits pour un mois donné.

#### 🔹 Exercice :

1. Copie les données de **Mars uniquement** (ligne correspondante).
2. Sélectionne les colonnes **Ordinateurs → Accessoires**.
3. Clique sur **Insertion → Graphique**.
4. Dans “Configurer” :

   * Type : **Graphique à colonnes (Column chart)**
   * X-axis : nom des produits
   * Series : valeurs des ventes
5. Personnalise : ajoute le titre → “Comparaison des ventes – Mars”

#### Variante :

* Essaye le **Graphique à barres (Bar chart)** → Compare la lisibilité horizontale/verticale.


### 3.2 – Montrer une évolution dans le temps

**Objectif :** Visualiser l’évolution mensuelle des ventes.

#### 🔹 Exercice :

1. Sélectionne les colonnes **Mois → Ordinateurs, Téléphones, Tablettes**.
2. Insertion → Graphique.
3. Type : **Graphique linéaire (Line chart)**
4. X-axis : Mois
5. Series : Ventes des produits
6. Ajoute un titre clair : *Évolution mensuelle des ventes de TechNova*.

#### Variante :

* Change le type en **Graphique en aires (Area chart)**
  → Observe la différence de perception (aire cumulée).

#### 💡 Bonus :

* Crée un **Graphique combiné (Combo chart)** :

  * Barres : Ventes
  * Courbe : Dépenses marketing


### 3.3 – Montrer une répartition

**Objectif :** Comprendre la part de chaque produit dans les ventes de décembre.

#### 🔹 Exercice :

1. Copie les données de Décembre.
2. Sélectionne **Ordinateurs → Accessoires**.
3. Insertion → Graphique → **Camembert (Pie chart)**
4. Compare ensuite avec le **Graphique en anneau (Donut chart)**.

#### Variante :

* Crée un **Graphique à barres empilées (Stacked bar chart)** pour voir la répartition cumulée sur 3 mois (Oct–Déc).


### 3.4 – Montrer une relation

**Objectif :** Étudier le lien entre dépenses marketing et satisfaction client.

#### 🔹 Exercice :

1. Sélectionne les colonnes **Dépenses marketing** et **Satisfaction client**.
2. Insertion → Graphique → **Nuage de points (Scatter chart)**
3. X-axis : Dépenses marketing
4. Series : Satisfaction client
5. Observe la tendance (si les dépenses augmentent, la satisfaction aussi ?)

#### Variante :

* Ajoute une troisième série (ventes totales) → **Graphique à bulles (Bubble chart)**.


## Étape 4 : Liste bilingue des graphiques (FR / EN)

| Français                    | Anglais (dans Google Sheets) |
| --------------------------- | ---------------------------- |
| Graphique à colonnes        | Column chart                 |
| Graphique à barres          | Bar chart                    |
| Graphique linéaire          | Line chart                   |
| Graphique en aires          | Area chart                   |
| Graphique circulaire        | Pie chart                    |
| Graphique en anneau         | Donut chart                  |
| Graphique combiné           | Combo chart                  |
| Graphique à barres empilées | Stacked bar chart            |
| Nuage de points             | Scatter chart                |
| Graphique à bulles          | Bubble chart                 |
| Histogramme                 | Histogram                    |
| Graphique radar             | Radar chart                  |
| Graphique en entonnoir      | Funnel chart                 |
| Carte géographique          | Geo chart                    |

## Étape 5 : Analyse et discussion

Pour chaque graphique, note :

1. **Quel message** il transmet le mieux.
2. **Ce qu’il montre mal** (limites).
3. **Quand l’utiliser** dans un vrai projet.


## Étape 6 : Défi final – Choisis le bon graphique

> “Tu veux présenter à ton manager un rapport clair sur les ventes, les dépenses et la satisfaction client de TechNova.”

➡️ Crée **un tableau de bord** contenant :

* Un graphique d’évolution (ventes par mois)
* Un graphique de répartition (ventes Décembre)
* Un graphique de relation (marketing vs satisfaction)
* Et un graphique de comparaison (produits)


## Résultat attendu

À la fin de l’atelier, tu sauras :

* Choisir le graphique adapté à ton objectif
* Construire et personnaliser un graphique dans Google Sheets
* Expliquer pourquoi un type de graphique est **plus pertinent** qu’un autre

