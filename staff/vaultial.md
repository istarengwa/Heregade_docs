# Vaultial - Commandes staff

## Partie joueurs
- `/money [currency|joueur] [currency]` - Voir votre solde (ou celui d'un joueur si autorise). Permission: `vaultial.command.money` (et `vaultial.command.money.other` pour voir les autres).
- `/monay [currency|joueur] [currency]` - Alias de `/money`. Permission: `vaultial.command.money`.
- `/pay <joueur> <montant> [currency]` - Envoyer de l'argent a un joueur. Permission: `vaultial.command.pay`.
- `/baltop [currency]` - Voir le classement des joueurs les plus riches. Permission: `vaultial.command.baltop`.

## Partie admin (commandes + permissions)
- `/money [currency|joueur] [currency]` - Voir le solde (option "autre joueur" via permission). Permission: `vaultial.command.money` (et `vaultial.command.money.other` pour voir les autres).
- `/monay [currency|joueur] [currency]` - Alias de `/money`. Permission: `vaultial.command.money`.
- `/pay <joueur> <montant> [currency]` - Envoyer de l'argent a un joueur. Permission: `vaultial.command.pay`.
- `/baltop [currency]` - Voir le classement des joueurs les plus riches. Permission: `vaultial.command.baltop`.
- `/eco` - Outils admin economie (affiche l'usage). Permission: `vaultial.admin.*`.
- `/eco set <joueur> <montant> [currency]` - Definir le solde d'un joueur. Permission: `vaultial.admin.set`.
- `/eco add <joueur> <montant> [currency]` - Ajouter de l'argent a un joueur. Permission: `vaultial.admin.add`.
- `/eco take <joueur> <montant> [currency]` - Retirer de l'argent a un joueur. Permission: `vaultial.admin.take`.
- `/eco history <joueur> [currency] [limit]` - Historique des transactions. Permission: `vaultial.admin.history`.
- `/eco rollback <id>` - Annuler une transaction. Permission: `vaultial.admin.rollback`.

## Permissions supplementaires
- `vaultial.admin.*` - Donne tous les droits Vaultial.
