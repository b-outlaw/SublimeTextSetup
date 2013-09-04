Sync only the Packages/User/ folder. This folder contains the Package Control.sublime-settings file, which includes a list of all installed packages. If this file is copied to another machine, the next time Sublime Text is started, Package Control will install the correct version of any missing packages.

Certain files and folders in the Packages/User/ folder change regularly, so you may want to add them to a .gitignore file. There is really no harm in syncing these, however some of them change on an hourly basis, which may result in having to run more Git commands. Examples include:

* Package Control.last-run
* Package Control.ca-list
* Package Control.ca-bundle
* Package Control.system-ca-bundle
* Package Control.cache/
* Package Control.ca-certs/