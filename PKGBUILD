# Maintainer: Moritz Lipp <mlq@pwmt.org>

_pkgname=Flask-Creole
pkgname=python2-flask-creole
pkgver=0.4.4
pkgrel=1
pkgdesc="Creole parser filters for Flask"
arch=(any)
url="http://packages.python.org/Flask-Creole/"
license=('BSD')
depends=('python2' 'python2-flask' 'python2-creoleparser')
makedepends=('python2-distribute')
source=("http://pypi.python.org/packages/source/${_pkgname:0:1}/$_pkgname/$_pkgname-$pkgver.tar.gz")
md5sums=('f630ba5018c0a2ecf480bf30b506d05c')

package() {
  cd "$srcdir/$_pkgname-$pkgver"
  python2 setup.py install --root="$pkgdir/" --prefix=/usr --optimize=1
}

# vim:set ts=2 sw=2 et:
