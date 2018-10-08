# OpenCV vidéo détections

Afin de comparer plusieurs vidéos et d’identifier si elles ont la même origine, il est nécessaire de trouver des similarités. Les vidéos comparer peuvent être modifiées ou coupé, c’est pour cela que comparer plusieurs vidéo s’avèrent être une tache compliquée. 

## Démarche 

Pour cela nous avons utilisé OpenCV pour effectuer l’analyse d’images et de vidéos afin de pouvoir répondre à la problématique. Après avoir fait quelques recherches sur les possibilités qu’offrait OpenCV, nous avons décidé d’appliquer la démarche suivante :

1. Lecture de la vidéo et extraction des image impliquant un changement de scène     
2. Traitement des images extraites (suppression des images noires/blanches, floues)   
3. Utilisation d’algorithmes pour la comparaison de deux images afin d’obtenir une liste d’images concordantes.   
4. Utilisation de fonctions en relation avec la théorie des graphs pour regrouper les images concordantes et ainsi regrouper les vidéos associées aux vidéos de références.   
5. Interprétation et traitement des résultats mis en évidence par les fonctions de regroupement d’images.   
6. Affichage des résultats sur la forme de listes ou/et d’arbres.   


## Methodes
Après avoir défini la manière dont nous allions effectuer le traitement des vidéos et des images, nous avons effectué une recherche plus approfondie des différentes méthodes proposées par la librairie OpenCV. Nous en avons retenu quatre qui nous semblaient intéressantes et pertinentes : 

- Évaluation perceptuelle de la qualité vidéo et des images (flou, surexposition, distorsion des couleurs).
- Histogramme de couleur primaire (R, G, B) pour détecter la transition de scène
- ORB
- SSIM
- Reconnaissance faciale et de personne
- Histogramme
- Autres méthodes

## Rapport
Pour plus d‘informations [Lien](/doc/cpw_projet_zeller_guignard.pdf)


