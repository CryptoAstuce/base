# Preimages et execution

Une preuve de transition doit reconstruire l execution depuis un etat initial et des entrees authentifiees.
Le crate preimage fournit les donnees adressees par hash dont le programme de preuve a besoin.
Le host repond aux demandes tandis que le guest ou backend consomme une vue strictement bornee.
Le MPT relie comptes et storage Ethereum a une racine d etat engagee.
Une preimage absente, surdimensionnee ou associee au mauvais hash doit produire un echec explicite.
Les caches ne doivent jamais melanger chain ID, bloc, fork ou version du programme.
La reproductibilite exige de conserver racines, inputs, version de code et identifiant de backend.

Suite : [03 — Proposer, workers et reprises](03-proposer-workers-et-reprises.md).
