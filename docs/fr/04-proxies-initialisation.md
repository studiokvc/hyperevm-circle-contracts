# 04 — Proxies et initialisation

Les proxies séparent adresse stable et logique d’implémentation remplaçable.
L’initialiseur doit être appelé une seule fois avec des dépendances vérifiées.
Une implémentation laissée initialisable peut ouvrir une prise de contrôle hors proxy.
Les emplacements de stockage doivent rester compatibles lors d’une mise à niveau.
Le pouvoir d’upgrade doit être identifié, limité et surveillé.
Un changement de logique peut modifier les hypothèses sur CCTP ou HyperCore.
Les événements d’upgrade ne suffisent pas : le bytecode et l’état doivent être contrôlés.
La gouvernance du proxy fait partie de la sécurité du pont.

Suite : [invariants et limites](05-invariants-limites.md).
