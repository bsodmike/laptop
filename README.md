Laptop
======

Laptop is a script to set up a Mac OS X laptop for development,
primarily in Ruby, Python, and Node.

Requirements
------------

1) Install a C compiler.

Use [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) for
Snow Leopard (OS X 10.6).

Use [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action)
for Lion (OS X 10.7) or Mountain Lion (OS X 10.8).

2) Set zsh as your login shell.

    chsh -s /bin/zsh

Install
-------

Run the script:

    zsh <(curl -s https://raw.github.com/bsodmike/laptop/bsodmike/mac)

What it sets up
---------------

* Download my dotfiles (and other temp files) to ~/.boostrap_laptop.
This folder can be deleted later on.
* Set my Git config
* Install OH MY ZSHELL! with my config
* Enable Solarized Dark theme for Terminal
* Install [Carlhuda's JANUS](https://github.com/carlhuda/janus) with [my
personalisations](https://github.com/bsodmike/dotfiles/tree/master/vim)
and [plugins](https://github.com/bsodmike/janus).
* Bundler gem for managing Ruby libraries
* Exuberant Ctags for indexing files for vim tab completion
* Foreman gem for serving Rails apps locally
* Homebrew for managing operating system libraries
* ImageMagick for cropping and resizing images
* Postgres for storing relational data
* Postgres gem for talking to Postgres from Ruby
* Qt for headless JavaScript testing via Capybara Webkit
* Rails gem for writing web applications
* Rbenv for managing versions of the Ruby programming language
* Redis for storing key-value data
* Ruby Build for installing Rubies
* Ruby stable for writing general-purpose code
* The Silver Searcher for finding things in files
* Tmux for saving project state and switching between projects
* Watch for periodically executing a program and displaying the output
* Python (Framework), pip, virtualenv, virtualenvwrapper
* Node and npm

It should take less than 15 minutes to install (depends on your machine).

Credits
-------

This is a [fork of Laptop](https://github.com/bsodmike/laptop) by
[thoughtbot, inc](http://thoughtbot.com), modified for my personalised
development setup.

License
-------

This project rocks and uses MIT-LICENSE.
