# reels-tmp

Hébergement temporaire des Reels de Théo avant leur publication.

- Chaque vidéo n'est ici que le temps que les réseaux la récupèrent, puis elle est retirée.
- Rempli et vidé automatiquement par la tâche « Reels perso — publication » ; ne rien déposer à la main.
- Les fichiers sont lus par leur adresse brute (raw.githubusercontent.com).
- `carrousels/<date>-<identifiant>/` : images des carrousels (ig-01.jpg …, tiktok-01.jpg …), déposées par la tâche « Carrousels perso » et retirées quelques jours après publication.
- `tutos/` : la page des tutos (lien fixe envoyé en message à qui commente « TUTO » sous un carrousel). Permanente, jamais vidée. `tutos.json` est la source, `index.html` est réécrit par `carrousel/tuto.py` du dépôt social-autopost. Elle n'est visible à l'adresse https://theodsnts.github.io/reels-tmp/tutos/ que si GitHub Pages est activé sur ce dépôt (Settings → Pages → branche main, dossier racine) ; au 11.11.2026 il ne l'est pas encore.
