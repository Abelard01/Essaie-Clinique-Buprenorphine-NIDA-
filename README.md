# Essaie-Clinique-Buprenorphine-NIDA-
"Réplication statistique de l'essai clinique CTN-0003 (Ling et al.) comparant Buprenorphine et Clonidine."
# Analyse Clinique : Buprénorphine-Naloxone vs Clonidine

Ce projet est une réplication technique et statistique de l'essai clinique du **NIDA CTN-0003** (Ling et al., 2005). Il vise à comparer l'efficacité de deux traitements pour la détoxification des opiacés via une analyse de données en Python.

## 📊 Résultats Clés
L'analyse menée sur 411 patients en Intention de Traiter (ITT) démontre :
* **Taux de succès global :** 33.5% pour Bup-Nx contre 6.7% pour Clonidine.
* **Significativité :** Différence validée par Z-test (p < 0.001).
* **Rétention :** La Clonidine entraîne un abandon massif (>90%) en contexte ambulatoire.

## 🛠️ Outils Techniques
* **Langage :** Python 3.10
* **Manipulation de données :** Pandas, Polars
* **Visualisation :** Matplotlib (Style Publication)
* **Statistiques :** Scipy (Chi2)

## 📂 Contenu du Dépôt
* `Analysis_Notebook.ipynb` : Le code complet de l'analyse et des visualisations.

## 🚀 Comment exécuter ce projet
1. Cloner le repo
2. Installer les dépendances : `pip install pandas polars matplotlib scipy`
3. Lancer Jupyter Lab
