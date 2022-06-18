## Basic scripts for Dinit on Devuan #Required
## Copyright (C) 2022 Dinit on Devuan
## LISENCE: GPLv3 or later
## Originaly author: Mobin Aydinfar <mobin@mobintestserver.ir>
# Maintainer: Dinit on Devuan Project <mobin@mobintestserver.ir>

pkgname=('dinitscripts')
pkgver=1.0
pkgrel=1
pkgdesc="Service monitoring / "init" system  -- dinit basic scripts"
arch=('any')
url="https://git.mobintestserver.ir/Dinit_on_Devuan/dinitscripts"
_base_url="https://git.mobintestserver.ir/attachments"
license=('GPLv3')
source=(${_base_url}/2684d0cb-52b1-4d28-8aea-bd27f39e75f2)
sha256sums=('a0c8a3dba48769ea58889408a79c491077614baac4c34e0eaa906166385f15d5')

package() {
	cd "$pkgdir" && mkdir etc/
	cd "$pkgdir"/etc && mkdir dinit.d/
	cd "$srcdir"/
	cp -r * "$pkgdir/etc/dinit.d/"
}