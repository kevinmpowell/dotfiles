# Installation
* `mkdir ~/Sites`
* clone this repo to `~/Sites`
* `cd ~/Sites/dotfiles`
* `script/install`

## iTerm2 Settings
* Go to Preferences/General
* Check 'Load preferences from a custom folder or URL:'
* Browse and point to `~/Sites/dotfiles/iterm`

## Install Oh-My-ZSH
* `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

## Reset .zshrc
* `mv ~/.zshrc.pre-oh-my-zsh ~/.zshrc`

## Copy OMZ Theme
* `cp ~/Sites/dotfiles/kevin.zsh-theme ~/.oh-my-zsh/themes/kevin.zsh-theme`

