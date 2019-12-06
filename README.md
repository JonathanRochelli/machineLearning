Pour cette activité, notre objectif a été d'améliorer notre modèle de prédiction de loyer, à l'aide d'une feature (variable) supplémentaire en entrée, pour obtenir un modèle plus performant. Il a été ajouté comme observation supplémentaire l'arrondissement de l'appartement. 

I/ Estimation du prix du loyer via régression linéaire :

	La première étape a été de prédire le résultat d'un loyer en fonction de la surface par régression linéaire (Entrée[5] du fichier Jupyter Notebook Loyer.ipynb)
	L'annalyse des résultats nous donne un taux d'erreur de 0.8244114491053267. Ce résultat est très élevé et ne nous donne pas un important niveau de confiance des prédictions.

II/ Estimation du prix du loyer via multiple régression linéaire :

	Cette étape a eu pour but de prédire le loyer en fonction de la surface et de l'arrondissement du bien immobilier (Entrée[6] du fichier Jupyter Notebook Loyer.ipynb). Le taux d'erreur de ce modèle 		est de 0.8133537342887921. Ce résultat n'est que très légérement meilleur que l'estimation par régression linéaire "simple". Ce taux de confiance est toujours très élevé.

III/ Estimation du prix du loyer par la méthode des k-NN :

	Cette méthode étudiée lors du cours consiste à choisir les k données les plus proches du point étudié afin d’en prédire sa valeur (Entrée[7] du fichier Jupyter Notebook Loyer.ipynb). Cette 		algorithme nous a donné un taux d'erreur de 0.610024. En étudiant le graphique permettant de trouver le meilleur cas nous pouvons nous rentre compte que le meilleur k est 2.
	Cette méthode de prédiction est meilleure que la régression linéaire mais le taux d'erreur est tout de même très important. Il est donc difficile de prédire un résultat via ce modèle.


Architecture du fichier Loyer.ipynb:

Entrée[1] : Titre
Entrée[2] : Librairies
Entrée[3] : Graphique des données sans les arrondissements
Entrée[4] : Graphique des données sans les arrondissements avec la droite de régression linéaire
Entrée[5] : Estimation par régression linéaire "simple"
Entrée[6] : Estimation par régression linéaire multiple
Entrée[7] : Méthode des k-NN

Fichier du dosser :

house.csv : Fichier de données sans les arrondissements
house_data.csv : Fichier de données avec les arrondissements
Loyer.ipynb : Fichier Jupyter Notebook contenant le code
Readme.md : Explication et justification





	
