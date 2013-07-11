# Maintainer: Peter Russo <kierkegaard.soren.a@gmail.com>
pkgname=ttf-ch-punctuation
pkgver=1.0
pkgrel=1
depends=('fontconfig' 'xorg-font-utils')
pkgdesc="CollegeHumour custom punctuation"
arch=('any')
url="http://www.github.com/SorenKierkegaard/$pkgname"
license=('BSD')
install=$pkgname.install
source=(https://github.com/SorenKierkegaard/$pkgname/blob/master/$pkgname.tar.bz2)
md5sums=('03f590999efa99ac3f9aee5a09e0d55b')

package() {
  cd $srcdir
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
  install -Dm644 ttf-ch-punctuation.ttf "$pkgdir/usr/share/fonts/TTF/ttf-punctuation.ttf"
}