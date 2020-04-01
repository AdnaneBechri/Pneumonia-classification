# Pneumonia-classification
Pneumonia classification models

Vous trouverez ici les implémentations des modèles de classification à savoir un réseau de neurones convolutif séquentiel "Model1_Sequential_CNN" et un VGG-16 personnalisé sous le nom "Model2_Custom_VGG16".

Le modèle CNN séqueltiel est basé sur le travail de recherche intitulé "Automated Pneumonia Diagnosis using a Customized Sequential Convolutional Neural Network" de Raheel Siddiqi

L'article est téléchargeable sur le lien : https://www.researchgate.net/publication/335084257_Automated_Pneumonia_Diagnosis_using_a_Customized_Sequential_Convolutional_Neural_Network



Le deuxième modèle de CNN séqueltiel est basé quant à lui sur l'article "Visualization and Interpretation of Convolutional Neural Network Predictions in Detecting Pneumonia in Pediatric Chest Radiographs" 

l'article est téléchargeable sur le lien : https://www.researchgate.net/publication/327793444_Visualization_and_Interpretation_of_Convolutional_Neural_Network_Predictions_in_Detecting_Pneumonia_in_Pediatric_Chest_Radiographs



Le code du modèle CNN séquentiel vient de la source suivante : https://github.com/raheelsiddiqi2013/pneumonia-diagnosis/blob/master/Chest_X_Ray_Image_Classification_Pneumonia_vs_Normal2D.ipynb

Partie rajoutées : Le code a été modifié afin de corriger certains erreurs, les Partie répartition des données (Train, val, test), La partie visualisation des résultats (Graphes Train, Val vs epochs), Matrices de confusion, Evaluation du Modèle ont été rajoutées par Adnane Bechri 



Le code du modèle VGG-16 vient de la source suivante : https://github.com/sivaramakrishnan-rajaraman/Visualization-of-CNN-toward-Pneumonia-Detection-in-CXRs/blob/master/VGG16%20custom%20training.ipynb

Les parties rajoutées sont les suivantes :  Augmentation de données, Répartition des données (Train, Val, test), Graphes (Accuracy, Loss vs Epochs), Evaluation du modèle (Mesures : accuracy, F1 Score, Precision et Recall) et la partie Matrices de confusion. 
