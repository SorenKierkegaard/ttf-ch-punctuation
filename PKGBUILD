# Maintainer: Peter Russo <kierkegaard.soren.a@gmail.com>
pkgname=ttf-ch-punctuation
pkgver=1.0
pkgrel=1
depends=('fontconfig' 'xorg-font-utils')
pkgdesc="CollegeHumour custom punctuation"
arch=('any')
url="http://www.collegehumor.com/"
license=('Custom:Proprietary')
makedepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=$pkgname.install
source=(https://github.com/SorenKierkegaard/$pkgname/blob/master/$pkgname.tar.bz2)
md5sums=('5957596e5858cfd30326356a45764a2a')

build () {
  cd "$srcdir"
  pwd
}

package() {
  cd $srcdir
  install -Dm644 ttf-ch-punctuation.ttf "$pkgdir/usr/share/fonts/TTF/ttf-punctuation.ttf"
}

