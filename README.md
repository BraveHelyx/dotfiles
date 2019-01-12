# Dotfog
Easily deployed dotfile bootstrap. 
Uses [dotbot](https://github.com/anishathalye/dotbot) as a means of tracking a robust deployment of my own dotfiles.

## Dependencies
* git
* zsh
* vim
* i3
* tmux

## Features
### Zshell
* Robust and idempotent deployment of dotfiles via dotbot.
* Easy installation of Powerline Fonts (for `prompt`)
* A minimally customized prezto fork for extensible zsh config management
    * [denysdovhan/spaceship-prompt](https://github.com/denysdovhan/spaceship-prompt.git)
### Vim
* Community recommended [vimrc](http://vim.wikia.com/wiki/Example_vimrc) (with vim-plug section) template.
* Installs/Uses vim-plug as vim's plugin manager.


## Installation / Deployment
```
git clone https://github.com/BraveHelyx/dotfog
cd dotfog
./install
/bin/bash $HOME/.dotfiles/mod/zsh/fonts/install.sh
chsh -s /bin/zsh
```

## Modules and Submodules
* [rupa/z](https://github.com/rupa/z)
* [changyuheng/fz](https://github.com/changyuheng/fz)
* zsh
    * [bravehelyx/prezto](https://github.com/bravehelyx/prezto)
    * [powerline/fonts](https://github.com/powerline/fonts)
* vim
    * [vim-plug](https://github.com/junegunn/vim-plug)
        * [securemodelines](https://github.com/ciaranm/securemodelines)
        * [terryma/vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors)
        * [ciaranm/securemodelines](https://github.com/ciaranm/securemodelines) override of vim's default 'modelines', managed by vim-plug.
        * [junegunn/fzf](https://github.com/junegunn/fzf)
        * [tpope/vim-surround](https://github.com/tpope/vim-surround)
        * [tpope/vim-eunuch](https://github.com/tpope/vim-eunuch)
        * [scrooloose/nerdtree](https://github.com/scrooloose/nerdtree)
        * [itchyny/lightline.vim](https://github.com/itchyny/lightlinei.vim)

## User Configuration Files
| Process | Config File | Directory |
| --- | --- | --- |
| zsh | Standard zsh config files (i.e. ~/.zshrc)  | mod/zsh/prezto/runcoms/ |
| zsh | User defined bash/zsh aliases (~/.zalias, ~/.zenviron) | cfg/zsh/ |
| vim | Personalised vim settings and vim-plug. (~/.vimrc | cfg/vim/ |

