zshmarks
========

A port of [Bashmarks (by huyng)](https://github.com/huyng/bashmarks), a directory bookmarks for the oh-my-zsh

### How to install

* Download the script or clone this repository in [oh-my-zsh](http://github.com/robbyrussell/oh-my-zsh) plugins directory:

        cd ~/.oh-my-zsh/custom/plugins
        git clone https://github.com/linux-china/zshmarks.git

* Activate the plugin in `~/.zshrc`:

        plugins=( [plugins...] zshmarks [plugins...])

* Source `~/.zshrc`  to take changes into account:

        source ~/.zshrc

### Differences with Bashmarks
Because some conflicts with oh-my-zsh and git plugin, changes as following:

* g -> go
* d -> delete
* l -> list
