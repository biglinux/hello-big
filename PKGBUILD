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
    cp -r "${srcdir}/usr/" "${pkgdir}/"
    mv "${pkgdir}/usr/lib/python3/dist-packages/bbv/" "${pkgdir}/usr/lib/python3.9/bbv/"
    ln -s /usr/share/bigbashview/bcc/apps/big-store/big-store-start.sh /usr/bin/big-store
}
