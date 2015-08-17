# Contributor: max.bra <max.bra at alice dot it>
# Maintainer: max.bra <max.bra at alice dot it>

pkgname=ooo-thumbnailer-unofficial
_pkgrealname=ooo-thumbnailer
pkgver=0.5
pkgrel=6
pkgdesc="This utility provides thumbnails for LibreOffice.org and Microsoft Office documents, presentations, spreadsheets, templates and drawings."
arch=('any')
url="https://launchpad.net/ooo-thumbnailer"
license=('GPL')
depends=('imagemagick' 'xdg-user-dirs' 'ooo-thumbnailer-libgsf')
makedepends=()
optdepends=()
provides=('ooo-thumbnailer')
conflicts=('ooo-thumbnailer')
source=(http://launchpad.net/$_pkgrealname/0.x/$pkgver/+download/$_pkgrealname-$pkgver.tar.gz)
md5sums=('e4559fb5c9a9d1b2ef8edf665303bc6d')

build() {
    /bin/true
}

package() {
    install -D -m755 "$srcdir"/$_pkgrealname-$pkgver/$_pkgrealname "$pkgdir"/usr/bin/$_pkgrealname
    install -D -m755 "$srcdir"/$_pkgrealname-$pkgver/$_pkgrealname.thumbnailer "$pkgdir"/usr/share/thumbnailers/$_pkgrealname.thumbnailer
}

