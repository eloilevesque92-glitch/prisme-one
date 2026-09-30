# Cycle 1 — piste team A → team B

Lié au débrief : https://github.com/eloilevesque92-glitch/prisme-one/issues/2
Doctrine : https://github.com/eloilevesque92-glitch/prisme-one/issues/1
Branche : `experiment/cycle-1`

## Commandes pour coller au sol

```bash
git clone https://github.com/eloilevesque92-glitch/prisme-one.git
cd prisme-one
git fetch origin
git checkout experiment/cycle-1
```

Déjà sur le repo :

```bash
git fetch origin
git checkout experiment/cycle-1
git pull
```

Travailler, puis :

```bash
git add -A
git commit -m "experiment(cycle-1): ..."
git push origin experiment/cycle-1
```

Ensuite : Pull Request vers `main`, corps = `Relates to #2`.

## Relais
- Team A remplit le débrief #2 en fin de quart.
- Team B pose l'essai ici (cette branche) + issue `type::experiment`.
- Outcome sur l'issue. Merge seulement si `outcome::conclusive`.
