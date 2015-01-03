dotfiles.git
============
Clone and run this on a new CentOS 7 VM to
configure your `bash` and `emacs` development environment as follows:

```sh
cd $HOME
git clone https://github.com/jimbark/c7dotfiles.git
ln -sb dotfiles/.screenrc .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
```
