<p align="right">
    <a href="https://travis-ci.org/l5x/dotfiles">
        <img src="https://travis-ci.org/l5x/dotfiles.svg?branch=master"
             alt="build status">
    </a>
</p>

## Installation

```sh
sudo chsh -s "$(which zsh)" "$(whoami)"
sudo usermod -a -G mail "$(whoami)"

git clone --depth 1 --recursive https://github.com/l5x/dotfiles.git ~/dotfiles
~/dotfiles/manage install

```

## Cheat Sheet

- `CTRL-T` - Paste the selected files and directories onto the command line
- `CTRL-R` - Paste the selected command from history onto the command line
- `ALT-C` - cd into the selected directory
