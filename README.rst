**Brew cask upgrade utility for Mac OS brew package manager**

The script checks for new versions of installed programs and installs
them if there any.  The main advantage is that a program is uninstalled
before upgrade. It ensures performing necessary cleanup steps that are
described in uninstallation script of the program.

To use script, just put ``brew-cask-upgrade`` into ``/usr/local/bin``
and execute ``sudo chmod +x /usr/local/bin/brew-cask-upgrade``.
Then simply run ``brew-cask-upgrade`` in the shell. No additional
packages are needed.

Use ``brew-cask-upgrade -h`` to get additional info.

The script is tested in Python 2.7/3.4-3.6.
