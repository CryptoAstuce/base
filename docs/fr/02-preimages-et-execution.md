# Préimages et exécution

Une preuve de transition doit reconstruire l’exécution depuis un état initial et des entrées authentifiées.
Le crate preimage fournit les données adressées par hash dont le programme de preuve a besoin.
Le host répond aux demandes tandis que le guest ou backend consomme une vue strictement bornée.
Le MPT relie comptes et storage Ethereum à une racine d’état engagée.
Une préimage absente, surdimensionnée ou associée au mauvais hash doit produire un échec explicite.
Les caches ne doivent jamais mélanger chain ID, bloc, fork ou version du programme.
La reproductibilité exige de conserver racines, inputs, version de code et identifiant de backend.

Suite : [03 — Proposer, workers et reprises](03-proposer-workers-et-reprises.md).
