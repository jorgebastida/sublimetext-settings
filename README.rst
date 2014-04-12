My Sublime Text 3 Preferences
-----------------------------

* Install Sublime Text 3 - http://www.sublimetext.com/3
* Install Sublime Package Control - https://sublime.wbond.net/installation

* Clone this repo::

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
    $ rm -Rf User
    $ git clone git@github.com:jorgebastida/sublimetext-settings.git User

* Install these packages using ``Sublime Package Control``:
 * ``Theme - Spacegray`` Quite more appealing theme
 * ``GitGutter`` Show +- close to each line number
 * ``Gist`` Create gists form the editor
 * ``SideBarEnhancements`` File/Folder actions in the sidebar
 * ``LESS`` Less highlighting
 * ``Puppet`` Puppet highlighting
 * ``Djaneiro`` Django snippets
 * ``Hex​Viewer`` Hex​ view/edits
 * ``INI`` INI syntax highlighting
 * ``GitHubinator``
 * ``SublimeLinter``
 * ``SublimeLinter-pep8``
 * ``SublimeCodeIntel``


SublimeCodeIntel works "out the box" but if you want to add more virtualenvs, you can edit ``~/.codeintel/config`` adding::

    {
    "Python": {
        "python": '/usr/bin/python',
        "pythonExtraPaths": ['/virtualenvs/streetlife/bin']
        }
    }
