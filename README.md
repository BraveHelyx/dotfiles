# Dotfog
Easily deployed dotfile bootstrap. 
Uses [dotbot](https://github.com/anishathalye/dotbot) as a means of tracking a robust deployment of my own dotfiles.

## Dependencies
* git
* zsh
* vim

## Installation / Deployment
```
git clone https://github.com/BraveHelyx/dotfog
cd dotfog
./install
/bin/bash $HOME/.dotfiles/mod/bash/fonts/install.sh
chsh -s /bin/zsh
```

## Modules and Submodules
* bash
    * [Powerline Fonts](https://github.com/powerline/fonts)
* zsh
    * [BraveHelyx:zprezto](https://github.com/BraveHelyx/prezto)
* vim
    * [vim-plug](https://github.com/junegunn/vim-plug)
        * [securemodelines](https://github.com/ciaranm/securemodelines)

## User Configuration Files
| Process | Config File | Directory |
| --- | --- | --- |
| zsh | Standard zsh config files (i.e. ~/.zshrc)  | mod/zsh/prezto/runcoms/ |
| zsh | User defined bash/zsh aliases (~/.zalias, ~/.zenviron) | cfg/zsh/ |
| vim | Personalised vim settings and vim-plug. (~/.vimrc | cfg/vim/ |

