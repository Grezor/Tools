Pour generer une clée : 
- gpg --full-gen-key
- taper une phrase pour chiffrer la clef
    - reconfirmer la clée

- gpg --list-secret-keys --keyid-format LONG
```sh
/Users/max/.gnupg/pubring.kbx
-----------------------------
sec   rsa4096/XXXXXXXXXXXXXXX 2020-09-17 [SC] [expire : 2021-09-17]
      YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY
uid        [  ultime ] user (commentaire) <user@mail.com>

```
Dans l'exemple ci-dessus la série de chiffre **XXXXXXXXXXXXXXX** représente l'identification d'une clef privée, son ID.

## 3 - Configurer le compte github

- gpg --armor --export XXXXXXXXXXXXXXX

```
-----BEGIN PGP PUBLIC KEY BLOCK-----

.
.
.

-----END PGP PUBLIC KEY BLOCK-----
```

Il ne vous reste plus qu'à ajouter votre clef publique dans les paramètres de votre compte Github.