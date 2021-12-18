pkgname=tau-branding
pkgver=0.0.1
pkgrel=1
pkgdesc="Tau branding assets"
arch=("x86_64")
url="https://tau.innatical.com/"
install=tau-branding.install
license=("GPL3")
depends=()
source=("os-release")
sha256sums=("SKIP")

package() {
    mkdir -p "$pkgdir"/etc
    cp "$srcdir"/os-release "$pkgdir"/etc/os-release.new
}