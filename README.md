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

## Mac Settings

### Hide Dock via cli

```
defaults write com.apple.dock autohide -bool true && killall Dock
```

### Make it only appear if you float over it with the mouse for 10 seconds (use 4 fingers up gesture to make it appear)

```
defaults write com.apple.dock autohide-delay -float 10000 && killall Dock
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
