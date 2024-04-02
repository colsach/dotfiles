# My dotfiles

This directory contains the dotfiles for my system

## Requiremetns

Ensure you have the following installed on your system

### Git

```
sudo apt-get install git
```

### Stow

```
sudo apt-get install stow
```

## Installation

First, check out the dotfiles repo in your `$HOME` direrctory using git
and then use GNU stow to create symlinks

```
git clone https://github.com/colsach/dotfiles
cd dotfiles
stow .
```


