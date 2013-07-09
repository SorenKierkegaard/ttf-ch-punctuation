# Maintainer: Peter Russo <kierkegaard.soren.a@gmail.com>
pkgname=ttf-ch-punctuation
pkgver=1.0
pkgrel=1
depends=()
pkgdesc="CollegeHumour custom punctuation"
arch=('any')
url="http://www.collegehumor.com/"
license=('custom:"LICENSE"')
makedepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=$pkgname.install
source=(https://github.com/SorenKierkegaard/$pkgname/blob/master/$pkgname.tar.bz2)
md5sums=('013832b07c046f43abf362ba3a93141f')

package() {
  cd $srcdir
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
  install -Dm644 ttf-ch-punctuation.ttf "$pkgdir/usr/share/fonts/TTF/ttf-punctuation.ttf"
}

