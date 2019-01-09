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
* Robust and idempotent deployment of dotfiles via dotbot.
* Easy installation of Powerline Fonts (for `prompt`)
* A minimally customized prezto fork for extensible zsh config management
* vim-plug as vim's plugin manager.
* Community recommended [vimrc](http://vim.wikia.com/wiki/Example_vimrc) (with vim-plug section) template.
    * [securemodelines](https://github.com/ciaranm/securemodelines) override of vim's default 'modelines', managed by vim-plug.

## Installation / Deployment
```
git clone https://github.com/BraveHelyx/dotfog
cd dotfog
./install
/bin/bash $HOME/.dotfiles/mod/zsh/fonts/install.sh
chsh -s /bin/zsh
```

## Modules and Submodules
* [z](https://github.com/rupa/z)
* [fz](https://github.com/changyuheng/fz)
* [fzf](https://github.com/junegunn/fzf)
* zsh
    * [BraveHelyx:zprezto](https://github.com/BraveHelyx/prezto)
    * [Powerline Fonts](https://github.com/powerline/fonts)
* vim
    * [vim-plug](https://github.com/junegunn/vim-plug)
        * [securemodelines](https://github.com/ciaranm/securemodelines)

## User Configuration Files
| Process | Config File | Directory |
| --- | --- | --- |
| zsh | Standard zsh config files (i.e. ~/.zshrc)  | mod/zsh/prezto/runcoms/ |
| zsh | User defined bash/zsh aliases (~/.zalias, ~/.zenviron) | cfg/zsh/ |
| vim | Personalised vim settings and vim-plug. (~/.vimrc | cfg/vim/ |

