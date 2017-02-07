**Brew cask upgrade utility for Mac OS brew package manager**

The program checks for new versions of installed programs and installs
them if there any.  The main advantage is that a program is uninstalled
before upgrade. It ensures performing of all
necessary cleanup steps that are described in uninstallation script of
the program.

In order to use script, just put ``brew-cask-upgrade``
into ``/usr/local/bin`` and execute
``sudo chmod +x /usr/local/bin/brew-cask-upgrade``. Then simply run
``brew-cask-upgrade`` in the shell.

Use ``brew-cask-upgrade -h`` to get additional info.
