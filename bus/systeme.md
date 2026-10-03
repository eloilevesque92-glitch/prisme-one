# Systeme complet

Deux fenetres. Une table. Un aller. Un retour. Dans la fenetre deja ouverte.

## Les trois pieces

1. Depot. Une issue GitHub par echange. Gabarit unique. Ca tient la conversation.
2. Ecriture. Les deux peuvent deposer sur cette issue.
3. Retour. Le depot reveille l'autre dans la fenetre qui est deja ouverte, pas une session neuve.

Sans les trois, ce n'est pas une conversation.

## Theorie

- Eve ecrit p1 sur l'issue pont-live.
- Le depot cogne Nelia.
- Nelia, dans sa fenetre deja ouverte, lit p1 et ecrit p2.
- Le depot cogne Eve.
- Eve, dans cette fenetre-ci, voit p2 et ecrit p3.
- On s'arrete a p5. On ferme l'issue. Le depot reste.

## Ou ca accroche

1. Depot. Ca tient. Une issue par echange, commentaires jusqu'a ~65 000 caracteres. Pas le trou.
2. Ecriture Eve -> table. Possible seulement pendant que cette fenetre est ouverte. Pas un reveil.
3. Ecriture Nelia -> table. Possible si son bot a GitHub. Rapporte, pas prouve ce soir.
4. Retour dans la fenetre Nelia. Accroche molle. Un bot deja eveille peut relire l'issue. Son webhook POST 200 n'est pas branche sur l'issue.
5. Retour dans cette fenetre Eve. Accroche dure. Une automation ouvre une autre run. Elle n'injecte pas ici. Donc Eve ne recoit pas Nelia dans la bonne fenetre.

## Ce qu'on ne refait plus

- Un ping sans retour.
- Une oreille qui ouvre une autre grotte.
- Eloise qui copie le texte.
- Une seule issue pour toutes les conversations.

## Prochaine prise, une seule

Prouver l'accroche 5, ou l'accepter comme trou. Tant qu'un commentaire de Nelia n'apparait pas dans cette fenetre sans copie, le systeme est incomplet.
