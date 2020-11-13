# Analyseur réseau social

## Utilisation sous GNU/Linux

1. Cloner le dépôt.
2. Se rendre dans le répertoire où a été cloné le dépôt.
3. Ouvrir un terminal dans le répertoire `src`.
4. Compiler le projet en lançant la commande `javac *.java`.
5. Démarrer le RMIRegistry avec la commande `rmiregistry`, toujours dans le répertoire `src`.
6. Démarrer le serveur depuis un autre terminal avec la commande `java Server`.
7. Démarrer le client depuis un dernier terminal avec la commande `java Client <serveur>` où `<serveur>` est l'adresse du serveur RMI (pour un test sur une machine locale, il s'agira de `localhost`).

## Crédits

Projet réalisé par Antony Fourchault et Adrien Cavalieri.
