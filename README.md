# API Aux Claviers Citoyens (ACC)

`openapi.yaml` est le contrat d'API, transcrit du *Cahier des charges développement v2.2* (CDC). C'est la référence : l'implémentation doit s'y conformer.

## Commandes

Prérequis : Node.js. Première fois : `npm install`.

| Commande | Rôle |
|---|---|
| `npm run docs` | Documentation navigable (http://localhost:8081) |
| `npm run mock` | Faux serveur sur http://localhost:4010 qui répond selon le contrat |
| `npm run lint` | Vérifie la validité du contrat |

Le faux serveur valide les requêtes mais ne garde aucun état : ses réponses sont des exemples générés à partir du contrat.
