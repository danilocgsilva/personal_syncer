# Documentation

Sync files from the computer to some generic destiny.

The psyncer must works as a utility that will holds several commands, like git or cordova. So, sometimes you will just synchronizes the things (the program main task). Meanwhile you must add new files to syncronizes. In another time, you will the configuration file. And so on.

## Concept

The source is the actual computer, that will have several directories that you want to backup and keep offline. The destiny is where you make your backup and synchronization, and it can be an arbitrary local folder, a local hd, a pendrive, an external hd, a folder in a pendrive or so on.

Through a configuration user file (actually, a unix-like pattern), there's a map from the local computer that will list all the sources. By while, you always will provides as parameter the backup destiny.