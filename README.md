# Blind Test

Blind test musical en une page : un extrait de 30 secondes, quatre titres, vingt secondes pour trouver.

- **Jazz Club** : 5 sets de difficulté croissante et 3 sets par style (manouche, salsa & latin jazz, bossa nova), 10 morceaux chacun.
- **Mode Duo** : deux joueurs sur un même appareil, chacun son tour.
- **Rétro Club** : 3 niveaux (Facile, Moyen, Difficile) par décennie, des années 60 aux années 2000, dont 30 % de titres hispaniques.

Les extraits viennent de l'API publique de Deezer, appelée via la redirection `/api/deezer/*` définie dans `netlify.toml` (contournement du CORS). Les records sont gardés dans le navigateur (localStorage).

Déploiement : Netlify, branche `main`, aucun build (publication du dossier racine).
