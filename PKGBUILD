# Maintainer: Bernhard Landauer <oberon@manjaro.org>

pkgname=i3-scrot
pkgver=1.0
pkgrel=1
pkgdesc="simple screenshot script using scrot"
arch=('any')
url="https://forum.manjaro.org/index.php?topic=31977.msg261964#msg261964"
license=('GPL')
depends=('libnotify'
	'scrot'
	'xclip'
	'xdg-user-dirs')
source=('i3-scrot')
md5sums=('8b5377c62549c8ca0ffee63bc7a097bb')

package() {
  install -Dm755 "$srcdir/$pkgname" "$pkgdir/usr/bin/$pkgname"
}
