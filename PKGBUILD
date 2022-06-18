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
source=(${_base_url}/363f0284-ac75-47a5-8cf9-3e1d4f6b62c7)
sha256sums=('5245a159cc4684200e2f38b6b59089494e3d3af68f18b302ff77342a790ea57e')

package() {
	cd "$pkgdir" && mkdir etc/
	cd "$pkgdir"/etc && mkdir dinit.d/
	cd "$srcdir"/
	cp -r * "$pkgdir/etc/dinit.d/"
}