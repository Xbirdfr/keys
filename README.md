# Xbird.me - Clés diverses

Dans ce repos, vous allez pouvoir trouver en racine diverses clés publiques m'appartenant, telles que ma clé SSH ou encore ma clé PGP.

  - SSH : (Format OpenSSH) [SSH_Xbird_PUBLIC](https://raw.githubusercontent.com/Xbirdfr/xbird-keys/master/SSH_Xbird_PUBLIC)
  - PGP : [PGP_contact@xbird.me_PUBLIC_(4AE16792).asc](https://raw.githubusercontent.com/Xbirdfr/xbird-keys/master/PGP_contact%40xbird.me_PUBLIC_(4AE16792).asc)

# Ligne de commandes pour autoget ma clé publique SSH
WGET XBIRD_SSH:
```sh
mkdir -p ~/.ssh && wget http://xbird.me/ssh -O ~/.ssh/XBIRD_SSH_PUB && cat ~/.ssh/XBIRD_SSH_PUB >> ~/.ssh/authorized_keys && rm -f ~/.ssh/XBIRD_SSH_PUB
```
