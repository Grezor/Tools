```sh
PS1="\[\033]0;$TITLEPREFIX:${PWD//[^[:ascii:]]/?}\007\]\n\[\033[32m\]\u \[\033[33m\]\w\[\033[36m\]`__git_ps1`\[\033[0m\]\n$ "
# Geoffrey /d/DEV/DGithub/Tools (master)
PS1="\# \[\e[0;36m\][\t]\[\e[0;m\] \[\e[0;32m\]\u@\h\[\e[0;m\]: \[\e[1;35m\]\w\[\e[0;m\] \[\e[1;32m\] \\$\[\e[0;m\] "
# [13:22:19] Geoffrey@host: /d/tools $```

# Pour changer de host
PS1="toto ->" # puis entrer
