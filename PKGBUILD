pkgname=shiftstate
pkgver=0.0.1
pkgrel=1
pkgdesc="A simple C program that returns the ioctl call shift_state."
arch=('i686' 'x86_64')
url="https://joserebelo.me"
license=('GPL3')
source=("shiftstate.c")
sha256sums=('SKIP')

build() {
    gcc shiftstate.c -o shiftstate
}

package() {
    install -Dm755 shiftstate "$pkgdir"/usr/bin/shiftstate
}
