dotfiles
========

A collection of common settings files.

* Bash - .bash-settings
* Bash - git-completion.bash
* iTerm2 - monokai-soda.itermcolors
* Sublime Text 2 - Preferences.sublime-settings

usage
=====

.bashrc
-------

if [ -f ~/Projects/dotfiles/.bash-settings ]; then
   source ~/Projects/dotfiles/.bash-settings
fi

.bash_profile
-------------

if [ -f ~/.bashrc ]; then
   source ~/.bashrc
fi

git-completion.bash
-------------------

Included in .bash-settings.

monokai-soda.itermcolors
------------------------

Run in Finder, load in Profiles>Color>Presets.

Prefences.sublime-settings
--------------------------

Sublime user settings.