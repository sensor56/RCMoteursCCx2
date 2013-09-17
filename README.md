RCmoteursCCx2
=============

Librairie Arduino pour contrôle de 2 moteurs CC par impulsion RC ("servo-like")
Cette librairie est utilisable avec une carte Sabertooth 2X25A ou Syren 25 en mode RC. 

Librairie Arduino permettant le contrôle de 2 moteurs CC par impulsion RC à la façon servomoteur à rotation continue. 

L'impulsion de contrôle est la suivante : 
* impulsion neutre = arrêt
* impulsion max = 100% sens 1
* impulsion min = 100% sens inverse

La vitesse est proportionnelle au delta de la largeur d'impulsion courante et la largeur d'impulsion du neutre. 

Cette librairie est dérivée de la librairie SimpleCDBot. 
