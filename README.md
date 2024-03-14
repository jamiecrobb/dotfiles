# Jamie's dotfiles
This directory contains my system dotfiles

## Requirements

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

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/jamiecrobb/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```

## Credits
Repository inspired by [Dreams of Autonomy](https://www.youtube.com/watch?v=y6XCebnB9gs)

