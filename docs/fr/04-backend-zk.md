# Backend ZK

Le backend ZK convertit une execution deterministe en preuve verifiable par un programme fixe.
Le host prepare inputs et preimages ; le guest ne doit accepter que les donnees engagees.
L image ou identifiant du programme lie la preuve a une version exacte de la logique.
Les sorties publiques doivent inclure les racines et numeros de blocs necessaires a l anti-rejeu.
Une preuve valide cryptographiquement peut rester inutilisable si son journal est mal domaine-separe.
Les benchmarks ZK mesurent un profil mais ne remplacent ni contraintes de capacite ni SLO operateur.
Le choix du backend doit exposer setup, version, format de preuve et politique de mise a niveau.

Suite : [05 — Attestations TEE](05-attestations-tee.md).
