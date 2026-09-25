# Carte du système de preuves Base

Le monorepo Base sépare production de blocs, exécution, génération de preuves et contestation.
Le proposer sélectionne les sorties L2 qui doivent être engagées ou prouvées.
Les workers exécutent les travaux lourds derrière un protocole de service versionné.
Le driver coordonne les étapes et leur progression sans confondre résultat calculé et résultat soumis.
Les backends ZK et TEE fournissent des attestations différentes sous des hypothèses distinctes.
Le challenger surveille les jeux de contestation et compare les claims à une exécution locale.
La soumission onchain constitue une frontière finale avec coût, nonce et finalité propres.

Suite : [02 — Préimages et exécution](02-preimages-et-execution.md).
