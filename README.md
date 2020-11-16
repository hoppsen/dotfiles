# dotfiles

This repository contains the dotfiles of an iOS developer. :iphone:

## Installation

Personally, I use this repository as a submodule of my [macOS setup routine](https://github.com/hoppsen/macos-setup).

> :warning: **WARNING!** The following installation commands will overwrite your existing dotfiles in your home directory! Don't use them blindly unless you know what that entails. I would suggest to review the code, maybe even fork and adapt to your own needs. But definitely backup your existing files before installing.

### Using Git

#### **Overwrite** your existing dotfiles with the one from this repository:

```bash
git clone https://github.com/hoppsen/dotfiles.git ~/.dotfiles
cp ~/.dotfiles/* ~/ 
source ~/.zshrc # to reload your zsh file
```

#### To update your dotfiles with the latest changes:

```bash
cd ~/.dotfiles/
git pull
cp ~/.dotfiles/* ~/
. ~/.zshrc # a shorter command for reloading
```

## Inspired by:

* [dotfiles](http://dotfiles.github.io/) - Your unofficial guide to dotfiles on GitHub.
* [Felix Krause](https://github.com/KrauseFx/dotfiles) and his dotfiles repository
* [Kevin Pabst](https://github.com/kevinpapst/dotfiles) and his dotfiles repository
* [Mathias Bynens](https://github.com/mathiasbynens/dotfiles) and his dotfiles repository
* [tutsplus tutorial](http://net.tutsplus.com/tutorials/tools-and-tips/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles/) on how to get started with dotfiles