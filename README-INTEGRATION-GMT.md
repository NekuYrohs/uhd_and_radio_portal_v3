# Mise à jour — montre GMT

Cette archive contient le fichier `index.html` mis à jour ainsi que les quatre assets nécessaires à la montre analogique GMT.

Pour l’intégrer dans une copie existante du portail, décompressez l’archive à la racine du projet en conservant la structure de dossiers. Acceptez le remplacement de `index.html` et fusionnez le dossier `assets/watch-refined/`. Les chemins relatifs employés par le nouveau code sont déjà inclus dans le fichier HTML.

La montre affiche l’heure réelle du fuseau `Europe/Paris`. Son cadran bleu, ses aiguilles animées et sa lunette GMT détourée sont superposés dans la zone de l’ancien timer.

## Contenu attendu

```text
index.html
assets/watch-refined/dial-blue.png
assets/watch-refined/hand-hour.png
assets/watch-refined/hand-minute.png
assets/watch-refined/gmt-bezel-cutout.png
```

## Contrôles effectués

La syntaxe JavaScript, le validateur HTML et `git diff --check` ont été exécutés sans erreur. L’horloge a également été testée dans un navigateur local : les aiguilles se mettent à jour chaque seconde et la synchronisation Europe/Paris est opérationnelle.
