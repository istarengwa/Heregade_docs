# Jobstale - Commandes staff

## Partie joueurs
- `/jobs` - Commande racine des metiers (alias: `/job`). Permission: `jobstale.command.jobs`.
- `/jobs list` - Lister les metiers (alias: `/jobs browse`). Permission: `jobstale.command.jobs`.
- `/jobs join <metier>` - Rejoindre un metier. Permission: `jobstale.command.jobs.join`.
- `/jobs leave <metier>` - Quitter un metier. Permission: `jobstale.command.jobs.leave`.
- `/jobs info [metier]` - Afficher les infos d'un metier (menu si possible). Permission: `jobstale.command.jobs.info`.
- `/jobs stats [metier]` - Afficher vos niveaux de metiers. Permission: `jobstale.command.jobs.stats`.
- `/jobs bonus <metier>` - Afficher les bonus actifs pour un metier. Permission: `jobstale.command.jobs.bonus`.
- `/jobs specialisation <metier> [specialisation]` - Lister ou choisir une specialisation (alias: `/jobs spec`, `/jobs specialize`). Permission: `jobstale.command.jobs.specialisation`.

## Partie admin (commandes + permissions)
- `/jobs` - Commande racine des metiers (alias: `/job`). Permission: `jobstale.command.jobs`.
- `/jobs list` - Lister les metiers (alias: `/jobs browse`). Permission: `jobstale.command.jobs`.
- `/jobs join <metier>` - Rejoindre un metier. Permission: `jobstale.command.jobs.join`.
- `/jobs leave <metier>` - Quitter un metier. Permission: `jobstale.command.jobs.leave`.
- `/jobs info [metier]` - Infos d'un metier (menu si possible). Permission: `jobstale.command.jobs.info`.
- `/jobs stats [metier]` - Stats de metiers. Permission: `jobstale.command.jobs.stats`.
- `/jobs bonus <metier>` - Bonus actifs pour un metier. Permission: `jobstale.command.jobs.bonus`.
- `/jobs specialisation <metier> [specialisation]` - Lister ou choisir une specialisation (alias: `/jobs spec`, `/jobs specialize`). Permission: `jobstale.command.jobs.specialisation`.
- `/jobs reload` - Recharger la config Jobstale. Permission: `jobstale.command.jobs.reload`.

## Permissions supplementaires
- `jobstale.admin.*` - Donne tous les droits Jobstale.
- Permissions de specialisation definies dans la config des metiers (champ `permission`).
