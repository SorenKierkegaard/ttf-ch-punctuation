pkgname=ttf-ch-punctuation
pkgver=1.0
pkgrel=1
depends=('fontconfig' 'xorg-font-utils')
pkgdesc="custom fonts"
arch=('any')
source=(https://github.com/SorenKierkegaard/$pkgname/blob/master/$pkgname.tar.bz2)
install=$pkgname.install
md5sums=('a9a44e37df5b0a8dced5893252eaffdb')

package() {
  install -d "$pkgdir/usr/share/fonts/TTF"
  cp -dpr --no-preserve=ownership "$srcdir/$pkgname/"*.ttf 
"$pkgdir/usr/share/fonts/TTF/"
}

