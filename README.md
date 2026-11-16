# PixelEventLaunch-Releases

Repo **public** : distribution + signal de mise a jour modpack.

- `config.json` : liens Dropbox (versions + ressources). Les joueurs le lisent au lancement.
- Releases GitHub : `PixelEventLaunch.exe` (build via tags `v*` sur le repo prive).

## Mettre a jour le modpack

1. Remplace les archives sur Dropbox (ou cree un nouveau lien)
2. Mets a jour `config.json` si l'URL a change
3. `git commit --trailer "Co-authored-by: Cursor <cursoragent@cursor.com>"` + `git push` sur `main`

Au prochain lancement, PixelEventLaunch detecte le changement et sync.
