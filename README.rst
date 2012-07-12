My Sublime Text 2 Preferences
-----------------------------

* Install Sublime Text 2 - http://www.sublimetext.com/2
* Install Sublime Package Control - http://wbond.net/sublime_packages/package_control
* Install these packages: ``SublimeCodeIntel`` ``SublimeLinter`` ``Theme - Soda`` ``Gist`` ``GitHubinator``


Clone this repo::

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User
    $ git clone https://jorgebastida@github.com/jorgebastida/sublimetext2-settings.git


Create/Edit ``~/.codeintel/config``::

    {
    "Python": {
        "python": '/usr/bin/python',
        "pythonExtraPaths": ['/Users/jorge/virtualenvs/streetlife/bin']
        }
    }
