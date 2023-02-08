# Projet de Machine Learning en langage Python : Prédiction de l'apparition du diabète sur la base d'un dataset sur le diabète des Indiens Pima
Jupyter Notebook en langage Python.
##  I- A  propos
Le dataset qui nous a été soumis comporte des données médicales concernant la population des Indiens Pima d'Amérique du Sud. Le jeu de données rassemble exclusivement des données provenant d'individus de sexe
féminin et âgés de 21 ans au moins. (https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

Il s'agit alors d'analyser les données qui nous ont été fournies et qui en l'occurrence concernent le secteur
médical. L'intérêt ici est d'identifier le "meilleur" modèle permettant de prédire et par extension effectuer de la
prévention concernant l'apparition du diabète dans cette population donnée.

Afin d'effectuer ces prédictions, nous allons utiliser différents algorithmes d'apprentissage supervisé et allons
comparer leur précision (exprimée en %). Par hypothèse, en nous appuyant sur le cours, nous considérerons
qu'un algorithme est performant selon différentes métriques et indicateurs de performance (matrice de
confusion et métriques associées, courbes d'apprentissage, courbe ROC). À la suite de cela, nous effectuerons
un classement des 3 algorithmes.

Compte tenu de notre problématique, il nous a paru plus pertinent d'utiliser des algorithmes d'apprentissage
supervisé car nos données sont étiquetées (i.e : on sait que la variable de sortie est une valeur booléenne notée
'Outcome' associée au fait que la personne soit diabétique ou non).
À partir des attributs médicaux de prédiction, nous allons donc prédire la variable de sortie 'Outcome' qui vaut
1 si la personne est diagnostiquée diabétique, ou 0 sinon.

Pour résoudre ce problème, nous avons donc décidé d'appliquer 3 algorithmes supervisés de classification vus
en cours à savoir :
- La méthode de classification naïve Bayésienne
- La méthode des K-plus proches voisins
- La méthode des arbres de décision

## II- Note de fin
Projet réalisé par Souccouchetty Darlène | Zheng Lisa-Marie
Université Paris Dauphine
