## Basic scripts for Dinit on Devuan #Required
## Copyright (C) 2022 Dinit on Devuan
## LISENCE: GPLv3 or later
## Originaly author: Mobin Aydinfar <mobin@mobintestserver.ir>
# Maintainer: Dinit on Devuan Project <mobin@mobintestserver.ir>

pkgname=('dinitscripts')
pkgver=0.1
pkgrel=1
pkgdesc="Service monitoring / "init" system  -- dinit basic scripts"
arch=('any')
url="https://git.mobintestserver.ir/Dinit_on_Devuan/dinitscripts-upstream"
license=('GPLv3')
source=($url/archive/$pkgver.tar.gz)
sha256sums=('8de73ed2ea47614baf85177f4bfe01838b48361ffec54ba41d345aa4c43b5d2f')

package() {
	cd "$pkgdir" && mkdir etc/
	cd "$pkgdir"/etc && mkdir dinit.d/
	cd "$srcdir"/dinitscripts-upstream
	cp -r * "$pkgdir/etc/dinit.d/"
}
