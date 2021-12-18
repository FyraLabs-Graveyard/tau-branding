pkgname=tau-branding
pkgver=0.0.1
pkgrel=1
pkgdesc="Tau branding assets"
arch=("x86_64")
url="https://tau.innatical.com/"
install=tau-branding.install
license=("GPL3")
depends=()
source=("os-release" "tau-logo.png" "tau-logo.svg" "tau-logo-text.png" "tau-logo-text.svg")
sha256sums=("SKIP" "SKIP" "SKIP" "SKIP" "SKIP")

package() {
    mkdir -p "$pkgdir"/etc "$pkgdir"/usr/share/pixmaps
    cp "$srcdir"/os-release "$pkgdir"/etc/os-release.new
    cp "$srcdir"/*.{png,svg} "$pkgdir"/usr/share/pixmaps
}