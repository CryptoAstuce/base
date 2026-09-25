# Proposer, workers et reprises

Le proposer transforme une cible de bloc en sessions de preuve distribuées aux workers.
Chaque session doit posséder une identité stable, un état terminal et un budget de tentatives.
Les retries doivent distinguer erreur transitoire, preuve invalide et travail définitivement impossible.
Une session déjà comptée ne doit pas contourner la limite de reprises lors d’un nouvel échec.
Le polling doit appliquer backoff et annulation afin d’éviter une boucle qui surcharge le prouveur.
Les résultats tardifs doivent être rejetés si la cible ou la version attendue a changé.
Les métriques utiles relient bloc cible, session, worker, tentative et cause de terminaison.

Suite : [04 — Backend ZK](04-backend-zk.md).
