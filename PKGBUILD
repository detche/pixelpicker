# Maintainer: Guillaume Detcheverry <g@detche.fr>
pkgname=pixelpicker
pkgver=1.0.0
pkgrel=1
pkgdesc="Prints color of a pixel after a click on the screen."
arch=(any)
url="https://github.com/detche/pixelpicker"
license=('MIT')
depends=(python-gobject python-cairo)
source=(pixelpicker)
sha256sums=(fd11fa1195a3041091ea987c606cb45aa6572953521798717ea337bfb45657c4)

package() {
    install -Dm0755 -t "$pkgdir/usr/bin/" "$pkgname"
}
