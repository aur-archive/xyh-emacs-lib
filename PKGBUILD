
# Maintainer: XIE Yuheng <xyheme@gmail.com>

pkgname=xyh-emacs-lib
pkgver=20140731
pkgrel=1
epoch=
pkgdesc="some emacs functions written by XIE Yuheng"
arch=('any')
url="https://bitbucket.org/xieyuheng/xyh-emacs-lib"
license=('ISC')
groups=()
depends=('emacs' 'mercurial')
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=('hg+https://bitbucket.org/xieyuheng/xyh-emacs-lib')
noextract=()
md5sums=('SKIP')

package() {
  cd "$srcdir/$pkgname/"
  install -d $pkgdir/usr/share/emacs/site-lisp/
  # install the files in directory created above
  install -m644 xyh-emacs-lib.el -t $pkgdir/usr/share/emacs/site-lisp/
  }
