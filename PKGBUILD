_mode=cross
_nodeps=true
pkgname=flavour-plasma-minimal
pkgdesc="Kupfer flavour: The qt-based KDE desktop environment (minimal edition)"
pkgver=1.0
pkgrel=1
_arches=all
arch=(
    x86_64
    aarch64
    armv7h
)
license=(GPL3)
depends=(
    plasma-meta
    plasma-wayland-session
    sddm
    networkmanager
)
source=(
    plasma.txt
)
sha256sums=(
    SKIP
)

package() {
    install -Dm644 "$srcdir"/plasma.txt "$pkgdir"/etc/kupfer/systemd/plasma.txt
}
