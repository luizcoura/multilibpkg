multilibpkg
===========

Slackware Multilib Pakage Manager (http://alien.slackbook.org/dokuwiki/doku.php?id=slackware:multilib)


# Installation

    $ git clone https://github.com/luizcoura/multilibpkg.git
    $ mkdir -p /var/lib/multilibpkg
    $ mkdir -p /var/cache/multilibpkg

# Usage

    $ cd multilibpkg
    $ ./multilibpkg help
    usage: ./multilibpkg command

      u | update            Build repository index locally.
      d | download          Download packages only, do not install.
      i | install           Download and install packages.
      h | help              Show this help.
