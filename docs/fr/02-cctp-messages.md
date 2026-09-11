# 02 — CCTP et authentification des messages

`CctpForwarder` et `CctpExtension` encadrent le transfert inter-chaînes de l’USDC.
Le burn sur la chaîne source produit un message destiné au domaine cible.
Le MessageTransmitter vérifie l’attestation avant de permettre le mint correspondant.
Domaine source, nonce, version et destinataire doivent être liés au message signé.
Un message déjà consommé ne doit jamais produire un second crédit.
Les versions supportées sont des paramètres de compatibilité et de sécurité.
Le forwarder doit préserver l’intention du bénéficiaire lors du passage entre composants.
La revue doit suivre le message depuis sa création jusqu’au crédit final.

Suite : [CREATE2 et déploiements](03-create2-deploiements.md).
