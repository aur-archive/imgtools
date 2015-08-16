# Maintainer: trile7 at gmail dot com

pkgname=imgtools
pkgver=0.1.1
pkgrel=3
pkgdesc="Various basic image operations based imagemagick"
url="http://bashscripts.googlecode.com"
arch=('i686' 'x86_64')
license=('GPL3')
depends=(imagemagick coreutils bash)
optdepends=("xorg-xrandr: determine monitor size for wallpaper" "xorg-xdpyinfo: determine monitor size for wallpaper" "xorg-xprop: determine monitor size for wallpaper")
source=($url/files/$pkgname-$pkgver.tar.gz)

package() {
  mkdir -p "$pkgdir/usr/share/$pkgname"
  mkdir -p "$pkgdir/usr/bin"
  cp "$srcdir/$pkgname-$pkgver"/* "$pkgdir/usr/share/$pkgname"
  mv "$pkgdir/usr/share/$pkgname/$pkgname" "$pkgdir/usr/bin"
}

md5sums=('aff0b36c1f8939ebe79dda21bd62f96c')
