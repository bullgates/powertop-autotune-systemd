pkgname=powertop-autotune-systemd
pkgver=1
pkgrel=1
pkgdesc="Systemd service file for autotuning with PowerTOP"
arch=('x86_64')
url="https://wiki.archlinux.org/index.php/Powertop"
license=('GPL')
depends=('powertop')
source=powertop-autotune.service
md5sums=('6af9eb8a2fba4319862c0765ced5e240')
install=notice.install

package() {
mkdir -p $pkgdir/etc/systemd/system/
cp $srcdir/powertop-autotune.service $pkgdir/etc/systemd/system/
}

