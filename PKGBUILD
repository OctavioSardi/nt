# Maintainer: SardiOps <octavio.sardi@proton.me>
pkgname=nt
pkgver=1.0.0
pkgrel=1
pkgdesc="An opinionated bash script to create tasks for Taskwarrior"
arch=('any')
url="https://github.com/OctavioSardi/nt/tree/v1.0.0"
license=('MIT')
depends=('gum' 'fzf')
source=("$pkgname-$pkgver.tar.gz")
md5sums=('SKIP')

build() {
	cd "$pkgname-$pkgver/"
	chmod +x $pkgname
	sudo mv $pkgname /bin/
}

package() {
	echo "Copied nt to /bin"
}
