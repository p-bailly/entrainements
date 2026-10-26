# entrainements — notes pour travailler dans le repo

Ce dépôt ne contient aucun code source : c'est une **vitrine générée** par `tools/entrainement.py` (dans le dépôt des
cours), qui écrit à la fois les pages HTML et la liste du `README.md`. Ne rien éditer à la main ici, la prochaine
génération écraserait les modifications ; corriger dans le dépôt des cours et regénérer.

- Publié par GitHub Pages sur `https://p-bailly.github.io/entrainements/` (apparemment pour garder les anciennes adresses
  valides). Chaque page (`seconde/`, `premiere/`, `terminale/`, `automatismes/`, plus `index.html` et `404.html`) est une
  **redirection** (meta refresh + `location.replace`) vers `https://maths.pbailly.fr/` ; les vrais contenus vivent là-bas.
- Cibles : chapitres `maths.pbailly.fr/eleves/entrainements/<niveau>-<chapitre>.html`, automatismes
  `maths.pbailly.fr/eleves/automatismes/<classe>` (la redirection conserve `?` et `#`), tout le reste vers l'accueil.
- Le `README.md` est un catalogue de liens (chapitres par niveau, puis les automatismes faits en classe entre les
  marqueurs `<!-- automatismes -->` / `<!-- /automatismes -->`). Il liste les anciennes adresses GitHub Pages (qui
  redirigent) ; fichier généré : ne pas le réduire ni le réécrire ici.
- Un nouveau jeu d'automatismes = un commit généré qui ajoute `automatismes/<classe>.html` et une ligne dans le README.
