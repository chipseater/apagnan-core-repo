# Apagnan-core-repo

Here I store packages that are needed to run apagnan-linux, my little joke arch-base GNU/linux distribution. To enable the `apagan-core-repo` on an arch-like system, you only have to append the following lines to your `/etc/pacman.conf`:

```
[apagnan-core-repo]
SigLevel = Optional TrustAll
Server = https://github.com/chipseater/$repo/raw/main/$arch
```

