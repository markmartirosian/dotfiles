## Install

```sh
sudo chsh -s "$(which zsh)" "$(whoami)"
sudo usermod -a -G mail "$(whoami)"

git clone --depth 1 --recursive https://github.com/markmartirosian/dotfiles.git ~/.dotfiles
~/.dotfiles/manage install
```
