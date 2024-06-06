Dans le cadre du projet CODEVSI, un groupe de 3 étudiants s'est vu confier la tâche de  d'améliorer les fonctionnalités de la version open source du robot Cubetto.
Le Cubetto est un robot destiné à l'enseignement des bases de la programmation aux enfants, permettant une introduction ludique et interactive au codage.



Il est composé d'un robot motorisé en bois, d’un tapis sur lequel il se déplace et d'une interface de commande permettant de programmer ses mouvements à l'aide de blocs physiques.
Un problème majeur a été identifié dans la version open source : le manque de précision dans les déplacements du robot dû au système de pilotage des roues. Ce dernier utilisait un capteur optique couplé à un moteur à engrenages, pour suivre la rotation des roues en comptant les
traits noirs et blancs.



Le groupe a conçu une solution de remplacement, incluant une modification complète du système de pilotage :
- des moteurs pas à pas 28BYJ-48 disponibles au Fablab ont remplacé les moteurs à engrenage
- les drivers moteurs associés ont été remplacés
- le code Arduino a été modifié en conséquence pour asservir le moteur pas à pas
- une breadboard a été ajoutée pour assurer l’alimentation des deux moteurs


Pour assurer la meilleure précision possible, il a été nécessaire de :
- modéliser puis imprimer en 3D un joint d’adaptation entre la roue et l’arbre-moteur



- modéliser puis réaliser en 3D un support de fixation pour le moteur sur la carrosserie




Par ailleurs, une nouvelle fonctionnalité de détection des obstacles a été ajoutée. Ceci est réalisé à l’aide d’un capteur ultrason de modèle HC-SR04 lui aussi disponible au Fablab.

Le code Arduino principal a intégré le fonctionnement du capteur optique.

Finalement, une nouvelle carrosserie a été fabriquée à l'aide de la découpeuse laser du Fablab pour être adaptée au nouveau capteur ultrason et pour contenir l’ensemble des nouveaux composants.
Une fois le nouveau modèle assemblé, une série de tests a été exécutée pour vérifier le bon fonctionnement du robot et du nouveau système, assurant ainsi que les améliorations apportées répondaient aux attentes et aux exigences du projet.


Membres du groupe : Khalil SOUGUIR, Ylan TEISSIER, Marie-Joséphine EDOA


Annexes :
Code Arduino du robot : insérer cubetto.ino
Joint d’adaptation entre la roue et l’arbre-moteur : insérer joint.stl
Support de fixation moteur : insérer support.stl
Carrosserie du robot : insérer carosserie.ink
