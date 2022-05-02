# Maintainer: Javi Serrano <javiserranoie@gmail.com>
pkgname=rofi-notes
pkgver=1.0
pkgrel=1
epoch=
pkgdesc="Rofi notes service"
arch=(x86_64)
url="https://github.com/javierserranoie/rofi-notes"
license=('MIT')
groups=()
depends=('detox' 'xfce4-terminal' 'rofi' 'neovim' 'inotify-tools')
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("$pkgname-$pkgver.tar.gz")
noextract=()
md5sums=()
validpgpkeys=()

build() {
	cd "$pkgname-$pkgver"
	./configure	
	make
}

package() {
	cd "$pkgname-$pkgver"
	make DESTDIR="$pkgdir/" install
}
sha256sums=('eb2d8c73dfc91a856cc76a75f9fb5bb2e34152647e23f040f27b7fc3eb10cdd3')
