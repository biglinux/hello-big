# Maintainer: Rafael Neri

pkgname=hello-big
pkgver=1.0.0
pkgrel=0
arch=('any')
license=('MIT')
url="https://github.com/biglinux/hello-big"
pkgdesc="Simple Hello"
depends=('curl')
source=("git+https://github.com/biglinux/hello-big.git")
md5sums=(SKIP)
package() {
    cp -r "${srcdir}/src/usr/" "${pkgdir}/usr/"
}
