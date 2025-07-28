# My personal dotfiles

My personal dotfiles. Its heavy inspired by [Mathias Bynens](https://github.com/mathiasbynens/dotfiles) and [Freek](https://freek.dev/uses).

It contains the installation of some basic tools, some handy aliases and functions.

You can install them by cloning the repository and running the bootstrap script.

## Option 1: Clone to home directory (recommended)

```bash
cd ~
git clone git@github.com:alies-dev/dotfiles.git .dotfiles
```

## Option 2: Clone anywhere and create symlink

You can clone the repository to any location and create a symlink to your home directory:

```bash
# Clone to any directory (e.g., ~/code/dotfiles)
git clone git@github.com:alies-dev/dotfiles.git ~/code/dotfiles

# Create symlink from home directory
ln -s ~/code/dotfiles ~/.dotfiles
```

The bootstrap script can be run by cd-ing into the `.dotfiles` directory and performing this command:

```bash
cd ~/.dotfiles
./bootstrap
```

![screenshot](https://freekmurze.github.io/dotfiles/screenshot.png)
