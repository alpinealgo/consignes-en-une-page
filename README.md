# Mes consignes en une page : le fichier que Claude lit à chaque session

Le fichier de consignes que Claude Code lit tout seul au début de chaque session, tenu sur une page. Quand j'ai fait le ménage, un de mes fichiers est passé de 143 à 41 lignes, et ma page des règles, celle qui vaut pour toutes mes sessions, a reçu un plafond de 50 lignes. C'est elle que voici, retirée de ce qui ne concerne que moi.

L'histoire du grand ménage : [Mon fichier de consignes est passé de 143 à 41 lignes](https://alpinealgo.ch/articles/consignes-en-une-page.html).

## Ce qu'il règle

- **Comment travailler** : finir, vérifier, dire ce qui reste, puis s'arrêter ; ne rien affirmer sans l'avoir vérifié ; une seule question à la fois.
- **Comment écrire du code** : chercher avant d'écrire, retirer plutôt qu'ajouter, le plus petit changement complet.
- **Comment écrire pour vous** : la place est laissée à vos propres règles.

## L'utiliser en trois minutes

1. Copiez `CLAUDE.md` à l'endroit que Claude Code lit pour toutes vos sessions : `~/.claude/CLAUDE.md`.
2. Gardez ce qui vous parle, rayez le reste, et remplissez la partie « Écrire pour moi ».
3. Tenez la règle du haut : 50 lignes au plus. Pour ajouter une règle, il faut en retirer ou en fusionner une.

## Pourquoi si court

Tout ce qui est dans ce fichier, Claude le relit au début de chaque session. Du coup, chaque ligne de trop, il la relit à chaque fois. Ce qui ne sert que pour une tâche précise va mieux dans un skill, qui n'est chargé que quand la tâche arrive.

## Licence

MIT : vous pouvez le reprendre, le modifier et le partager, en gardant la mention de licence.
