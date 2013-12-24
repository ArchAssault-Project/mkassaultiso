pkgname=mkassaultiso
pkgver=13
pkgrel=1
pkgdesc="Tools for creating ArchAssault live and install iso images"
arch=('any')
url="https://github.com/ArchAssault/mkassaultiso"
license=('GPL')
depends=('archiso')
source=("git+git@github.com:ArchAssault/mkassaultiso.git")
md5sum=("SKIP")

package() {
  cd "$srcdir"
  install -Dm755 "mkassaultiso" $pkgdir/usr/bin/mkassaultiso
}
