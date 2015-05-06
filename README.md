# Flotilla Provisioner

Flotilla is a set of ansible tasks to setup a new server in a consistent way.

Software installer is:

- PHP 5.6
- Apache 2.4
- MySQL 5.6
- Vim
- Git
- Curl
- Composer

It also sets the timezone and locale to GB (UTC), sets up the PHP.ini file  to be suitable for development (E_ALL & errors on).

In the future it will be extendible by custom task files, as well as the core; to be called after all of the core provisioner files are called.

There are several handlers callable by custom tasks by default.

These are (as written): 
- restart apache
