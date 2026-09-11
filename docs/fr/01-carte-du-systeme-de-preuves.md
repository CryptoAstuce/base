# Carte du systeme de preuves Base

Le monorepo Base separe production de blocs, execution, generation de preuves et contestation.
Le proposer selectionne les sorties L2 qui doivent etre engagees ou prouvees.
Les workers executent les travaux lourds derriere un protocole de service versionne.
Le driver coordonne les etapes et leur progression sans confondre resultat calcule et resultat soumis.
Les backends ZK et TEE fournissent des attestations differentes sous des hypotheses distinctes.
Le challenger surveille les jeux de contestation et compare les claims a une execution locale.
La soumission onchain constitue une frontiere finale avec cout, nonce et finalite propres.

Suite : [02 — Préimages et exécution](02-preimages-et-execution.md).
