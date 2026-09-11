# 01 — Relier HyperCore et HyperEVM

Ces contrats Circle organisent le déplacement de fonds autour d’HyperEVM.
`CoreDepositWallet` reçoit des actifs destinés au chemin de dépôt vers HyperCore.
Les contrats EVM ne doivent pas confondre crédit interne, transfert ERC-20 et finalité économique.
Chaque transition doit lier actif, montant, bénéficiaire et domaine d’origine.
Une confirmation EVM peut précéder la disponibilité observée dans l’autre composant.
L’interface doit donc afficher des états intermédiaires explicites.
Les événements servent au rapprochement mais ne remplacent pas l’état canonique.
Cette frontière Core/EVM est le premier invariant du parcours.

Suite : [CCTP et messages](02-cctp-messages.md).
