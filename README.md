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

### Shell Commands

    s      <bookmark_name> - Saves the current directory as "bookmark_name"
    go     <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
    p      <bookmark_name> - Prints the directory associated with "bookmark_name"
    delete <bookmark_name> - Deletes the bookmark
    list                 - Lists all available bookmarks

### Example Usage

    $ cd /var/www/
    $ s webfolder
    $ cd /usr/local/lib/
    $ s locallib
    $ list
    $ go web<tab>
    $ go webfolder
