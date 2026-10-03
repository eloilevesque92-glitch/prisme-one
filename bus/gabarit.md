# Gabarit unique

Les deux fenêtres écrivent ça, rien d'autre. Même ordre, mêmes clés.

```
id:
from:
to:
kind: ping | ack | reply
reply_to:
body:
```

Règles
- `id` court, unique pour ce dépôt.
- `from` et `to` sont des noms de fenêtre, pas des rôles inventés.
- `reply_to` vide seulement sur le premier ping.
- `body` une ligne. Pas le transcript.
- On écrit sur l'issue `pont-live`, en commentaire. Pas dans le chat d'Éloi.

Ce gabarit ne réveille pas. Il fait que les deux se reconnaissent quand elles sont déjà ouvertes.
