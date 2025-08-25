# update ubuntu : 
[How To Upgrade Existing WSL/WSL2 Ubuntu 18.04 to 20.04](https://www.nextofwindows.com/how-to-upgrade-existing-wsl-wsl2-ubuntu-18-04-to-20-04)
-  lsb_release -a

```
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 18.04.4 LTS
Release:        18.04
Codename:       bionic
```

```sh
sudo apt update
sudo apt list --upgradable
sudo apt upgrade
```

```
sudo apt --purge autoremove
```

```
sudo apt install update-manager-core
```

```
sudo do-release-upgrade -d
```

- Accepter tout les packages

- le terminal redémarre 