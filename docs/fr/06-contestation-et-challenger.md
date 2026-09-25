# Contestation et challenger

Le challenger observe les dispute games et recherche les claims incompatibles avec l’état dérivé.
Il doit suivre la bonne factory, implémentation, version de jeu et fenêtre temporelle.
Une réorganisation L1 peut invalider les observations récentes et impose une reprise cohérente.
Les mouvements de jeu exigent preuves, horloges et positions correctement calculées.
Une alerte sans possibilité de transaction avant expiration n’est pas une protection opérationnelle.
La séparation observation, décision, construction et envoi facilite l’audit des automatismes.
Les runbooks doivent couvrir RPC indisponible, nonce bloqué, fonds insuffisants et mise à niveau de contrat.

Suite : [07 — Limites et vérification](07-limites-et-verification.md).
