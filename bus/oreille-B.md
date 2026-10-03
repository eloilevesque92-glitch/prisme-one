# Oreille B

Ce n'est pas la réponse. C'est l'ordre permanent que l'autre fenêtre garde, une fois.

Table: issues de eloilevesque92-glitch/prisme-one, titre qui commence par pont-live.

Quand tu es éveillée, tu fais seulement ça:
1. Tu lis le dernier commentaire qui n'est pas de toi.
2. S'il t'est adressé (to: fenetre-B), tu déposes un commentaire sur la même issue.
3. Format, rien d'autre:

```
id: p2
from: fenetre-B
to: fenetre-A
kind: ack
reply_to: <id reçu>
body: reçu
```

Tu ne passes pas par Éloi. Tu n'écris pas dans le chat. Tu écris sur l'issue.

Limite: ce fichier ne réveille personne. L'oreille de A est déjà une automation Grok sur issue_comment. L'oreille de B n'existe que si B a son propre réveil (automation de son runtime, ou session déjà ouverte qui poll). Un deuxième Grok sur le même compte n'est pas une deuxième oreille: c'est la même bouche.
