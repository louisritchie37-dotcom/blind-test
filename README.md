# Blind Test

Blind test musical en une page : un extrait de 30 secondes, quatre titres, vingt secondes pour trouver.

- **Jazz Club** : 5 sets de difficulté croissante et 3 sets par style (manouche, salsa & latin jazz, bossa nova), 10 morceaux chacun.
- **Le Mix** : chansons et questions de culture générale (dont certaines en images, issues de Wikimedia Commons avec crédit auteur et licence), 4 niveaux de 10 manches.
- **Mode Duo** : deux joueurs sur un même appareil, chacun son tour.
- **Rétro Club** : 3 niveaux (Facile, Moyen, Difficile) par décennie, des années 60 aux années 2000, dont 30 % de titres hispaniques.

Les extraits viennent de l'API publique de Deezer, appelée directement en JSONP : aucun serveur n'est nécessaire. Les records sont gardés dans le navigateur (localStorage).

Déploiement : GitHub Pages, branche `main`, dossier racine : https://louisritchie37-dotcom.github.io/blind-test/

En local : ouvrir `index.html` dans un navigateur (connexion internet nécessaire pour les extraits).
