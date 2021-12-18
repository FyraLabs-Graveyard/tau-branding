pkgname=tau-branding
pkgver=0.1.0
pkgrel=1
pkgdesc="Tau branding assets"
arch=("x86_64")
url="https://tau.innatical.com/"
license=("GPL3")
depends=()
source=("https://github.com/tauLinux/tau-branding.git")
sha256sums=("SKIP")

package() {
    mkdir -p "$pkgdir"/etc
    cp os-release "$pkgdir"/etc/os-release
}