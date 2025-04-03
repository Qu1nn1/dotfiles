# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed

### Git

```
brew install git
```

### Stow

```
brew install stow
```

### Tmux

```
brew install tmux
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## Installation

First, copy the dotfiles repo into $HOME using git

```
$ git clone git@github.com/Qu1nn1/dotfiles.git
$ cd dotfiles
```

then use stow to create symlinks

```
$ stow .
```
