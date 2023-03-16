# Détection des erreurs LiDAR

Ce pluging a été développé dans le cadre du Projet Analyse Spatiale du M2 IGAST. Il a pour objectif de détecter des erreurs à la suite d'un déclassement manuel dans des nuages de points LiDAR.

## Pré-requis 

Ce pluging nécessite la version 3.28 de [QGIS](https://www.qgis.org/fr/site/), ainsi que la librairie Python Laspy, à installer depuis le terminal OSGeo4W de QGIS :
```
pip install laspy
```


## Installation

Pour utiliser le pluging, cloner le projet sur votre ordinateur directement dans le répertoire pluging de votre QGIS (``\AppData\Roaming\QGIS\QGIS3\profiles\default\python\plugins``) :

```
git clone https://github.com/ibtissamfrj/Projet-Analyse-Spatiale.git
```
Ou télécharger l'archive zip, et l'ajouter directement depuis QGIS (`` Extensions → Installer / Gérer les extensions  → Installer depuis un ZIP``)

Puis cocher le pluging dans (`` Extensions → Installer / Gérer les extensions  → Installées``)


## Author

* **Ibtissam Faraji** 
* **Judith Nabec** 
* **Lubin Roineau** 
* **Estelle Stefanini** 
