# Mes consignes en une page

Le fichier de consignes que Claude Code lit tout seul au début de chaque session, réduit à une page. Le mien est passé de 143 à 41 lignes. Voici le modèle, nettoyé de ce qui ne concerne que moi.

L'histoire : [Mon fichier de consignes est passé de 143 à 41 lignes](https://alpinealgo.ch/articles/consignes-en-une-page.html).

## Comment s'en servir

1. Copiez `CLAUDE.md` à l'endroit que Claude Code lit pour toutes vos sessions : `~/.claude/CLAUDE.md`.
2. Gardez ce qui vous parle, rayez le reste, et remplissez la partie « Écrire pour moi ».
3. Tenez la règle du haut : 50 lignes au plus. Pour ajouter une règle, il faut en retirer ou en fusionner une.

## Pourquoi si court

Tout ce qui est dans ce fichier, Claude le relit au début de chaque session. Du coup, chaque ligne de trop, il la relit à chaque fois. Ce qui ne sert que pour une tâche précise va mieux dans un skill : il n'est chargé que quand la tâche arrive.

## Licence

MIT : vous pouvez le reprendre, le modifier et le partager, en gardant la mention de licence.
