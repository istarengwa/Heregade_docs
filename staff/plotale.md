# Plotale - Commandes staff

## Partie joueurs
- `/plot claim` - Reclamer le plot ou vous etes. Permission: `plotale.command.claim`.
- `/plot auto` - Reclamer automatiquement un plot libre et s'y teleporter. Permission: `plotale.command.auto`.
- `/plot home [index]` - Se teleporter a l'un de vos plots. Permission: `plotale.command.home`.
- `/plot visit <joueur> [index]` - Visiter le plot d'un autre joueur. Permission: `plotale.command.visit`.
- `/plot info` - Afficher les infos du plot actuel. Permission: `plotale.command.info`.
- `/plot list` - Lister vos plots reclames. Permission: `plotale.command.list`.
- `/plot add <joueur>` - Ajouter un membre a votre plot. Permission: `plotale.command.add`.
- `/plot remove <joueur>` - Retirer un membre de votre plot. Permission: `plotale.command.remove`.
- `/plot deny <joueur>` - Interdire un joueur sur votre plot. Permission: `plotale.command.deny`.
- `/plot undeny <joueur>` - Reautoriser un joueur exclu de votre plot. Permission: `plotale.command.undeny`.
- `/plot limit` - Activer ou desactiver l'affichage des limites du plot. Permission: `plotale.command.limit`.
- `/plot flag list` - Lister les flags disponibles (et prix/durees si configures). Permission: `plotale.command.flag`.
- `/plot flag <flag> <true|false>` - Activer ou desactiver un flag sur le plot. Permission: `plotale.command.flag`.
- `/plot tpback` - Retour a la position precedente avant un /plot home ou /plot auto. Permission: `plotale.command.tpback`.
- `/plot help` - Afficher l'aide des commandes plot. Permission: `plotale.command.help`.

## Partie admin (commandes + permissions)
- `/plot` - Commande racine des plots. Permission: `plotale.command.plot`.
- `/plot claim` - Reclamer le plot ou vous etes. Permission: `plotale.command.claim`.
- `/plot auto` - Reclamer automatiquement un plot libre et s'y teleporter. Permission: `plotale.command.auto`.
- `/plot home [index]` - Se teleporter a l'un de vos plots. Permission: `plotale.command.home`.
- `/plot visit <joueur> [index]` - Visiter le plot d'un autre joueur. Permission: `plotale.command.visit`.
- `/plot info` - Afficher les infos du plot actuel. Permission: `plotale.command.info`.
- `/plot list` - Lister vos plots reclames. Permission: `plotale.command.list`.
- `/plot add <joueur>` - Ajouter un membre a votre plot. Permission: `plotale.command.add`.
- `/plot remove <joueur>` - Retirer un membre de votre plot. Permission: `plotale.command.remove`.
- `/plot deny <joueur>` - Interdire un joueur sur votre plot. Permission: `plotale.command.deny`.
- `/plot undeny <joueur>` - Reautoriser un joueur exclu de votre plot. Permission: `plotale.command.undeny`.
- `/plot limit` - Activer ou desactiver l'affichage des limites du plot. Permission: `plotale.command.limit`.
- `/plot flag list` - Lister les flags disponibles. Permission: `plotale.command.flag`.
- `/plot flag <flag> <true|false>` - Activer ou desactiver un flag sur le plot. Permission: `plotale.command.flag`.
- `/plot tpback` - Retour a la position precedente. Permission: `plotale.command.tpback`.
- `/plot help` - Afficher l'aide des commandes plot. Permission: `plotale.command.help`.
- `/plot admin` - Commandes admin plots. Permission: `plotale.command.admin`.
- `/plot admin claim` - Reclamer un plot pour le serveur. Permission: `plotale.command.admin.claim`.
- `/plot admin setspawn` - Definir le spawn du monde plot. Permission: `plotale.command.admin.setspawn`.
- `/plot admin delete` - Supprimer un plot. Permission: `plotale.command.admin.delete`.
- `/plot admin info` - Infos admin du plugin. Permission: `plotale.command.admin.info`.

## Permissions supplementaires
- `plotale.admin` - Bypass protections (admin plot, flags, etc.).
- `plotale.limit.<n>` - Limite de plots par joueur (ex: `plotale.limit.3`).
- Permissions de flags definies dans la config (champ `flags.*.permission`).
