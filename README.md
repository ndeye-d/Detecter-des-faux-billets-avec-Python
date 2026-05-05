# 📊Détecter des faux billets avec Python
## 🎯Objectif
L'ONCFM (Organisation Nationale de lutte Contre le Faux-Monnayage) est une organisation publique ayant pour objectif de mettre en place des méthodes d’identification des contrefaçons des billets en euros.
Le but de ce projet est de tester 4 algorithmes de Machine Learning afin de verifier l'authenticité d'un billet et de choisir le meilleur qui detecte les faux billets.    
Les algorithmes sont les suivants:
- **La régression logisitique** qui permet de prédire une valeur binaire 0 ou 1
- **Le KNN (k-nearest neighbors ou plus proche voisin)** qui permet de prédire une valeur à partir des k valeurs qui lui sont le plus proche en faisant une moyenne ou une classification majoritaire
- **Le Random Forest Classifier** qui construit plusieurs arbres de décisions (decision tree) et prédit suivant le résultat de la majorité des arbres de décision
- **Le K-means** qui permet de regrouper des données en plusieurs groupes homogènes qui sont des clusters
## 🛠️Outils
- Python
  - **Pandas** : Analyse et exploration des données
  - **Matplotlib** et **Seaborn** : Visualisation des données
  - **Statsmodels** : Analyse statistique
  - **Sklearn** : Machine Learning
  - **Joblib** : Sauvegarde du modèle
## 🚀Résultats
Matrice de confusion pour la régression logisitique
<img width="508" height="454" alt="image" src="https://github.com/user-attachments/assets/0d21830f-0d6e-404c-ae7b-3af54d892d44" />
La régression logisitique détecte les vrais billets, ce modèle est précis et fiable


