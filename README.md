# Installation
* `mkdir ~/Sites`
* clone this repo to `~/Sites`
* `cd ~/Sites/dotfiles`
* `script/install`


## Install Oh-My-ZSH
* `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

## Reset .zshrc
* `mv ~/.zshrc.pre-oh-my-zsh ~/.zshrc`

## Copy OMZ Theme
* `cp ~/Sites/dotfiles/kevin.zsh-theme ~/.oh-my-zsh/themes/kevin.zsh-theme`

## iTerm2 Settings
* Go to Preferences/General
* Check 'Load preferences from a custom folder or URL:'
* Browse and point to `~/Sites/dotfiles/iterm`

### iTerm2 Settings Powerline Font
Under the Preferences/Profile Pane in the Text tab change the font for each type (Regular and Non-ASCII) to 'Inconsolata for Powerline'.
Refresh ZSH by typing source ~/.zshrc on the command line.

## Install Slate
`cd /Applications && curl http://www.ninjamonkeysoftware.com/slate/versions/slate-latest.tar.gz | tar -xz`
