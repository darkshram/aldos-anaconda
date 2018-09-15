# aldos-anaconda
Aldos-anaconda is the program which is used to install ALDOS. It's based on Fedora's anaconda 14.22. These files are of little use on an already installed system or other Linux distributions.

To install just run:

``
autoreconf -fi

``
``
./configure --prefix=/usr
``
``
make
``
``
make install
``

Things to be done:

- Currently works only with NetworkManager < 1.1. Needs to be ported to NetworkManager >= 1.4. NetworkManager 1.8 packages are available in ALDOS-plus repository.
- Needs to be ported to pygobject and GTK+ 3.

Any help is welcome.
