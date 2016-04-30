# scode/dotfiles

dotfiles (and similar) along with scripting to set up my personal
preferences.

If you use this and you're not me, audit all changes before using
them. No attempt at release engineering/backwards compatibility is
made.

# How to use it
Intended use is to run, from your home directory (with the path to
your checkout appropriately substituted):

  ./git/rcfiles/setup_env.py

It will set up symlinks to configuration files (and in the future,
possibly due addition things, if it isn't already and I just failed to
update the README to match).

# Configuration

The following files affect the behavior of either the setup script or
the scripts it installs:

## ~/.config/scode/dotfiles/kbdtype

Contains the keyboard type. See dotfiles/xkb/*.xkb for available
types.

## ~/.config/scode/dotfiles/profile

Name of host profile (oryxpro, chromebook, ...).