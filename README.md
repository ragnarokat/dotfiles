dotfiles
========

Really simple

```
cd ~
git clone https://github.com/ramseydsilva/dotfiles
cd dotfiles
git submodule init
git submodule update
cd ~
ln -s ~/dotfiles/.vim .vim
ln -s ~/dotfiles/.vimrc .vimrc
ln -s ~/dotfiles/.config/* .config/.
sudo ln -s ~/dotfiles/bin/* /usr/bin/.
```
