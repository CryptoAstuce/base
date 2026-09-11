# Proposer, workers et reprises

Le proposer transforme une cible de bloc en sessions de preuve distribuees aux workers.
Chaque session doit posseder une identite stable, un etat terminal et un budget de tentatives.
Les retries doivent distinguer erreur transitoire, preuve invalide et travail definitivement impossible.
Une session deja comptee ne doit pas contourner la limite de reprises lors d un nouvel echec.
Le polling doit appliquer backoff et annulation afin d eviter une boucle qui surcharge le prouveur.
Les resultats tardifs doivent etre rejetes si la cible ou la version attendue a change.
Les metriques utiles relient bloc cible, session, worker, tentative et cause de terminaison.

Suite : [04 — Backend ZK](04-backend-zk.md).
