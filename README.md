# Dotfog
Easily deployed dotfile bootstrap. 
Uses [dotbot](https://github.com/anishathalye/dotbot) as a means of tracking a robust deployment of my own dotfiles.

## Dependencies
* git
* zsh

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
    - Powerline Fonts (https://github.com/powerline/fonts)
*  zsh
    - zprezto fork (https://github.com/BraveHelyx/prezto)
