# Xbird.me - Clés diverses

Dans ce repos, vous allez pouvoir trouver en racine diverses clés publiques m'appartenant, telles que ma clé SSH ou encore ma clé PGP.

  - SSH :
  - PGP :

Dans le répertoire "Amis", j'y entrepose les clés des personnes souhaitant utliser mon systeme de raccourci pour leurs clés SSH / PGP (Ce systeme n'est pas encore disponible actuellement)

# Ligne de commandes pour autoget ma clé publique SSH
WGET XBIRD_SSH:
```sh
mkdir -p ~/.ssh && wget http://xbird.me/ssh -O ~/.ssh/XBIRD_SSH_PUB && cat ~/.ssh/XBIRD_SSH_PUB >> ~/.ssh/authorized_keys && rm -f ~/.ssh/XBIRD_SSH_PUB
```