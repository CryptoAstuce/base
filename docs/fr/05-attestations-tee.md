# Attestations TEE

Le chemin TEE utilise une enclave Nitro et une attestation matérielle plutôt qu’une preuve sans confiance.
Le registrar associe mesures autorisées, clefs et politique de déploiement.
L’enclave exécute le calcul dans un environnement isolé puis signe un document d’attestation.
Le verifier contrôle chaîne de certificats, mesures, fraîcheur et liaison aux sorties L2.
Cette garantie dépend du constructeur, du provisionnement et de la gestion des clefs de l’enclave.
ZK et TEE ne sont donc pas deux encodages interchangeables d’une même hypothèse de sécurité.
Une interface commune doit conserver le type de preuve et son modèle de confiance jusqu’à la soumission.

Suite : [06 — Contestation et challenger](06-contestation-et-challenger.md).
