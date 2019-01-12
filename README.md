# Dotfog
Easily deployed dotfile bootstrap. 
Uses [dotbot](https://github.com/anishathalye/dotbot) as a means of bundling a robust deployment of my own dotfiles.

## Dependencies
### Required
* git
* zsh
* vim
* i3
* tmux

### Optional
* rofi (Defined in cfg/i3/config and cfg/zsh/zalias)
* fd-find (Defined in cfg/zsh/zalias)

## Features
### Zshell
* Robust and idempotent deployment of dotfiles via dotbot.
* Easy installation of Powerline Fonts (for `prompt`)
* A minimally customized prezto fork for extensible zsh config management

### Vim
* Community recommended [vimrc](http://vim.wikia.com/wiki/Example_vimrc) (with vim-plug section) template.
* Installs vim-plug as vim's plugin manager.


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
        * [denysdovhan/spaceship-prompt](https://github.com/denysdovhan/spaceship-prompt.git)
    * [powerline/fonts](https://github.com/powerline/fonts)
* vim
    * [vim-plug](https://github.com/junegunn/vim-plug)
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

