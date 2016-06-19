# Package build for RTKlib
An archlinux pkgbuild for RtkLib

RTKLIB is an open-source program for GNSS positioning

# How to use it :

cd /tmp/

git clone git://github.com/giscan/rtklib_pkgbuild.git

cd rtklib_pkgbuild

makepkg

pacman -U rtklib_2.4.3*
