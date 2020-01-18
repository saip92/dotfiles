# My Personal Dotfiles

This repository houses my personal dotfiles which uses `chezmoi` to manage them

## Prerequistes

The following packages are expected to be installed _for now_

- curl
- [zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)
- [chezmoi](https://www.chezmoi.io/docs/install/)
- [Hack Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Hack)

## First Time Setup

```sh
chezmoi init https://github.com/saip92/dotfiles.git
chezmoi apply
```

## Update Dotfiles

```sh
chezmoi update
```