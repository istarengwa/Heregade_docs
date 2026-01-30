# Picturtale - Placeholders

Permission requise: `placeholdertale.use`

## Description
Picturtale expose des placeholders qui renvoient un chemin de texture utilisable dans les UI/menus.
Mode recommande: images packees dans le JAR (`Common/Pictures/...`).
Le mode sync runtime (depuis `pictures/` en data dir) est optionnel via la config.

## Placeholders

### Placeholder racine (recommande)
- `%picturtale<folder=rank_icon;name=vagabond>%`
- `%picturtale<path=rank_icon/vagabond>%`

### Placeholders par dossier
- `%picturtale.rank_icon<name=vagabond>%`

### Placeholders par image (si active dans config)
- `%picturtale.rank_icon.vagabond%`

## Menu admin
- `/pict menu` - Parcourir les dossiers/images et copier un placeholder. Permission: `picturtale.admin.menu`.

## Notes
- Les placeholders retournent un chemin du type `Common/Pictures/<dossier>/<image>.png`.
- Pas d images inline dans le chat; utiliser des UI/menus/notifications.
