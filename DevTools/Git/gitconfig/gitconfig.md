## gitconfig settings 

```bash
[user]
	name = [name] //exemple : John Doe
	email = [email] // exemple : johndoe@example.com
	signingkey = [signkey] // gpg --list-secret-keys --keyid-format=long
[commit]
	gpgsign = true
    gpsign = true
[gpg]
	program = [program-gpg] // where.exe gpg > [Link](https://www.git-tower.com/blog/setting-up-gpg-windows/)
[alias]
    lg = !"git lg1"
    s = status
    d = diff --cached
    dl = diff HEAD HEAD^
    a = add --all
    ap = add --all -p
```