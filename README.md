-------------------
Installing Kaffeine
-------------------

The following development headers are needed (recommended versions):
* Qt >= 4.6
* KDE >= 4.4
* libX11
* libXss

For the translations you need:
* gettext

Create an empty build directory and do the following steps:
# cmake <path/to/kaffeine/source/directory> <options>
# make
# make install

Useful options include:
* -DCMAKE_BUILD_TYPE=<type> (Debug or Release)
* -DCMAKE_INSTALL_PREFIX=<path> (installation prefix for Kaffeine, e.g. /usr)

For further information look for generic KDE4 / cmake instructions.

--------
Homepage
--------

http://kaffeine.kde.org

-------
Authors
-------

Maintainer:
  Fabien R <theedge456(at)free.fr>

Former maintainers:
  Christoph Pfister <christophpfister@gmail.com>
  Christophe Thommeret
  Jürgen Kofler

Thanks to various contributors, translators, testers ...
