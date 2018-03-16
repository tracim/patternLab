## Installation des dépendances nécessaires au patterlab de Tracim.

Pour faire fonctionner patternlab, il faut installer :

- Bootstrap
- Les fonts Quicksand, Open Sans et fontawesome v5


### BOOSTRAP

Pour que Boostrap fonctionne sur patternlab, il faut installer :

Jquery : 

Installer jquery :

- Télécharger jquery via [jquery/download](http://jquery.com/download/).
- Une fois télécharger, placer jquery dans le dossier js, présent dans source.
- Chargé le fichier jquery dans patternlab : ouvrir le fichier _01-foot.mustache présent dans le dossier _meta.
- Ajouter la balise script : "<script src="../../js/jquery/jquery.3.2.1.min.js"></script>".

Popper :

Même schéma que pour jquery mais avec popper :

- Télécharger Popper via [popper/github](https://github.com/FezVrasta/popper.js).
- Le placer dans le dossier js présent dans source. 
- Chargé le fichier popper dans patternlab : ouvrir le fichier _01-foot.mustache présent dans le dossier _meta.
- Ajouter la balise script : "<script src="../../js/popper/popper.1.12.9.min.js"></script>".


Bootstrap :

- Télécharger Bootstrap.
- Placer le dossier Bootstrap.js dans le dossier js présent dans source.
- Placer le dossier Bootstrap.css dans le dossier css présent dans source.
- Charger les deux fichiers:
  bootstrap.min.js dans _01-foot.mustache via le script : "<script src="../../js/bootstrap/bootstrap.min.js"></script>"
  bootstrap.min.css dans _00-head.mustache via le link  : "<link rel="stylesheet" href="../../css/bootstrap/bootstrap.min.css" />".


### FONTS

Quicksand et Open Sans :

Pour utiliser les fonts Quicksand et Open Sans, utiliser le lien CDN fournit par [google fonts](https://fonts.google.com/) et placé le lien CDN dans _00-head.mustache :
"<link href="https://fonts.googleapis.com/css?family=Open+Sans|Quicksand" rel="stylesheet" />"


Font Awesome :

- Télécharger fontawesome via le site [fontawesome](https://fontawesome.com/)
- Placer le dossier téléchargé dans le dossier font présent dans source ( si celui-ci n'existe pas, créé le dossier )
- Chargé le fichier présent dans le dossier fontawesome/svg-with-js/fontawesome-all.js via le script :
"<script defer src="../../fonts/fontawesome/svg-with-js/js/fontawesome-all.js"></script>"