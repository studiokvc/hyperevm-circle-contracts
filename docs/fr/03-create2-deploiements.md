# 03 — CREATE2 et adresses déterministes

Les scripts prédisent les adresses de déploiement à partir de CREATE2.
L’adresse dépend du déployeur, du sel et du hash du code d’initialisation.
Modifier un argument constructeur change donc l’adresse attendue.
La prédiction doit être comparée au résultat avant toute configuration croisée.
Une adresse déterministe n’authentifie pas à elle seule le bytecode déployé.
Le propriétaire de la factory et les sels utilisés appartiennent au modèle de confiance.
Les scripts séparent implémentations, proxies, forwarder et extension CCTP.
Un manifeste de déploiement doit conserver chaînes, versions et hashes de code.

Suite : [proxies et initialisation](04-proxies-initialisation.md).
