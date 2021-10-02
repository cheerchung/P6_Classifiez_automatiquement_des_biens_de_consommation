# P6_Classifiez_automatiquement_des_biens_de_consommation
Openclassroom Data Scientist project 6

<b>Project description</b>:<br>
Sur la place de marché, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.

Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit.

Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche.

Linda, lead data scientist, vous demande donc d'étudier la faisabilité d'un moteur de classification des articles en différentes catégories, avec un niveau de précision suffisant.
Linda vous a fourni un premier jeu de données d’articles avec le lien pour télécharger la photo et une description associée.

Votre mission est de réaliser une première étude de faisabilité d'un moteur de classification d'articles basé sur une image et une description pour l'automatisation de l'attribution de la catégorie de l'article.

Vous analyserez le jeu de données en réalisant un prétraitement des images et des descriptions des produits, une réduction de dimension, puis un clustering. Les résultats du clustering seront présentés sous la forme d’une représentation en deux dimensions à déterminer, qui ’illustrera le fait que les caractéristiques extraites permettent de regrouper des produits de même catégorie.

La représentation graphique vous aidera à convaincre Linda que cette approche de modélisation permettra bien de regrouper des produits de même catégorie.

<b>function.py</b>: personal function library for feature reduction, data visualisation etc.

<b>P06_notebook</b>: Text processing and image processing, including:<br>
NLP: tokenization, text normalization, TF-IDF, BOW, NMF, LDA<br>
Computer Vision : Bag-of-feature, SIFT, ORB, convolutional neural network (VGG16, ResNet50, Xception)<br>
Feature combination and reduction : TSNE<BR>
Data augmentation<br>
TPU in Google colab<br>

