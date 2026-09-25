# Backend ZK

Le backend ZK convertit une exécution déterministe en preuve vérifiable par un programme fixe.
Le host prépare inputs et préimages ; le guest ne doit accepter que les données engagées.
L’image ou identifiant du programme lie la preuve à une version exacte de la logique.
Les sorties publiques doivent inclure les racines et numéros de blocs nécessaires à l’anti-rejeu.
Une preuve valide cryptographiquement peut rester inutilisable si son journal est mal domaine-séparé.
Les benchmarks ZK mesurent un profil mais ne remplacent ni contraintes de capacité ni SLO opérateur.
Le choix du backend doit exposer setup, version, format de preuve et politique de mise à niveau.

Suite : [05 — Attestations TEE](05-attestations-tee.md).
