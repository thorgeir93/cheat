# cheat

First you need to install the `cheat` tool:

```sh
yay -S cheat-bin
```

Generate config folder:
```sh
cheat
```
It will ask you to download the community config files, accept that.


Then apply the personal configs from this repository to the local PC:

```sh
rsync --backup --suffix=.backup cheatsheets/personal/* ~/.config/cheat/cheatsheets/personal/
```

Allow autocomplate using `fzf` tool:

```sh
echo "export CHEAT_USE_FZF=true" >> ~/.bashrc
```
Make sure `fzf` is installed.

_Haven't used this option._
