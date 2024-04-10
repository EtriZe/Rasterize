# Raycaster
Raycaster réalisé lors d'un devoir en Game Prog en Mastère 1 Game Prog à Ynov

![raycasteruntextured](https://github.com/EtriZe/Rasterize/assets/83014937/61833d95-dc70-4bce-8253-d04964c4c046)


ATTENTION : 
Il faut SFML pour le faire fonctionner le fichier source.

OBJECTIF : 
Améliorer le code en performance 
ET SURTOUT le nettoyer.


Exercice : 

Voici le projet Visual Studio de référence pour le 2e projet "Raycaster".
La technique est une simplification du raytracing optimisé pour murs verticaux. Vous trouverez sur internet beaucoup de références le concernant.

Pour rappel il s'agit de rendre une scène 3D comme le tout premier jeu en 3D "Wolfenstein" en SFML.

Le projet contient une boucle de jeu simple avec le traitement des input avec les touches du clavier qui modifie ces variables :
camPos : position de la caméra
camDir : direction de la caméra.
Quelques étapes pour guider :
1. Implémenter drawVerticalLine()

2. Implémenter drawRect()

3. Le Raycaster proprement dit : Implémenter la méthode RasterizeScene() avec de simple couleurs de mur
4. Quels sont les performance (FPS) obtenu ? Est-ce suffisant ? Comment les améliorer ?
5. Appliquer une texture sur les murs.


Les paramètres d'entrées des fonctions doivent vous permettre d'implémenter les méthodes mais vous pouvez les modifier.
