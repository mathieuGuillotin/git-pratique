
#### Aller dans le home
```shell
$ cd
équivalent à
$ cd ~
```

#### Aller dans le répertoire précédent
```shell
$ cd -
```

#### Récupérer la commande précédente (history substitution)
```shell
$ cat sudo.conf
cat: sudo.conf: Permission non accordée
$ sudo !!
sudo cat sudo.conf
Mot de passe :
```

#### Récupérer l'exécution de la commande précédente
```shell
$ locate myawesomefile
~/Documents/myawesomefile.txt
$ cat `!!`
My awesome content
```