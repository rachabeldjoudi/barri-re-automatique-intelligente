Cahier des charges

Projet : Conception d’une barrière automatique intelligente avec détection de véhicules

1. Présentation du projet
Dans le cadre de mon projet, jai choisi de réaliser une barrière automatique capable de détecter la présence d’un véhicule et de commander son ouverture et sa fermeture sans intervention manuelle.Le système sera réalisé à l’aide d’une carte Arduino, d’un capteur de distance et d’un servomoteur.
L’objectif est de fabriquer une petite maquette qui représente le fonctionnement d’une barrière utilisée à l’entrée d’un parking ou d’une résidence.

2. Objectif du projet
Le but principal est de faciliter le passage des véhicules grâce à un système automatique simple et pratique.
Les objectifs sont les suivants :

* Détecter la présence d’un véhicule devant la barrière.
* Ouvrir automatiquement la barrière lorsque le véhicule est détecté.
* Maintenir la barrière ouverte pendant le passage du véhicule.
* Refermer la barrière lorsque le véhicule a quitté la zone de passage.
* Éviter la fermeture de la barrière lorsqu’un véhicule se trouve encore dans cette zone.

3. Fonctionnement du système
Au départ, la barrière est en position fermée. Lorsqu’un véhicule s’approche, le capteur détecte sa présence et transmet l’information à la carte Arduino. Celle-ci commande alors le servomoteur afin d’ouvrir la barrière.
Une fois le véhicule passé, le système vérifie que la zone est libre. Après un court délai, la barrière se referme automatiquement et attend l’arrivée d’un autre véhicule.
Pour améliorer la sécurité, un deuxième capteur pourra être utilisé afin de vérifier que le véhicule a bien quitté la zone de passage.

4. Matériel nécessaire
Le matériel prévu pour la réalisation du projet est le suivant :
Une carte Arduino Uno pour commander le système.
Un capteur ultrasonique HC-SR04 pour détecter la présence d’un véhicule.
Un servomoteur SG90 pour assurer l’ouverture et la fermeture de la barrière.
Une breadboard pour réaliser le montage électrique.
Des fils de connexion pour relier les différents composants.
Un câble USB pour programmer la carte Arduino et la connecter à l’ordinateur.
Des matériaux de récupération, comme du carton, du bois léger ou du plastique, pour fabriquer la maquette de la barrière.
Le matériel pourra être complété selon les besoins rencontrés pendant la réalisation.

5. Contraintes à respecter
Pendant la réalisation, plusieurs contraintes devront être prises en compte :

* Utiliser des composants simples et faciles à trouver.
* Assurer une bonne connexion entre les différents composants.
* Choisir une barrière suffisamment légère pour être commandée par le servomoteur.
* Régler correctement le capteur pour éviter les détections incorrectes.
* Prévoir un fonctionnement qui empêche la fermeture de la barrière lorsqu’un véhicule est encore présent dans la zone surveillée.

6. Résultats attendus
À la fin du projet, nous devons obtenir une maquette fonctionnelle capable de détecter un véhicule et de commander automatiquement l’ouverture et la fermeture de la barrière.
Le système devra fonctionner correctement lors de plusieurs essais successifs et respecter les conditions de sécurité prévues.

7. Tests à effectuer
Pour vérifier le bon fonctionnement du système, les tests suivants seront réalisés :
• Aucun véhicule devant la barrière : la barrière reste fermée.
• Un véhicule est détecté : la barrière s’ouvre.
• Le véhicule est encore dans la zone de passage : la barrière reste ouverte.
• Le véhicule a quitté la zone : la barrière se referme après un délai.
• Un nouveau véhicule arrive : le cycle recommence.

8. Conclusion
Ce projet me permettra de mettre en pratique mes connaissances en électronique, en programmation Arduino et en automatisation. Il permettra également de comprendre comment utiliser des capteurs et un actionneur pour réaliser un système automatique répondant à un besoin concret.
