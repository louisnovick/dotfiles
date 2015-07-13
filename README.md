Louis Novick's Dotfiles
==========================

Some configuration I'm attempting to keep organized.

Symlinks
--------

### Symlink the .files

This will remove current dotfiles (specified in the symlinks.sh file) and move them into ~/dotfile_old.  It will then create symlinks to the .files in your ~/dotfiles that you specified.

```shell
sh symlinks.sh
```

### Sublime Text

```shell
ln -s ~/dotfiles/sublime/User/ ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
```

Sources
-------

Based on the dotfiles of:

- [John D. Jameson][john]
- [Mathias Bynens][mathias]



[john]: https://github.com/johndjameson/dotfiles
[mathias]: https://github.com/mathiasbynens/dotfiles
