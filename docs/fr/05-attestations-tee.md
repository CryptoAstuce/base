# Attestations TEE

Le chemin TEE utilise une enclave Nitro et une attestation materielle plutot qu une preuve sans confiance.
Le registrar associe mesures autorisees, clefs et politique de deploiement.
L enclave execute le calcul dans un environnement isole puis signe un document d attestation.
Le verifier controle chaine de certificats, mesures, fraicheur et liaison aux sorties L2.
Cette garantie depend du constructeur, du provisionnement et de la gestion des clefs de l enclave.
ZK et TEE ne sont donc pas deux encodages interchangeables d une meme hypothese de securite.
Une interface commune doit conserver le type de preuve et son modele de confiance jusqu a la soumission.

Suite : [06 — Contestation et challenger](06-contestation-et-challenger.md).
