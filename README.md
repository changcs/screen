# screen
screen terminal multiplexor with VT100/ANSI terminal emulation

To build the deb file, run
$ apt-get install libncursesw5-dev libpam0g-dev debhelper dpatch
$ export LANG=C LC_CTYPE=C
$ dpkg-buildpackage -rfakeroot -b
